# xkb
Author: jamcha (jamcha.aa@gmail.com)

These are modified key settings under a Unix-like Environment. These programs are based on the article of [tetsuran](http://qiita.com/tetsutan/items/bfa5768c3d618ca35d4a).

## Modification key (jp keyboard)

- Muhenkan -> Ctrl
- Henkan -> Esc
- sands (temporal sticky-shift, see https://en.wikipedia.org/wiki/Modifier_key#Dual-role_keys)

### Attention

When you use my [init](https://github.com/jamcha-aa/init)'s skk-stickey-key, edit .xkb/symbols/myswap as below;

- enable CapsLock to Muhenkan
- Or disable Muhenkan to Ctrl

Otherwise, a Ctrl key modification conflicts with skk-sticky-key.

## Modification key (us keyboard, but considerably private settings)

- Alt_L -> Ctrl
- CapsLock -> F12 (just for my [init](https://github.com/jamcha-aa/init)'s skk-stickey-key)
  + You can remove this setting by editing symbols/myswap.
- sands (temporal sticky-shift, see https://en.wikipedia.org/wiki/Modifier_key#Dual-role_keys)

## Install

1. Install xcape.
2. Rename either "jp" or "us" to ".xkb" (don't forget a period).
3. Copy .xkb, xkb_startup.sh, and sands.sh to your home directory.
4. Open terminal, then type

   chmod 755 xkb_starup.sh sands.sh

## Usage

When you login, click xkb_startup.sh and sands.sh or open terminal then type

     bash xkb_startup.sh

     bash sands.sh


## Reference
http://qiita.com/tetsutan/items/bfa5768c3d618ca35d4a

### License
Qiita Terms of Service. (https://qiita.com/terms)

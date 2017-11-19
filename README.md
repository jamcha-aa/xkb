# xkb
Author: jamcha (jamcha.aa@gmail.com)

These are modified key settings for jp keyboards under a Unix-like Environment. These programs are based on the article of [tetsuran](http://qiita.com/tetsutan/items/bfa5768c3d618ca35d4a).

## Modified key

- Muhenkan -> Ctrl
- Henkan -> Esc
- sands (temporal sticky-shift, see https://en.wikipedia.org/wiki/Modifier_key#Dual-role_keys)

## Install

1. Install xcape.
2. Copy .xkb, xkb_startup.sh, and sands.sh to your home directory.
3. Open terminal, then type

   chmod 755 xkb_starup.sh sands.sh

## Usage

When you login, click xkb_startup.sh and sands.sh or open terminal then type

     bash xkb_startup.sh

     bash sands.sh

### Attention

When you use my [init](https://github.com/jamcha-aa/init)'s skk setting, edit .xkb/symbols/myswap as below:

- enable CapsLock to Muhenkan
- Or disable Muhenkan to Ctrl

Otherwise, a Ctrl key modification conflicts with skk-stickey-key.

## Reference
http://qiita.com/tetsutan/items/bfa5768c3d618ca35d4a

### License
Qiita Terms of Service. (https://qiita.com/terms)

# Minimal clone
```
git clone --depth=1 -b andyvorld --filter=tree:0 git@github.com:andyvorld/qmk_firmware.git
cd qmk_firmware
git sparse-checkout set --no-cone '/*' '\*' '!keyboards' 'keyboards/keychron'
git checkout
```
Build Steps:

```
export PICO_BOARD=waveshare_rp2040_zero

export PICO_SDK_PATH=$HOME/repos/pico-sdk

cmake -DFAMILY=rp2040 pico .

make
```

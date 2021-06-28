# PWMtest
PWM test code for [Nucleo F446 RE](https://os.mbed.com/platforms/ST-Nucleo-F446RE/)


## Requirements

### Ubuntu
```bash
 $ sudo apt install gcc-arm-none-eabi openocd
```

### Fedora
```bash
 $ sudo dnf install arm-none-eabi-gcc arm-none-eabi-newlib openocd
```


## Build
```bash
 $ cd <PROJECT_ROOT>
 $ make
```

## Burn to Nucleo
1. Connect Nucleo to PC
2. burn
```bash
 $ make burn
```

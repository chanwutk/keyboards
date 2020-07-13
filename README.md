# Layout config for my keyboard

## To edit this firmware
1. visit [qmk configurator](https://config.qmk.fm/#/keebio/iris/rev3/) for iris rev3
2. import keymap `.json` file
3. edit the layout
4. click compile
5. download the compiled firmware in `.hex`

## To flash the firmware
1. connect your keyboard to your computer
2. open QMK Toolbox
3. click open and locate your `.hex` file
4. MCU is `atmega32u4`
5. put your keyboard to DFU mode by pressing the reset button under the keyboard until the console says that your keyboard is in DFU mode
6. click flash
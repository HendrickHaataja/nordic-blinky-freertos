# nordic-blinky-freertos

This project is a modified version of the blinky_freertos example in Nordic Semiconductor's sdk_15.0.0. Two additonal 
tasks were added to blink BSP_LED1 and BSP_LED2 on the nRF52dk and nRF52840pdk at one-half and one-third the frequency of
BSP_LED0. It has been tested on the nRF52dk, the nRF52840dk, and Electronic Realization's puck (a custom board).
It has only been tested using the gcc toolchain.

### Installing
It is assumed that you have already installed the nRF5_SDK_15.0.0, and set up the toolchain.
This project should be cloned into <YOUR_SDK_LOCATION>/nRF5_SDK_15.0.0/examples/peripheral/

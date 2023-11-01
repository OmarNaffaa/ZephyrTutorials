# Videos 1 and 2 - Blinking LED

Blinking LED implementation. Includes device tree overlay for GPIO pin 25

## Build Steps:
- (1) Create directory under Zephyr root and files in this repo (e.g. ".../zephyrproject/helloworld")
- (2) In created directory run the command "west build -b esp32_devkitc_wroom"

## Flashing Device:
- (1) Change directories to folder containing build
- (2) Use the command "west flash", which will flash the build onto board
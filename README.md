# STM32-RUST 
## start project
```
cargo generate --git https://github.com/sisrsis/stm32-rust
```
## run project 
```
cd <neme project>
cargo run
```
## create file build
```
arm-none-eabi-objcopy -O ihex -R .eeprom .\target\thumbv7m-none-eabi\debug\<name project file > <name file>.hex
```

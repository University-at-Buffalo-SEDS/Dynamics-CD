# Dynamics-Computer-Firmware

This is the firmware for the Dynamics Computer. Used for parachute drop tests.

## Expected Use Case

- Drop from building
- Deploy FruityChuteTM Tender Descender
- Deploy before hit ground

## What is needed

- [ ] Drop activation logic
- [ ] BMI088 IMU
- [ ] BMP390 BARO
- [x] W25Q32 FLASH
- [ ] Using USB to output data
- [ ] Make a board variant for STM32G431

*Board variants makes it so platformIO knows how to build and upload for the STM32G431 since we are using a bit of a custom design.

## Contributions

To make contributions please fork the repo so that you have your own copy to modify.

Then make a branch with the name of the changes/additions that you have.

Work in the branch making commits to checkpoint your work and once finished and satified you can make a pull request.

We can then review it and make sure it works (or at least compiles).

# Datasheets

[STM32G431 MCU](https://www.st.com/en/microcontrollers-microprocessors/stm32g431c8.html)

[BMI088 IMU](https://www.bosch-sensortec.com/products/motion-sensors/imus/bmi088/#documents)

[BMP390 BARO](https://www.bosch-sensortec.com/media/boschsensortec/downloads/datasheets/bst-bmp390-ds002.pdf)

[W25Q32JV 32Mb Flash](https://www.winbond.com/hq/product/code-storage-flash-memory/serial-nor-flash/?__locale=en&partNo=W25Q32JV)

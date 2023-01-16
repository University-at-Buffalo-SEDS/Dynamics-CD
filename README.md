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
- [ ] Make a board variant for STM32G431

*Board variants makes it so platformIO knows how to build and upload for the STM32G431 since we are using a bit of a custom design.

## Contributions

To make contributions please fork the repo so that you have your own copy to modify.

Then make a branch with the name of the changes/additions that you have.

Work in the branch making commits to checkpoint your work and once finished and satified you can make a pull request.

We can then review it and make sure it works (or at least compiles).

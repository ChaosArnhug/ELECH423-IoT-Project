# ELEC-H423 Labs Course Project

The purpose of this repository is to archive and provide future students with the report and source code submitted for the ELEC-H423 labs course project at ULB.

**Note**: This project successfully passed the course.

# Usage

The code can be flashed directly onto one of the ESP32 boards, provided that the WiFi, pin, and key constants have been adjusted to match your setup.
Some modifications are required for the second ESP32, particularly to the constant values, but also to how those constants are used in several functions. 
For example, occurrences of `COMMIT_ESP_1` should be replaced with `COMMIT_ESP_2` when building the firmware for the second ESP32.

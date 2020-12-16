# raspotemp

Script to print current temperature of CPU, GPU and CPU frequency on Raspberry devices.

It works on Raspberry model 2 and model 3B+. 
It probably works on other models too without changes.

## Requirements

libraspberrypi-bin must be installed.

`$ sudo apt install libraspberrypi-bin`

## Usage

`temp` can be run as not privileged user.

```
$ temp
CPU temp=36.4'C
GPU temp=37.0'C
FREQ 600 Mhz
```

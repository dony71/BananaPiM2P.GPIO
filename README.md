# BananaPiM2P.GPIO

This is a modified version of **RPi.GPIO** for Banana Pi M2+ Boards.

It is based on the original [RPi.GPIO](https://pypi.python.org/pypi/RPi.GPIO).

## Installation

#### With PIP

    sudo pip install BananaPiM2P.GPIO

#### Manual

    sudo apt-get update
    sudo apt-get install python-dev git
    git clone https://github.com/dony71/BananaPiM2P.GPIO.git
    cd /BananaPiM2P.GPIO
    sudo python setup.py install

## Supported Boards

* OPi ZERO
* OPi ZERO PLUS
* OPi ZERO PLUS2 H3
* OPi ZERO PLUS2 H5
* OPi R1
* OPi PC & PC PLUS
* OPi ONE
* OPi LITE
* OPi PC2
* OPi PRIME
* BPi M2 PLUS

## Usage

Same as RPi.GPIO but with a new function to choose BananaPi M2+ Board.

    import BPi.GPIO as GPIO
    GPIO.setboard(GPIO.M2P)
    GPIO.setmode(GPIO.BOARD)
    GPIO.output(5, 1)

Many demo is on the example folder

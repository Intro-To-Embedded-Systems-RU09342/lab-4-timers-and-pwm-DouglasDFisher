The goal of this project is to write the debouncing code so that a single button press isn't read multiple times. This is done by having a button enable a timer and disable itself, and then the timer will reenable the button interrupt.

The difference between the two is that the FR6989 has to have is default high impedance state disabled, and the button's pullup resistor needs to be enabled.
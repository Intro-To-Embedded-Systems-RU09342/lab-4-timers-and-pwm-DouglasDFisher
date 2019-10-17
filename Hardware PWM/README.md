This project has a button control the duty cycle length which blinks an LED. This is done using the hardware PWM modules versus the software PWM of the previous project.

The difference between the two is that the FR6989 has to have is default high impedance state disabled, and the button's pullup resistor needs to be enabled.
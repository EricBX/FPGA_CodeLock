# FPGA_CodeLock

### Basic functions:

- After pressing BTN2, enter **4-bits password mode**: Please switch SW7~SW4 to set the default password, SW3~SW0 to enter the password to be verified. The digital tube displays the input status and judgment result (TRUE or FALS) in turn. (No need to trigger buttons)

### Expanding function:

- After pressing BTN0, enter **8-bits default password mode** (default state after booting): Please switch SW7~SW0 to set the default password. The digital tube shows "COdE", the high 4-bits default password (SW7~SW4), and the low 4-bits default password (SW3~SW0) in turn.

- After pressing BTN1, enter **8-bits input password mode**: Please switch SW7~SW0 to input the password to be verified. The digital tube displays the judgment result (TRUE or FALS), the high 4-bits input password (SW7~SW4), and the low 4-bits input password (SW3-SW0) in turn. (No need to trigger buttons, automatic judgment)

- In **4-bits password mode**, LED3~LED0 will display the default password when BTN3 is pressed.
- In **8-bits password mode**, LED7~LED0 will display the default password when BTN3 is pressed.

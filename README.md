# intelunnati_BETintelunnati_BETA
Design and Implementation of Automated Teller Machine (FSM) Controller (BETA-Chatrana ,kavya)

Description
This repository contains the design and implementation of an ATM machine controller using the Finite State Machine (FSM) modelling technique. The controller is implemented in VHDL and can be synthesized into a hardware description, which can be realized on an FPGA (Field-Programmable Gate Array).

The controller implements the following ATM functions, with additional checks:

User authentication
Transaction processing
Cash dispensing
Receipt generation
Invalid PIN entry (3 times allowed and later it should lock the account for next 24 hours)
Withdraw (if withdraw more than 10000 INR, please do Face Recognition Test)
Deposit
Old balance and new balance display
Mini statement for the recent transactions
The controller is designed to be modular and reusable, and it can be easily extended to support additional ATM functions.

Requirements
VHDL compiler
FPGA development board
Software: Intel Quartus Prime Design Software (Lite edition) Simulation using Modelsim / Questa Sim *Download Center for Intel FPGAs https://www.intel.com/content/www/us/en/software-kit/665990/intel-quartus-prime-lite-edition-design-software-version-18-1-for-windows.html
Usage
To use the controller, you will need to first compile the VHDL code. Once the code has been compiled, you can synthesize it into a hardware description. The hardware description can then be loaded onto an FPGA development board.

The controller can be simulated using a simulation software. This will allow you to test the controller's functionality and correctness.

Documentation
The documentation for the controller is available in the docs directory. The documentation includes the following:

A description of the FSM model
The VHDL code for the controller
A simulation model of the controller
License
The controller is licensed under the MIT License.

Author
The controller was created by Charana and kavya.

Contact
If you have any questions about the controller, please contact charanacharan94436@gmail.com .

Changelog
2023-07-14: Initial release.
2023-07-15: Added checks for invalid PIN entry, face recognition, and mini statement.
TODO
Add support for additional ATM functions.
Improve the documentation.
Test the controller on different FPGA development boards.
Additional Notes
The controller will lock the account for 24 hours if the PIN is entered incorrectly 3 times.
The face recognition test will be triggered if the withdrawal amount is greater than 10000 INR.
The mini statement will show the 10 most recent transactions.
I hope this is helpful!A

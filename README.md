# README

This jar file implements a Java Simulator for an Access Control System to manage the opening of a door giving accesses to a specific area. This access is granted only when the user introduces a valid pair of UIN and PIN.

The Access Control System has been proposed as the 2019/20 fall semester hardware/software co-design project developed in Laboratório de Informática e Computadores, which is a course in the second curricular semester of the BSc in Computer Science and Computer Engineering lectured at Instituto Superior de Engenharia de Lisboa (ISEL), the school of engineering of the IPL - Politécnico de Lisboa in Portugal.  

# Files

AccessCtrl.jar      -> implements the system

AccessCtrl.simul    -> defines the hardware to be used in the system

Simul.properties    -> saves the window and frames position

USB_PORT.properties -> defines the usbport properties required for switching between hardware and simulation

USERS.txt           -> system user database, containing the UIN, PIN, NAME and MSG 

LOG.txt             -> Access Control System log file

# User examples
UIN: 000 to 006     -> PIN: 1111 

# Acknowledgments
This simulator has been developed by Pedro Miguens Matutino based on the Java Hardware Simulation developed by Pedro Pereira (palex@cc.isel.ipl.pt). 
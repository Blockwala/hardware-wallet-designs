# HARDWARE WALLET DESIGNS

This repo is being updated with latest designs for our ongoing build of hardware wallet. You can find cad models and board files here from our Engineers and designers.

## ABOUT BITGUARD

### BitGuard

BitGuard is a HD-Hardware Wallet, which does not store your private keys. It just stores the 12 words mnemonics. From these mnemonics your private key is derived every time you do a transaction and then the transaction is signed. Hardware is divided into two parts. One part will be storing a custom bootloader and other part will be storing the firmware. Mnemonics will be stored in eeprom which will never leave the device. Lets look into details of its working.

### Communication

BitGuard will be compatible with PC, android and Ios. There will be two types of communications one over USB and another over BLE(bluetooth 4.0). Both modes will be working on UART communication(Universal asynchronous receiver-transmitter). UART is basic type of communication and hacking a device through it is really tough.

### Bootloader

Bootloader is used to update the firmware through serial port. This is needed for Over the Air update of the device’s firmware. We will be coming up with our own bootloader which will do the decryption of encrypted firmware code and like this malicious firmware wont be able to uploaded on the device. Which will avoid hackers to temper with the integrity of the device. In short no one will be able to access its eeprom, hence mnemonics.

### Eeprom

Electrically Erasable Programable Read Only Memory will store the mnemonics in encrypted form. Which can only be decrypted by the firmware while signing the transaction.

### Flash memory

In this section of the device firmware will be stored. Which will handle the user interface components like Screen and buttons.

Right now fully working prototype is ready and we are done with first draft of pcb design. We will also come up with a test bench to check the integrity of the device and do testing. Soon BitGuard will be available in market.

Follow to track progress

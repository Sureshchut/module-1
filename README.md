# BluetoothConnection 

## Overview

The BluetoothConnection smart contract is a simple Ethereum smart contract written in Solidity that allows for managing Bluetooth device connections. The contract is designed to restrict the number of connected devices to a maximum of three. It includes functionality for connecting devices, changing the password, and ensures secure password handling.

## Features

### Owner and Password

- The contract is initialized with an owner address and a private password.
- The owner address is set to the address of the deployer of the contract.
- The password is used to control access to device connections.

### Connect Device

- External entities can connect their devices to the contract by providing the correct password.
- The contract enforces a limit of three connected devices to prevent abuse.

### Change Password

- The contract provides a method for the owner to change the password.
- Changing the password is important for maintaining the security of the Bluetooth connection.

## Usage

1. **Deployment**
   - Deploy the BluetoothConnection contract to the Ethereum blockchain, providing an initial password.

2. **Connect Devices**
   - External entities can call the `connectDevice` function, providing the correct password to establish a connection.
   - Connections are limited to three devices.

3. **Change Password**
   - The contract owner can change the password by calling the `changePassword` function, providing a new password.


## License

This smart contract is released under the MIT License. See the [LICENSE](./LICENSE) file for more details.

## Author 
Suresh
sur03esh11@gmail.com

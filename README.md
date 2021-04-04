# Honey_encryption in Python

<!-- ABOUT THE PROJECT -->
## About The Project

This program demonstrates the honey encryption algorithm. When a user
is prompted to enter a password and a message, the password is then
used to create 'sweetwords' or passwords very similar to the original that a
malicious hacker may try in order to see the secret message. However, when
a sweetword is entered instead of the password, the program outputs an intruder
alarm and a fake message.

Algorithm and python code referenced from https://github.com/victornguyen75/honey-encryption.git

### Features
* User input passwords and messages
* One-time pad encryption
* Dictionary of fake messages to demostrate decoy

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

#### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/kejordan23/Honey_encryption.git
   ```

<!-- BUILD AND RUN -->
## Run

Once you run the program, you will be prompted to enter a password and a message. This password will then be 
altered and encrypted 5 times. The cosole will then prompt you to enter a password to crack and either give you 
the original message or a fake message.

<!-- LICENSE -->
## License

Distributed under the MIT License.

# ESP8266 MAC address AES-128 encryption/decryption example

Arduino based running example to encrypt and decrypt the ESP8266 MAC address with AES-128.

In this example I randomized the initialization vector and put the sample encryption/decryption in loop() with a 5 second delay to show that the encrypted message changes but still decrypts to the original MAC address.


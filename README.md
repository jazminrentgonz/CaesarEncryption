# Caesar Encryption
### Caesar Shift Encryption program that generates an encrypted output based on user input by shifting ASCII values using Assembly on a 32-bit Arm® Cortex®-Microprocessor.

This project repository houses an ARM assembly language implementation of a Caesar cipher encryption subroutine. This code enables users to input a shift offset and plaintext, which are then processed to produce encrypted text using a simple substitution encryption algorithm. The `main` function orchestrates the user inputs for the shift offset and plaintext, calls the `caesarencrypt` subroutine for encryption, and finally displays the resulting encrypted text. Within the `caesarencrypt` subroutine, each character of the plaintext undergoes encryption by shifting its ASCII value according to the given offset. Additionally, the code handles special cases such as spaces and digits while ensuring the encryption operates within the confines of the English alphabet. Detailed comments within the code enhance comprehension, making it easier for developers to understand and modify the implementation as needed. This assembly code serves as a valuable resource for learning encryption algorithms and ARM architecture programming.

### Compiling Outcome: 
Offset: 3

Original: professor

surihvvru //output shifted 3 from "Original"

 ![image](https://github.com/jazminrentgonz/CaesarEncryption/assets/70347153/f3b5fc3c-a18a-4a27-9f4e-9d15d8171616)

Another Example: 

 ![image](https://github.com/jazminrentgonz/CaesarEncryption/assets/70347153/228cd831-a8eb-469e-bd41-e1848fd447fb)

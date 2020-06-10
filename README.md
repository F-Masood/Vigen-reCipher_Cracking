# Vigenre Cipher Cracking
A C++ program for breaking the ciphertext of vigenere cipher.
The program “BREAKING VIGNERE CIPHER” is made in C++ the IDE used was “Visual Studio 2013”.

Logic:
The program first finds out whether the given ciphertext is “Polyalphabetic” or not.  For this, it calculates the “index of coincidence” value of the loaded ciphertext if the value is not close to ~0.065, the program considers it to be polyalpabetic.
Next, the program starts iteration for each keylength, first it looks for key length 2 and performs index of coincidence, then for keylength 3,4,5,6,7,8,9 until or unless it finds the IC value very close to 0.065. When the value is found it calculates the KEY value and from their it uses this KEY to derive the PLAINTEXT value. 

![alt text](https://raw.githubusercontent.com/F-Masood/Vigenre_Cipher_Cracking/master/screenshot%20of%20program.png)

#Cryptography 

# Classical ciphers


## Terms
- Encryption is the peocess of transforming information to make it unreadable

- Key special knwledge used in encryption, makes the encrypted inormation readable again
- ciper is an algorithym for performing encryption and decryption
- symmetric encryption - same cipher for encryption and decryption
- asymmetric, not that ^ 

![[Pasted image 20211103131959.png]]

![[Pasted image 20211103132147.png]]

## Substitution ciphers
1. simple substitution
	- each letter in the alphabet is mapped to another letter
	- could be reversed, shifted or shifted after a phrase
2. Polyalphabetic substitution
	- Vigenere cipher
		- String based substitution cipher
		- key is a string
		- each letter in key shows how many shifts to perform
		- ciphertext = (plaintext + key)%27
		- decryption within each session do:
		- plaintext = (ciphertext-key)%27
		- when Key length is 1, vigenere = caesar
		- polyaphabetic substitution = a seres of simple shifted substitutions
	3. Substitution ciphers
		- The vernam cupher and the one time pad
		- During encryption:
			- ciphertext = (plaintext + key)%2 (XOR operation)
		- During decryption it does the same XOR operation
			- plaintext = (ciphertext + key)%2
		- note that the key is very long, the same as the message, it is also called the one time pad. if the key string is sued one time only, te cipher satisfies strong securty conditions. distributing one time pad keys is inconvenient
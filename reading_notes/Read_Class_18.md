# Class Reading 18

## What is the basic principle behind the Caesar Cipher, and how was it used historically?


The Caesar Cipher is a substitution cipher where each letter in the plaintext is shifted a certain number of positions down the alphabet. 
For example, with a shift of 3, "A" becomes "D," "B" becomes "E," and so on. Historically, Julius Caesar used this cipher to communicate securely with his generals during military campaigns.
## What are the key differences between symmetric and asymmetric encryption? How is asymmetric used in secure communication today?
Symmetric encryption uses the same key for both encryption and decryption, while asymmetric encryption uses different keys for these operations. Asymmetric encryption is used in secure communication today by employing a public key for encryption and a private key for decryption. This allows for secure transmission of information without the need for a shared secret key.

## How do computers generate random numbers, and what are the differences between true random number generation (TRNG) and pseudo-random number generation (PRNG)? Discuss their use cases in cryptography.

Computers generate random numbers using algorithms called random number generators (RNGs). 
True random number generation (TRNG) utilizes physical processes like atmospheric noise or radioactive decay to generate unpredictable random numbers. 
Pseudo-random number generation (PRNG) uses mathematical algorithms to generate sequences of seemingly random numbers, but they are deterministic and repeatable. 
TRNG is used when high entropy and true randomness are required, while PRNG is suitable for most cryptographic applications.
## What’s the difference between encryption and decryption? Explain with an analogy.
Encryption is the process of converting plaintext into ciphertext using an encryption algorithm and a secret key. 
It ensures that the message is unreadable to anyone who doesn't possess the key. 
Decryption, on the other hand, is the reverse process of converting ciphertext back into plaintext using the same encryption algorithm and key. 
An analogy for encryption and decryption is a locked box and its corresponding key. 
Encryption locks the box, making it inaccessible, while decryption unlocks the box, revealing its contents.







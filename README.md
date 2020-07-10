# VigenereCipher
Vigenère Cipher is the simpliest polyalphabetic substitution cipher. The ciphertext is obtained by modular addition of a (repeating) keyword and an open text. The keyword must be repeated as many times to become the same length as the plaintext.
The encryption of the text is done using the Vigenère table/Vigenère square, which  consists of the alphabets written out 26 times in different rows, each alphabet shifted cyclically to the left compared to the previous alphabet, corresponding to the 26 possible Caesar Ciphers.

ENCRYPTION & DECRYPTION can be described by the formula: 

![ImgName](https://pages.mtu.edu/~shene/NSF-4/Tutorial/VIG/IMG-EN-DE-500.jpg)

ci - i-th character of the ciphertext

pi - i-th character of the open text

ki - i-th character of the key phrase (if the key phrase is shorter than the open text,is reapeated to match the length of the open text)

26 - length of the alphabet

This cipher has many weaknesses, but the primary weakness of the Vigenère cipher is the repeating nature of its key. If a cryptanalyst correctly guesses the length of the key ( it's fairly easy to guess the key length, for example by looking at correlations between characters n positions apart.), 
then the ciphertext can be treated as interwoven Caesar ciphers, which, individually, can be easily broken.

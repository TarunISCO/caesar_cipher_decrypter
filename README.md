Caesar Cipher Decrypter
=======================

## Caesar Cipher

In Cryptography, a *Caesar Cipher* also known as the *Shift Cipher*, *Caesar Shift*, is one of the simplest and most widely known encryption techniques. It is a type of [substitution cipher](https://en.wikipedia.org/wiki/Substitution_cipher) in which each letter in the plaintext is replaced by a letter some fixed number of positions down the alphabet.  For example, with a left shift of 3, D would be replaced by A, E would become B, and so on. The method is named after Julius Caesar, who used it in his private correspondence.

![Caesar Cipher Example](https://upload.wikimedia.org/wikipedia/commons/4/4a/Caesar_cipher_left_shift_of_3.svg "Caesar Cipher Example")

`Plain Text : THE QUICK BROWN FOX JUMPS OVER THE LAZY DOG`

`Cipher Text : QEB NRFZH YOLTK CLU GRJMP LSBO QEB IXWV ALD`

Deciphering is done in reverse, with a right shift of 3.

### Modular Arithmetic
The encryption can also be represented using modular arithmetic by first transforming the letters into numbers, according to the scheme, A → 0, B → 1, ..., Z → 25. Encryption of a letter x by a shift n can be described mathematically as,

![Encryption](https://wikimedia.org/api/rest_v1/media/math/render/svg/77b59c7a676a99610ddee4ffc305aa7f9cda3b1a "Encryption")

Decryption is performed similarly,

![Decryption](https://wikimedia.org/api/rest_v1/media/math/render/svg/8ed607e0202ff8d35aa41559f846cac9d358a362 "Decryption")

The replacement remains the same throughout the message, so the cipher is classed as a type of [monoalphabetic cipher](https://en.wikipedia.org/wiki/Monoalphabetic_substitution) as compared to [polyalphabetic cipher](https://en.wikipedia.org/wiki/Polyalphabetic_substitution).

## Cryptography

---

Cryptography is a method of protecting information and communications through the use of codes, so that only those for whom the information is intended can read and process it.

## Encryption

---

The process of converting information or data into a code, especially to prevent unauthorized access.

There are mainly two types of encryption techniques used in CS:

1. Symmetric key encryption.
2. Asymmetric key encryption.

## Symmetric key Encryption

---

Symmetric encryption is a type of encryption where only one key (a secret key) is used to both encrypt and decrypt electronic information.

Some of the common symmeteric key algorithms :

1. AES (Advanced Encryption Standard) / (Rijndael)
   - Invented in year 2001
2. DES (Data Encryption Standard)
3. Twofish
4. Serpent

Pros

1. Fast
2. Efficient for large data.

Cons

1. Difficult to transport shared key.

## Asymmetric key Encryption (Public Key encryption)

---

Asymmetric cryptography, also known as public-key cryptography, is a process that uses a pair of related keys --> one public key and one private key to encrypt and decrypt a message and protect it from unauthorized access or use. A public key is a cryptographic key that can be used by any person to encrypt a message so that it can only be deciphered by the intended recipient with their private key. A private key also known as a secret key is shared only with key's initiator.

Some of the common asymmetric key algorithms :

1. RSA (Rivesh-Shamir-Adleman)
2. Diffe-Hellman
3. ElGamal

Pros

1. Public key can be shared
2. Designed for small data(ssh)

Cons

1. Slow
2. Inefficient for large data.

## Hybrid Approach

---

In many applications, such as website security, there was a need to encrypt the data at a high speed and the verification of identity was also required to ensure the users that they’re talking to the intended entity. That’s how the idea of hybrid encryption was born.

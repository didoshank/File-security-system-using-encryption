# File-security-system-using-encryption
So, as we are using RSA encryption algorithm, it is asymmetric cryptography algorithm. Asymmetric actually means that it works on two different keys i.e., Public Key and Private Key. As the name describes that the Public Key is given to everyone and Private key is kept private. The public key consists of two numbers where one number is multiplication of two prime numbers(n) and another number is an integer (e). And private key(d) is also derived from the same two prime numbers. So, while registering the user is asked to enter two numbers and using those two numbers, we find two nearest next prime numbers and use that to find public and private key that will be used for encryption and decryption. User have to first get registered, register form will ask to enter username, password and any two random numbers. After registering user can login to the system using that username and password and then they can encrypt and decrypt files after entering password. Encryption and decryption will be performed using public and private keys which has been calculated using those two numbers that user have given while registering.

Generating Public Key and Private Key:
Generating Public Key: Select two prime numbers. Suppose P and Q. Now First part of the Public key: n = P*Q.
We also need a small exponent say e:But e Must be
An integer.
Not be a factor of n.
1 < e < Φ(n) [Φ(n) is discussed below], 

Our Public Key is made of n and e
Generating Private Key: We need to calculate Φ(n): Such that Φ(n) = (P-1) (Q-1) Now calculate Private Key, d: d = (k*Φ(n) + 1) / e for some integer k So, by this we get our – Public Key (n and e) and Private Key(d)


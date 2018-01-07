# Deoxys-cipher
We have implemented the Deoxys cipher which includes the concept of well known AES algorithm. The encryption part takes as input a variable length plaintext, a variable length associated data, a fixed length public message number and a k bit key.  After encryption it outputs the corresponding cipher text and a tag (unique for particular nonce and key).

In short, Deoxys is an authenticated encryption scheme that provides full 128bit security for both privacy and authenticity

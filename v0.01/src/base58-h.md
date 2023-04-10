Base58 is a group of binary-to-text encoding schemes used to represent large integers in a more compact and user-friendly format.

It is similar to Base64 encoding, but it uses a different set of characters that is designed to be more user-friendly and less prone to errors when transcribed by hand. The most commonly used character set for Base58 encoding is the one used in Bitcoin, which consists of the upper- and lower-case letters, the numbers 0 through 9, and the characters '+' and '/'.

Some of the benefits of using Base58 are that it is more compact than Base64 encoding, it is more readable than hexadecimal encoding and it excludes characters that are easily confused, such as the number "0" and the letter "O".

It is also worth noting that various modifications on base58 exist, the most known one is base58Check which is used for Bitcoin addresses and private keys. It is base58 but with an added 4 bytes checksum at the end, that guarantees that the encoded data is correctly decoded.
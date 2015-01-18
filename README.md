# ciphermate cipher util

A utility that aims to ease simple encryption/decryption/hashing/base64 tasks

    ciphermate <encrypt/decrypt/base64/hash> [-a <CipherAlgorithm>] [-k <Key>] [-iv <IV>] [-i] <CipherText>
    ciphermate; a utility to encrypt/decrypt a cipher text
    usage:
        -h                       prints this text
        -a       <algorithm>     Specify the Cipher Set Algorithm to use (default aes256)
        -k       <key>           Sets the key to be used for the encryption
        -iv      <IV>            Sets the IV parameter if needed
        encrypt                  Triggers Encryption flow
        decrypt                  Triggers Decryption flow
        base64                   Triggers base64 flow
        hash                     Triggers hash flow
        CipherText               Sets the text to be encrypted/decrypted/hashed encoded

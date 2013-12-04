AES crypto example
==================

        Java Example how to use AES (http://en.wikipedia.org/wiki/Advanced_Encryption_Standard)
        simmetric-key to encrypt/decrypt data

        Use keytool to create KeyStore

         keytool command.
         $keytool -genseckey -keyalg AES -alias myseckey -keysize 256 -keypass
          mykeypass -storetype jceks -keystore mystore.jck -storepass mystorepass

          run AESCrypto

            Text [Byte Format] : [B@10382a9
            Text : My Secret Text
            Text Encrypted : [B@a761fe
            Encode Base64 String Encrypted : 94tY+otQOYMM8GGseUlb9g==
            Text Decrypted : My Secret Text

++++++++++++++++++

Hash password example
=====================

       Java example how to hash password into Hexadecimal String.

       Run HashPassword

       Program prints similar report

       PBKDF2WithHmacSHA1:salt:[B@5f7a8a02:hash:[6, 104, 99, 101, -17, 55, -87, 81, -75, 75, -78, 87, 45, 97, 66, -23, -101, 25, -124, 100, 112, -4, -126, 115]:hex:06686365ef37a951b54bb2572d6142e99b19846470fc8273

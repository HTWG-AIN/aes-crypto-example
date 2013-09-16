aes-crypto-example
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

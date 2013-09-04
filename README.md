aes-crypto-example
==================

        Java Example how to use AES (http://en.wikipedia.org/wiki/Advanced_Encryption_Standard)
        simmetric-key to encrypt/decrypt data

        Use keytool to create KeyStore

         keytool command.
         $keytool -genseckey -keyalg AES -alias myseckey -keysize 256 -keypass
          mykeypass -storetype jceks -keystore mystore.jck -storepass mystorepass

          run AESCrypto

          Text [Byte Format] : [B@a761fe
          Text : My Secret Text
          Text Encrypted : [B@6d126b07
          Text Decrypted : My Secret Text

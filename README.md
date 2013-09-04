aes-crypto-example
==================

        Java Example how to use AES simmetric key to encrypt/decrypt data

        Use keytool to create KeyStore

         keytool command.
         $keytool -genseckey -keyalg AES -alias myseckey -keysize 256 -keypass
          mykeypass -storetype jceks -keystore mystore.jck -storepass mystorepass

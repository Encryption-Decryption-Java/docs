# docs
There are two general categories of key based algorithms:

1.Symmetric encryption algorithms: Symmetric algorithms use the same key for encryption and decryption. These algorithms, can either operate in block mode (which works on fixed-size blocks of data) or stream mode (which works on bits or bytes of data). They are commonly used for applications like data encryption, file encryption and encrypting transmitted data in communication networks (like TLS, emails, instant messages, etc.).</br> 
2.Asymmetric (or public key) encryption algorithms: Unlike symmetric algorithms, which use the same key for both encryption and decryption operations, asymmetric algorithms use two separate keys for these two operations. These algorithms are used for computing digital signatures and key establishment protocols. </br>

JCE API's are implemented by Cryptographic Service Providers. Each of these cryptographic service providers implements the Service Provider Interface which specifies the functionalities which needs to be implemented by the service providers. Programmers can plugin any Service Providers for performing cryptographic functionalities provided by JCE. J2SE comes with a default provider named SunJCE.</br>

<h2>Symmetric Encryption Algorithms provided by SunJCE</h2></br>

DES - default keylength of 56 bits</br>
AES -</br>
RC2, RC4 and RC5</br>
IDEA</br>
Triple DES – default keylength 112 bits</br>
Blowfish – default keylength 56 bits</br>
PBEWithMD5AndDES</br>
PBEWithHmacSHA1AndDESede</br>
DES ede</br>
Modes of Encryption</br>
ECB</br>
CBC</br>
CFB</br>
OFB</br>
PCBC</br>

<h2>Asymmetric Encryption Algorithms implemented by SunJCE</h2></br>

RSA</br>
Diffie-Hellman – default keylength 1024 bits</br>

<h2>Hashing / Message Digest Algorithms implemented by SunJCE</h2></br>

MD5 – default size 64 bytes</br>
SHA1 - default size 64 bytes</br>

<h2>Reference URLs</h2>
http://www.java-redefined.com/2013/08/symmetric-and-asymmetric-key-encryption.html </br>
http://www.java-redefined.com/2013/08/symmetric-key-encryption-decryption.html</br>
http://www.java-redefined.com/2014/03/symmetric-and-asymmetric-key-encryption-with-keytool.html</br>
http://www.java-redefined.com/2014/03/symmetric-asymmetric-signature.html</br>
http://www.java-redefined.com/2014/03/java-digital-singnature.html</br>
https://www.quickprogrammingtips.com/java/java-asymmetric-encryption-decryption-example-with-rsa.html</br>
https://www.owasp.org/index.php/Using_the_Java_Cryptographic_Extensions</br>
http://www.code2learn.com/2011/06/encryption-and-decryption-of-data-using.html</br>
https://howtodoinjava.com/security/java-aes-encryption-example/</br>
https://www.veracode.com/blog/research/encryption-and-decryption-java-cryptography</br>







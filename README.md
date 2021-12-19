# CryptographicUtilities
Examples and HowTos for BouncyCastle and Java Cryptography Extension (JCE)

See class "/src/main/java/de/soderer/utilities/crypto/CryptographicUtilities.java" for handling of symmetric and asymmetric keys.

See classes "/src/main/java/de/soderer/utilities/crypto/Asymmetric*Worker.java" for asymmetric enryption/secryption and signing/verficication of data.

See classes "/src/main/java/de/soderer/utilities/crypto/Symmetric*Worker.java" for symmetric enryption/secryption and signing/verficication of data.

JUnit 4 tests included in "/src/test/de/soderer/utilities/crypto/CryptographicUtilitiesTest.java".

Of course this project has dependencies. I tested with Java 11 and this current bouncycastle versions of libs:
- bcmail-jdk15on-1.69.jar
- bcpg-jdk15on-1.69.jar
- bcpkix-jdk15on-1.69.jar
- bcprov-jdk15on-1.69.jar
- bcutil-jdk15on-1.69.jar

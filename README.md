<h1 align="center">Hash Blade</h1>
<p align="center">
  <img src="https://github.com/WalderlanSena/tagsGit/blob/master/licenseMIT.svg">
</p>
<p align="center">:closed_lock_with_key: :hocho: Encrypted texts and perform Brute Force. Through Hash MD5, SHA1, SHA256, SHA512.. In all operating systems Gnu/Linux :penguin:, Windows, MacOs :apple:</p>

<h2>Whats is Hash?</h2>
<p align="center">
  <img src="https://www.gta.ufrj.br/ensino/eel879/trabalhos_vf_2008_2/hugo/NotesImages/Topic10NotesImage3.jpg"><br>
  Font img: https://www.gta.ufrj.br
</p>
<p align="justify">A hash function is an algorithm that maps variable-length data to fixed-length data. The values returned by a hash function are called hash values, hash codes, hash sums, checksums, or simply hashes.</p>

<h2>Whats is Md5?</h2>
<p align="justify">MD5 is a 128-bit unidirectional cryptographic scatter function developed by RSA Data Security, Inc., described in RFC 1321, and widely used by point-to-point protocol software for file and log integrity checking.</p>
<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c8/CPT-Hashing-File-Transmission.svg/350px-CPT-Hashing-File-Transmission.svg.png"><br>Font img: https://upload.wikimedia.org</p>

<h2>Whats is Sha1?</h2>

<p align="justify">SHA1 implements a keyness hashed algorithm that takes a message up to 264 bits and produces a 160-bit message summary and is used for message integrity checking. It is based on the design principles of the MD4 and MD5 hash algorithms (Memory Digest 4 and 5).</p>

<h2>Whats is Sha2?</h2>

<p align="justify">Pseudo-collision attacks against up to 46 rounds of SHA-256. SHA-2 is a set of cryptographic hash functions designed by the NSA. SHA stands for secure hash algorithm.</p> 
<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/7d/SHA-2.svg/400px-SHA-2.svg.png"><br>Font img: https://upload.wikimedia.org</p>

<h2>Documentaçao - HashBlade</h2>

<p align="justify"> Hashblade is a multiplatform software (Gnu / Linux, MacOs, Windows) that performs text encryption for: MD5, SHA1, SHA256 and SHA512. However, the software also has the brute force functionality in the hashes previously mentioned. <br>
"In computer science, brute force search or exhaustive search, also known as generate and test, is a trivial yet very general problem solving technique that consists of enumerating all possible candidates for the solution and checking each candidate to see if he or she satisfies the problem statement."
</p>

<h3>:information_source: Software startup screen</h3>

<p align="center">
  Ubuntu Operating System<br />
  <img src="https://github.com/WalderlanSena/hashblade/blob/master/src/hashbladeLinux.png">
</p>

<p align="center">
  Windows Operating System<br />
  <img src="https://github.com/WalderlanSena/hashblade/blob/master/src/hashbladewin.png">
</p>

<h3>:information_source: Compilation</h3>

<p align="justify">The compilation process is basically the same in all operating systems, because it is a software written in c ++ language. While using <b>:penguin: Gnu/Linux</b> operating systems, just use the <b>make</b> command to compile and generate the binary <b>ELF</b>
  
 ```shellscript  
 make
 ```
 or
  ```shellscript
 g++ hashblade.cpp lib/md5.cpp lib/sha1.cpp lib/sha256.cpp lib/sha512.cpp lib/libhashblade.cpp -o hashblade
 ```
 <p align="justify">:heavy_exclamation_mark: In Windows, the process is the same, and only the extension of the final file that will be changed to <b>hashblade.exe</b></p>

---
layout: post
title:  "The genesis and nature of  ransomware attack"
date:   2014-12-11
---

<p class="intro">
<span class="dropcap">I</span>t may surprise you to know that ransomware has been around for quite a long time. The first
asymmetric ransomware prototypes were developed in the mid-1990s. </p>

### Ransomware History
 The idea of using public-key
cryptography for computer attacks was introduced in 1996 by Adam L. Young and Moti Yung in the
1996 Proceedings of the IEEE Symposium on Security and Privacy. In the abstract, Young and Yung
said their prototype was meant to show how cryptography could be “used to mount extortion-based
attacks that cause loss of access to information, loss of confidentiality, and information leakage,
tasks which cryptography typically prevents.” Young and Yung presented a proof-of-concept
cryptovirus for the Apple Macintosh SE/30 using RSA and TEA asymmetric block ciphers.
<img class="aligncenter" src="/images/history.jpg" >

### How Ransomware Works
There are six steps that ransomware generally uses to accomplish its goals. 
<ol>
<li>The first step is distribution: </li>
Ransomware uses standard methods of distribution. Generally it is
spread through phishing schemes involving email attachments or downloads and installs on an
endpoint through website compromises. 
<li>Infection.</li> The binary arrives on the user’s computer and starts the processes
it needs to complete its malicious activities. These may include quite a bit of new, sophisticated
behaviors. For example, CryptoWall 3 will do the following:
<ul>
<li>Generate a unique computer identifier.</li>
<li>Ensure “reboot survival” by installing the program to run at start-up
(through service entry, scheduled task, AutoRun key, etc.).</li>
<li>Deactivate shadow copies, start-up repair, and Windows error recovery.</li>
<li> Stop Windows Security Center, Windows Defender, Windows Update Service, error
reporting, and BITS.</li>
<li> Inject itself into explorer.exe and svchost.exe.</li>
<li>Retrieve the external IP address.</li>
</ul>
<li>Communications.</li> The ransomware process will talk to encryption-key servers
to retrieve the public key needed to encrypt data. CryptoWall 3, for example, connects to a
compromised WordPress site and reports its status. All control server traffic is encrypted using the
RC4 encryption algorithm.
<li>File search.</li> The ransomware process searches for files on the system in a
systematic fashion. It typically looks for files that are important to the user and cannot be easily
replicated, such as files with extensions of jpg, docx, xlsx, pptx, and pdf.
<li>Encryption.</li> This is typically done through moving and renaming the targeted files,
then encrypting and renaming the files after a successful encryption.
<li>The sixth and final step is the ransom demand, typically through taking over the screen of the
infected endpoint and demanding payment.</li> 
</ol>
<img class="aligncenter" src="/images/howorks.jpg" >

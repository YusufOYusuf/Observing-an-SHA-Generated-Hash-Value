<h1>Observing an SHA Generated Hash Value</h1>


<h2>Description</h2>
In this lab, I learned to observe an SHA-generated hash value. The SHA-256 hashing algorithm produces 1-bit to 256-bit hash values of the entire file. These hash values can be used for checking the data integrity of the file. When a user downloads any file, the file data can be manipulated by an attacker in between. SHA-256 generates an almost-unique 256-bit (32-byte) signature for a text.
<br />



<h2>Environments Used </h2>

- <b>Kali GNU/Linux rolling</b> 

<h2>Utilities and Language </h2>

- <b>Terminal</b>

<h2>Program walk-through:</h2>

<p align="center">
From the left sidebar open up the terminal  <br/>
<img src="https://i.postimg.cc/Yq7pNPHv/Screen-Shot-2023-02-23-at-12-21-34-AM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
  
  
  
<br />
In the Terminal window execute the "sha256sum ~/Downloads/ucertify.iso > ~/Downloads/sha.txt" to compute and check the SHA-256 message digest of the of a downloaded file for errors<br>
<img src="https://i.postimg.cc/QN0Y86q2/Screen-Shot-2023-02-23-at-12-31-01-AM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />



<br />
Now check the downloaded file and its aactual SHA-256 by typing the "diff ~/Downloads/real.txt ~/Downloads/sha.txt" command<br>
<br> The diff command stands for "difference" and it is used to display the differences in the files by comparing the files line by line <br>
<img src="https://i.postimg.cc/15717GYQ/Screen-Shot-2023-02-23-at-12-35-16-AM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />



















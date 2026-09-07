## Can I exploit all open ports? ##

Here are all identified open ports: 

<img width="1914" height="763" alt="identifying configs" src="https://github.com/user-attachments/assets/333989bc-a33d-466e-ac6c-557c9ea10e00" />

Level 1: FTP

<img width="911" height="211" alt="FOUND FTP VULN" src="https://github.com/user-attachments/assets/79e2c67a-208b-4a0b-9d02-c9ae954d59c3" />

Here is the vulnerability with FTP. It is running an older version, creating vulnerabilties for me to exploit.

Metasploit created a backdoor and with a few commands, I was able to find all files.

<img width="935" height="833" alt="entered the server, now in the files" src="https://github.com/user-attachments/assets/9dbd31d3-75b7-4f25-a73e-99cb98fe4dae" />

Level 2: SSH

The next open port was SSH. This appears to be hard to crack as SSH is encrypted. Luckily, Metasploit Framework shows us how to crack it through brute force. 

<img width="1075" height="848" alt="how to brute force" src="https://github.com/user-attachments/assets/95c02ccf-586b-4d0f-9a47-bc7b7384569f" />

Setting all the parameters for the brute force
<img width="712" height="270" alt="revving engines for brute force" src="https://github.com/user-attachments/assets/33825971-4936-4410-8f79-ec25b03cb005" />

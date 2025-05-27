# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

- `Step 1:` Install kali linux either in partition or virtual box or in live mode
- `Step 2:` Investigate on the various categories of tools as follows.
-  `Step 3:` Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:
![image](https://github.com/user-attachments/assets/fe579a10-e2f8-44cd-9e6e-31f958a069e5)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/user-attachments/assets/909c137f-4794-4af8-9e66-dc7c8a263651)


 dsniff:In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/user-attachments/assets/8890752e-5b7b-42e1-92c7-a0a94455e94d)


In Kali issue the following commands:
sudo dsnifff
![image](https://github.com/user-attachments/assets/cd19e080-701c-47c7-a09d-81f07d4f31e5)


Invoke the wireshark and examine the various menus  and controls of the tool:
![image](https://github.com/user-attachments/assets/6ddbd07c-a3a7-4cec-b14a-189e4a062c32)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully

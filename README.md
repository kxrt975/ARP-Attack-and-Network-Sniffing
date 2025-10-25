# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:
<img width="671" height="693" alt="324250921-23e1040d-0d30-47d2-a9d1-73b1988ca8a3" src="https://github.com/user-attachments/assets/deaa106f-1bce-4041-9067-68ec73919192" />

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
<img width="621" height="302" alt="324251000-fe31b4ad-3f7c-420c-98b2-a744753543b3" src="https://github.com/user-attachments/assets/9da3b569-cef8-4236-b743-94869a13994e" />


 dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
<img width="930" height="394" alt="324251080-0bc59714-d2a5-459c-9e7d-517c82037ae1" src="https://github.com/user-attachments/assets/c713416e-0785-491d-b000-f02849522d28" />

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

<img width="766" height="125" alt="324251192-d8000a29-e6c6-4ea3-ae36-9c66f9d139a6" src="https://github.com/user-attachments/assets/5895dc01-e65f-4b8f-b3dc-a11d0d63f43b" />



Invoke the wireshark and examine the various menus  and controls of the tool:

<img width="1914" height="807" alt="324251213-19ba4623-276d-43d9-8105-7395b509f9ae" src="https://github.com/user-attachments/assets/013a82b4-2f02-4e17-9d84-8a583943db09" />

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully

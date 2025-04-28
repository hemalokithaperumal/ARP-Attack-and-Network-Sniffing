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

![image](https://github.com/user-attachments/assets/0dd0fb53-21f9-4c77-a341-182accca7bc9)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![image](https://github.com/user-attachments/assets/eacfe94c-78b1-4b95-b475-aca311eef8ee)

 dsniff:In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![image](https://github.com/user-attachments/assets/2e2789cc-100a-420d-9016-723f8d409a6f)




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![image](https://github.com/user-attachments/assets/583f59dd-94c8-41a0-9d67-a27ffa25ed3a)


Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully

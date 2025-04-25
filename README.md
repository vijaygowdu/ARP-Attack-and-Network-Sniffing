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

![Screenshot 2025-04-12 090758](https://github.com/user-attachments/assets/9b9c707b-603f-4793-9f8b-5d4df90caee9)



From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![Screenshot 2025-04-12 090806](https://github.com/user-attachments/assets/ff5e69d8-f210-49bc-a092-aa76508bc255)



 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![Screenshot 2025-04-12 090816](https://github.com/user-attachments/assets/83b4a470-2cbe-42b6-aca2-6c10d03d7183)





In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![Screenshot 2025-04-12 090826](https://github.com/user-attachments/assets/69eed1bf-0d62-41c2-b2b2-a1fc9df58b63)




Invoke the wireshark and examine the various menus  and controls of the tool:

![Screenshot 2025-04-12 090835](https://github.com/user-attachments/assets/e9c2561e-6ab4-40b6-81c3-003323598ec8)



## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully

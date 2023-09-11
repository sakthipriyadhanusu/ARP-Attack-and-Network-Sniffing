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
![image](https://github.com/sakthipriyadhanusu/ARP-Attack-and-Network-Sniffing/assets/119393194/b832a36f-d361-46a3-83d9-536b35b634e2)
From kali linux issue the command : sudo arpspoof -i eth0 -t
## OUTPUT:
![image](https://github.com/sakthipriyadhanusu/ARP-Attack-and-Network-Sniffing/assets/119393194/e66e1874-b56d-4f48-bcb0-f1b5010da95c)
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/sakthipriyadhanusu/ARP-Attack-and-Network-Sniffing/assets/119393194/7b2ee7dd-86a1-4c73-b56b-8b48ad6e6bc7)
In Kali issue the following commands: sudo dsnifff
## OUTPUT:
![image](https://github.com/sakthipriyadhanusu/ARP-Attack-and-Network-Sniffing/assets/119393194/7ed4ad4d-fdcf-42e3-b907-806c25a51938)


Invoke the wireshark and examine the various menus and controls of the tool:
![image](https://github.com/sakthipriyadhanusu/ARP-Attack-and-Network-Sniffing/assets/119393194/da10c858-da87-4c56-b945-e82b9069656a)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully

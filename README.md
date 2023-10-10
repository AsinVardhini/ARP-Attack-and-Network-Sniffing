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
![image](https://github.com/AsinVardhini/ARP-Attack-and-Network-Sniffing/assets/119417735/2fe52578-42cb-4242-97b5-1777d143033a)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![image](https://github.com/AsinVardhini/ARP-Attack-and-Network-Sniffing/assets/119417735/ecc9cfec-4038-4fac-b946-63bf348d1195)


 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:


![image](https://github.com/AsinVardhini/ARP-Attack-and-Network-Sniffing/assets/119417735/b3f418ba-fdaf-49e2-a50d-b7b8ef688efb)


In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![image](https://github.com/AsinVardhini/ARP-Attack-and-Network-Sniffing/assets/119417735/d28920c0-c2dd-477a-b882-4cafd6577eba)


Invoke the wireshark and examine the various menus  and controls of the tool:
![image](https://github.com/AsinVardhini/ARP-Attack-and-Network-Sniffing/assets/119417735/d5011e8e-d087-4d6b-a580-2170535b49fd)



## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully

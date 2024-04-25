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
```
## Developed By:Lokesh N
## Reg No:212222100023
```

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:
![image](https://github.com/lokeshnarayanan/ARP-Attack-and-Network-Sniffing/assets/119393019/653a14dd-9ae0-4df1-9643-57106083cec8)


From kali linux issue the command :
sudo arpspoof -i eth0 -t 
## OUTPUT:
![image](https://github.com/lokeshnarayanan/ARP-Attack-and-Network-Sniffing/assets/119393019/89c87e6d-a2ea-40d2-bb21-5e5957c27e02)

## dsniff:


In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:


![image](https://github.com/lokeshnarayanan/ARP-Attack-and-Network-Sniffing/assets/119393019/f76857a0-c2ca-4106-a812-30583c2da774)


In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/lokeshnarayanan/ARP-Attack-and-Network-Sniffing/assets/119393019/2ccc2344-4757-4ce0-bac2-a85fe1e69b25)


Invoke the wireshark and examine the various menus  and controls of the tool:

![image](https://github.com/lokeshnarayanan/ARP-Attack-and-Network-Sniffing/assets/119393019/376ebaf6-1ca7-4580-a8ea-3d10a59b47c1)




## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully

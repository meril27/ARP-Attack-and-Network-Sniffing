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


<img width="1037" height="240" alt="image" src="https://github.com/user-attachments/assets/9accdd65-1f5a-450e-8d07-1436a116b967" />


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:


<img width="1247" height="848" alt="image" src="https://github.com/user-attachments/assets/197d8ff7-016a-49ff-b4a7-c23bb8c947b2" />


 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:


<img width="1312" height="808" alt="image" src="https://github.com/user-attachments/assets/fbd203b1-8860-42a3-a98f-c9840b7ce7bf" />



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:


<img width="2042" height="512" alt="image" src="https://github.com/user-attachments/assets/7a76ecad-6874-48e4-8452-5c2a08ee47bb" />





Invoke the wireshark and examine the various menus  and controls of the tool:

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/41ea7516-9c0c-4720-b0e6-8bbd9f86c97c" />



## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully

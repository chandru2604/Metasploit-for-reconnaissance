# Metasploit-for-reconnaissance
# Metasploit
Metasploit for reconnaissance in pentesting

# AIM:

To get introduced to Metasploit Framework and to  perform reconnaissance  in pentesting .

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:

# Checking the Port using ifconfig:


<img width="617" height="448" alt="image" src="https://github.com/user-attachments/assets/8d8bd114-6fad-4dc0-b72d-c6ac5cde4e36" />

# Get into The MsfConsole :

<img width="680" height="576" alt="image" src="https://github.com/user-attachments/assets/19670a90-819f-40d1-a736-d3dd342c1ccc" />

# Using Help Command :

<img width="772" height="602" alt="image" src="https://github.com/user-attachments/assets/cf663e02-96e4-44a3-a08d-246df28f68a0" />

Type help or a question mark "?" to see the list of all available commands you can use inside msfconsole.

# Nmap :

<img width="532" height="145" alt="image" src="https://github.com/user-attachments/assets/d0e1cbe8-2069-41ee-90ee-d9a38edb0e85" />

Port Scanning:
Following command is executed for scanning the systems on our local area network with a TCP scan (-sT) looking for open ports between 1 and 1000 (-p1-1000).

# DB_Nmap :
<img width="640" height="816" alt="image" src="https://github.com/user-attachments/assets/35c94c38-c97b-445b-828c-5aa6c3da0118" />

use the db-nmap command to scan and save the results into Metasploit's postgresql attached database. In that way, you can use those results in the exploitation stage later.

# Viewing the metasploit framework on root:

<img width="732" height="397" alt="image" src="https://github.com/user-attachments/assets/3b75de13-4d60-4ae2-94d2-10687dbe4435" />

Metasploit has a multitude of scanning modules built in. If we open another terminal, we can navigate to Metasploit's auxiliary modules and list all the scanner modules.
cd /usr/share /metasploit-framework/modules/auxiliary
kali > ls -l





## RESULT:
The Metasploit framework for reconnaissance is  examined successfully

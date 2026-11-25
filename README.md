# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:
## OUTPUT


<img width="945" height="905" alt="image" src="https://github.com/user-attachments/assets/b7ba9340-da40-414a-b087-d8ff261e5c6b" />



The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT

<img width="600" height="245" alt="image" src="https://github.com/user-attachments/assets/517ebb67-dd6d-4708-ae1e-d358da4f44e6" />


It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT

<img width="870" height="721" alt="image" src="https://github.com/user-attachments/assets/2b0a6b15-1630-47a1-8cfe-1078c7244562" />



The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT



It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT




It shows the following screen in which the option Google can be selected:
## OUTPUT





SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT




In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT


SET logs the information regarding the Google credentials:
## OUTPUT



SET logs the information in the xml file under /root/.set directory:
## OUTPUT












## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully

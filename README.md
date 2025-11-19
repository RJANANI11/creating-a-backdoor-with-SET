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


<img width="871" height="988" alt="Screenshot 2025-11-18 235733" src="https://github.com/user-attachments/assets/31a3e1bb-cb63-408c-9c08-8ecc8211b66d" />


The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT


<img width="441" height="240" alt="Screenshot 2025-11-18 235945" src="https://github.com/user-attachments/assets/3ed413ff-1580-4a56-9dc5-c6772966908b" />



It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT

<img width="419" height="288" alt="Screenshot 2025-11-19 000007" src="https://github.com/user-attachments/assets/ade5601e-155c-47f2-9b3c-8d3ef8a0ffeb" />

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
## OUTPUT

<img width="475" height="207" alt="Screenshot 2025-11-19 000024" src="https://github.com/user-attachments/assets/f98fd4b5-d406-40a5-8df2-948773c99af5" />



The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT

<img width="368" height="142" alt="Screenshot 2025-11-19 000038" src="https://github.com/user-attachments/assets/be512e94-efd8-4db6-b412-21af93818785" />


It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT
<img width="781" height="496" alt="Screenshot 2025-11-19 000123" src="https://github.com/user-attachments/assets/35b66350-961a-4c5c-be00-2229e2e91114" />




It shows the following screen in which the option Google can be selected:
## OUTPUT


<img width="676" height="422" alt="Screenshot 2025-11-19 000200" src="https://github.com/user-attachments/assets/fd56b043-ecb0-4b94-8500-b549f31f964e" />



SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT

<img width="703" height="206" alt="Screenshot 2025-11-19 000218" src="https://github.com/user-attachments/assets/9cfc7b51-8c7f-4a96-b4d3-227300cbd0da" />



In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT

<img width="809" height="609" alt="Screenshot 2025-11-19 223721" src="https://github.com/user-attachments/assets/cfdae044-18c4-4ae7-9bda-6db83ac25ec1" />

SET logs the information regarding the Google credentials:
## OUTPUT


<img width="797" height="192" alt="image" src="https://github.com/user-attachments/assets/c7f9d7a3-a805-408d-9a09-712fa15e153d" />














## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully

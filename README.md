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


![{253691D6-93BC-46E5-82BA-88419F42C75C}](https://github.com/user-attachments/assets/45e2acee-46eb-4fe0-a2ae-8e504208a694)


The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:


![{46D4DCB9-2022-42D6-AD6B-88E247F9791C}](https://github.com/user-attachments/assets/0d9518fa-c81f-42ae-992c-dbaf89653d3a)


It displays the following menu and select 2 for Website Attack Vectors:


![{4777F584-4BD9-4E2D-AC4B-FB355A6BE02B}](https://github.com/user-attachments/assets/682057cb-af7b-467c-ac2f-7f522b26209a)



The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:



![{695B2E9A-78DF-49A0-865E-4385CD39898E}](https://github.com/user-attachments/assets/ae30e1c9-fa2a-4415-a823-702961d54bbe)


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:


![{496D07F1-8591-4BD8-AF4C-5BE1B84974E5}](https://github.com/user-attachments/assets/b5d9bece-704a-475b-a74e-661cf0bd188b)



It shows the following screen in which the ip address of the attacker need to be given which is the default value:


![{1C0B2CE1-E5BB-475C-99E9-F2B39C8CEA0B}](https://github.com/user-attachments/assets/c42c5dff-aa30-4e2e-9fba-7879c573689f)



It shows the following screen in which the option Google can be selected:



![{EE37978E-0F84-48DA-93AA-09FE898E3AD6}](https://github.com/user-attachments/assets/c241c255-848e-4e52-81f9-f0fde7e8086e)




SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:



![{B64541C5-4047-4F04-BD93-C15576C6077A}](https://github.com/user-attachments/assets/17784397-4941-452f-92ac-65184fc9d7d0)






In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password



![{1FDA3E9C-C2D8-469C-9DDE-74F6E5D70BAF}](https://github.com/user-attachments/assets/eb20c3b6-65d0-4e3e-ae9e-33e84551c44e)






## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully

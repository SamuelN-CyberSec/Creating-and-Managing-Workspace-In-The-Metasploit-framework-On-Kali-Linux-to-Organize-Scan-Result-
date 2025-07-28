# Creating-and-Managing-Workspace-In-The-Metasploit-framework-On-Kali-Linux-to-Organize-Scan-Result-
Creating and managing workspace in Metasploit helps you organize scan result and isolate penetration test activities across different project, target and client efficiently.  In this  project I will demonstrate configuration  and managing of workspace in the  Metasploit framework on Kali Linux 
# Objectives
-Start Metasploit framework console  
-start Metasploit framework database
-Check if PostgreSQL is connected ( Metasploit database) 
-Create workspace (add,rename,delete) The Metasploit framework 
-Add host In The Metasploit framework workspace (Ip address) 

# Tools Used
-Kali Linux 
-VMware 

# Steps
-Start Metasploit framework console (mfsconsole)
-Start Metasploit framework database (Mfsdb init)
-Check if PostgreSQL is connected ( Metasploit database : db_status) 
-If not connected manually connect PostgreSQL( Metasploit database: db_connect -y/usr/share/metasploit-famework/config/databse.yml)
- Create workspace (add,rename,delete : to add, workspace -a <name of workspace>,to delete, workspace -d <name of workspace> to rename, workspace -r <previous name of workspace>  <new name of workspace> ) 
- To access workspace ( workspace <name>) 
- To add host in the Metasploit framework workspace ( db_nmap <Ip address>)

# Key Findings
- Can be seen in the screenshot attached
- <img width="545" height="311" alt="Starting Metasploit Console" src="https://github.com/user-attachments/assets/95ddb1ce-a5c0-4d35-982a-3b3243e59823" />
<img width="539" height="235" alt="Starting Metasploit Framework Database" src="https://github.com/user-attachments/assets/8f0a3199-d009-484b-930c-7f88e5e2df1c" />
<img width="307" height="23" alt="Manually Connecting Metasploit Frame Work Database " src="https://github.com/user-attachments/assets/c252f517-099c-42e5-9e2a-e093f07355d4" />
<img width="553" height="132" alt="Creating  Workspace In The Metasploit Frawork" src="https://github.com/user-attachments/assets/32f93075-3a4c-42bb-a081-afa0969f8ed4" />
<img width="539" height="129" alt="To Access Metasploit Framework Workspace" src="https://github.com/user-attachments/assets/7fbf8179-70f4-4eb4-8560-5e99e269cadd" />
<img width="553" height="63" alt="Check For Host In The Workspace " src="https://github.com/user-attachments/assets/39d0f12b-c0a2-41e7-9ca2-6243095476b4" />
<img width="554" height="59" alt="Adding Host In The Metasploit Framework 1" src="https://github.com/user-attachments/assets/91484cba-8f1a-4fe6-ba85-cbf5c665b6fa" />

 

# honeypot-2023
Modern Honeypot Network 

1. Installed Google SDK on my host machine. 
![image](https://user-images.githubusercontent.com/55906428/234359808-85161299-d36e-4f16-bda3-1753747ce424.png)

2. created a GCP account and setup the project.
![image](https://user-images.githubusercontent.com/55906428/234360410-81b78fc1-3d11-4f82-8497-a2fc9e158a29.png)

3. Created the Honeypot instance and the admin-console instance
![image](https://user-images.githubusercontent.com/55906428/234360146-00d48310-682a-4bd0-8bfd-b5b49a4ddb7d.png)

4. installed the honeypots
![image](https://user-images.githubusercontent.com/55906428/234360942-3e9b383f-fbdb-463c-9752-0d61614af7ab.png)

5. recorded attacks 
![image](https://user-images.githubusercontent.com/55906428/234361223-15d62293-84e6-4875-bdbb-d07fe4f27852.png)

Challenge Note: The first time I installed Google SDK and installed some honeypots it ran smoothly and I was able to download the session.json file 
in the GCP terminal. but, I was not unsuccessful in trasnfering the file from the VM to my host machine. I struggled with finding a solution. I decided to 
uninstall Google SDK and re-install it on my host machine and then run the commands on the host machine terminal. This time i was completely unsuccessful in 
downloading the session.json file and copying it to my host machine. I decided to uninstall it and reinstall Google SDK but this time I also deleted the 
project in GCP and the instances. I ran all the commands in GCP browser terminal and I was unsuccessful in copying the session.json file to my host machine.
I realized there was a conflict with the instances. I had installed the honey put in region/zone us-west-1b but I was in instance region/zone us-west-4b. 
I deleted the instances that were extra and ran the commands again and was successful in copying the file session.json and transferring to my Host machine. 
![session_json](https://user-images.githubusercontent.com/55906428/234366169-8bbb9f44-b2bf-4bd9-93f7-80ab3ee2d8ea.gif)
![Honey gif](https://user-images.githubusercontent.com/55906428/234366203-ebdeab10-089c-4df9-817e-d4515c8e591e.gif)

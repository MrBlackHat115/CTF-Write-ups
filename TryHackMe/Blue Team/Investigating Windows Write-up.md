# Investigating Windows

<img width="1099" height="132" alt="image" src="https://github.com/user-attachments/assets/2b586d25-2eae-4d0c-a4bc-f5f59bb3ef99" />

## Questions: 
- Whats the version and year of the windows machine?

- Which user logged in last?

- When did John log onto the system last?

- What IP does the system connect to when it first starts?

- What two accounts had administrative privileges (other than the Administrator user)?

- Whats the name of the scheduled task that is malicous.

- What file was the task trying to run daily?

- What port did this file listen locally for?

- When did Jenny last logon?

- At what date did the compromise take place?

- During the compromise, at what time did Windows first assign special privileges to a new logon?

- What tool was used to get Windows passwords?

- What was the attackers external control and command servers IP?

- What was the extension name of the shell uploaded via the servers website?

- What was the last port the attacker opened?

- Check for DNS poisoning, what site was targeted?

## Answers:

<img width="1202" height="395" alt="image" src="https://github.com/user-attachments/assets/8b217f45-1390-45d4-86bc-e0bf24182f4c" />

- Whats the version and year of the windows machine?
  - Windows Server 2016
 
<img width="702" height="79" alt="image" src="https://github.com/user-attachments/assets/5e929b64-2880-46b7-a8c0-70304dfe6dc5" />

- Which user logged in last?
  - 

<img width="440" height="438" alt="image" src="https://github.com/user-attachments/assets/a9b4a288-22d3-4dc8-a70e-a08a3a15ea36" />

- When did John log onto the system last?
  - 

<img width="709" height="146" alt="image" src="https://github.com/user-attachments/assets/275e05db-b165-4328-b77a-67ddaf0b5255" />

- What IP does the system connect to when it first starts?
  - We open regedit, head to `HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Run`; this is where all of the startup programs are, meaning if the system starts up, then the program will execute.

<img width="739" height="222" alt="image" src="https://github.com/user-attachments/assets/56ee6a85-f4d8-4010-94e0-4f82a7f6e4a4" />

- What two accounts had administrative privileges (other than the Administrator user)?
  - 

<img width="648" height="351" alt="image" src="https://github.com/user-attachments/assets/5d9b3753-fbd1-4018-93ae-cebe691983d3" />

- Whats the name of the scheduled task that is malicous.
  - 

<img width="270" height="55" alt="image" src="https://github.com/user-attachments/assets/76b1f6fe-a9e4-4dad-9a3f-6d2c8efebb4a" />

- What file was the task trying to run daily?
  - 

- What port did this file listen locally for?
  - 

<img width="486" height="435" alt="image" src="https://github.com/user-attachments/assets/1343fd07-e021-4629-9431-90e1f2d99c82" />

- When did Jenny last logon?
  - 

<img width="552" height="241" alt="image" src="https://github.com/user-attachments/assets/40686f37-ae29-435b-aab7-607eb49f5040" />

- At what date did the compromise take place?
  - I went to File Explorer to take a look at this fake `TMP` folder. This folder is fake because a real `Temp` folder is located in `C:\Windows\Temp`. The date of this fake `TMP` folder is the date the compromise took place.

<img width="524" height="40" alt="image" src="https://github.com/user-attachments/assets/8db269e9-9145-49c9-ad1c-dc861dc823e7" />



- During the compromise, at what time did Windows first assign special privileges to a new logon?

- What tool was used to get Windows passwords?

- What was the attackers external control and command servers IP?

- What was the extension name of the shell uploaded via the servers website?

- What was the last port the attacker opened?

- Check for DNS poisoning, what site was targeted?



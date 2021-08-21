# Red-Team

## Unit README: Red Team for Project 2

### Assessment Summary
The Red Team uncovered the following:

  - Accessed the system via HTTP Port 80 --> [Nmap Screenshot](https://github.com/hart2533/Red-vs-Blue-PROJECT-2/blob/main/Red_Team/RED_TEAM_Screenshots/Nmap_RED_TEAM.png)
  - Found Root accesesibility
  - Found the occurrence of simplistic usernames and weak passwords --> [Hydra Command Screenshot](https://github.com/hart2533/Red-vs-Blue-PROJECT-2/blob/main/Red_Team/RED_TEAM_Screenshots/Hydra_RED_TEAM.png)
  - Brute forced passwords to gain system access --> [Gaining Access](https://github.com/hart2533/Red-vs-Blue-PROJECT-2/blob/main/Red_Team/RED_TEAM_Screenshots/Login_RED_TEAM.png)
  - Cracked a hashed password to gain system access and used shells script --> [Cracking Ryan's Password](https://github.com/hart2533/Red-vs-Blue-PROJECT-2/blob/main/Red_Team/RED_TEAM_Screenshots/Hashed_Password_RED_TEAM.png)
  - Identified LFI vulnerability --> [Meterpreter](https://github.com/hart2533/Red-vs-Blue-PROJECT-2/blob/main/Red_Team/RED_TEAM_Screenshots/LFI_Vulnerability_RED_TEAM.png)
      - [Flag Found](https://github.com/hart2533/Red-vs-Blue-PROJECT-2/blob/main/Red_Team/RED_TEAM_Screenshots/Flag_RED_TEAM.png)
  - Identified Directory Vulnerability CWE-548

# Lab: Performing a Buffer Overflow

## Objective
The point of this lab was to test and use Kali Linux Metasploit to perform a buffer overflow against Windows XP PRO. 

## Steps taken
- Verified both IP addresses of the Kali Linux and XP virtual machines
- Checked connections and users before implementing anything
- Used the exploit on Kali and established the connection
- Looked at Task Manager on XP to see the process running
- Performed a hashdump on Kali to get the password hashes of the users on XP
- Remotely created a new user and set them to administrator on the XP machine, via Kali
- Collected evidence that the tasks were successful

## Screenshots and observations
*Placeholder for images*

## Key takeaways
During this lab, I learned how easy it was to get into a vulnerable machine with simple tools and start manipulating it, without anyone knowing it was happening. 

It was also almost impossible to tell by looking at the task manager and didn't produce any logs in the event viewer, which makes it even more dangerous.

## Relevance
This lab was relevant because it shows how easy it is to exploit vulnerable systems, without the victim knowing anything is going on. It also proves how easy it is to manipulate and steal information without being near the victim's PC.

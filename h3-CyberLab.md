# x) Read/watch/listen and summarize


1. Karvinen (2020): Command Line Basics Revisited

###### Overview
Nice refresher to learn and revisit essential Linux command-line basics. Includes clear examples and explanations.
Some new things I learned:

  a. Install example software quickly: sudo apt-get -y install krita blender vlc tree httpie curl tmux python3-py
  b. Pipe command output into less for easier reading: ls /etc | less
  c. $ means a normal user prompt — don’t type it.
  d. Use Ctrl + R to search command history.
  e. Be cautious with rm — no undo option.


2. Karvinen (2022): Cracking Passwords with Hashcat

###### Overview
Hands-on tutorial for cracking password hashes using Hashcat. Covers setup, hash identification, and running dictionary attacks.

Key takeaways:

  a. RockYou wordlist (~14.3 million passwords) is a great starting point for dictionary attacks.
  b. Installed Hashcat and followed the tutorial successfully.
  c. Cracked the example password using an MD5 hash.


Good to know:
  a. GPU acceleration gives major speed boosts (use native host OS with NVIDIA/CUDA drivers).
  b. Hashcat automatically detects GPUs — avoid running in VMs for better performance.


# b) Install Linux:

As I am using MAC so I will installing UTM and configuring dabian 11 with that.
The steps were quite easy 
1. install UTM on MAC from https://mac.getutm.app/
2. configure the space that you would like to allocate to the VM.
3. Download the OS you want to run on the UTM from this link https://mac.getutm.app/gallery/
4. once Downloaded , unzip the package and mount the .utm file.
<img width="901" height="651" alt="Screenshot 2025-11-11 at 17 43 54" src="https://github.com/user-attachments/assets/aa41051f-2680-461e-8410-fdeb3cec8ae9" />



# C) Crack password with hashing technique 
followed the samwe instruction as in the first task.
I have attached the output here:

<img width="728" height="473" alt="Screenshot from 2025-11-11 07-02-58" src="https://github.com/user-attachments/assets/c96974a2-dded-405b-9256-c384131f653f" />


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

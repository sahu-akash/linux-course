# Feed me – Assignment Report

#### a) Installing a Feed Reader
1. I installed **Thunderbird** as my feed reader. It supports RSS/Atom feeds and is easy to configure.


<img width="860" height="594" alt="Screenshot from 2025-11-18 02-56-47" src="https://github.com/user-attachments/assets/10b17c33-2e39-4e9d-97af-d1b4eafd0122" />

<img width="853" height="594" alt="Screenshot from 2025-11-18 03-02-16" src="https://github.com/user-attachments/assets/50b523de-f3fb-4601-a220-691e8d1a4694" />

<img width="1322" height="811" alt="Screenshot from 2025-11-18 03-18-16" src="https://github.com/user-attachments/assets/ec383cf3-f081-43d1-8cba-29010f8dc48d" />

<img width="862" height="608" alt="Screenshot from 2025-11-18 03-18-53" src="https://github.com/user-attachments/assets/5598aed0-f577-416c-801a-9e0d6beb127b" />


2. I added a test feed to confirm the reader works correctly and verified that articles load as expected.

   
<img width="880" height="719" alt="Screenshot from 2025-11-18 03-19-28" src="https://github.com/user-attachments/assets/84724bba-7de8-4e39-b2db-8eb871ec460a" />


---

#### b) Adding Krebs on Security Feed
Feed added:

- **Krebs on Security RSS:** https://krebsonsecurity.com/feed/
- 
<img width="862" height="611" alt="Screenshot from 2025-11-18 03-58-15" src="https://github.com/user-attachments/assets/e79d76d9-cd89-4318-a6e5-1123a5bfeb8c" />

<img width="885" height="612" alt="Screenshot from 2025-11-18 03-58-58" src="https://github.com/user-attachments/assets/8a79f93c-86a4-421e-a3c7-a853a28b80fd" />

---

#### c) Adding Schneier on Security Feed
Feed found and added:
- **Schneier on Security Atom:** https://www.schneier.com/blog/atom.xml
- 
<img width="885" height="730" alt="Screenshot from 2025-11-18 04-22-42" src="https://github.com/user-attachments/assets/322b47b5-1c73-4aa1-bcc8-29111a9e1b53" />

- Found many RSS feeds on reddit: https://www.reddit.com/r/cybersecurity/comments/1fbeym6/current_updated_rss_feeds/

---

#### d) Adding Two Additional Security-Related Feeds

- Add 2 new RSS
- 1. Troy Hunt RSS: https://www.troyhunt.com/rss/
     - reasons to choose Troy: Troy Hunt is a globally respected security researcher. Writes deep-dive articles on breaches, password security, and cyber hygiene

  2. Securelist RSS: https://securelist.com/feed/
     - reason to choose SecureList: Its managed by Kaspersky’s GReAT team. It includes information about malware, APTs, botnets, 0-days, campaigns and threat intelligence.
- 
- <img width="885" height="730" alt="Screenshot from 2025-11-18 04-34-59" src="https://github.com/user-attachments/assets/02132752-dd00-452d-b11e-532986d7b807" />

- <img width="1667" height="730" alt="Screenshot from 2025-11-18 04-36-20" src="https://github.com/user-attachments/assets/4d1b5df5-c501-4aed-8091-c3fcce3ce12c" />

#### e) Follow the security feeds for a while
What I learned

- Several new vulnerabilities appear daily (e.g., CVEs, ransomware variants).
- Many attacks begin with phishing or misconfigurations.
- Patch releases often happen quietly, announced only through RSS feeds.

Benefits of using a feed reader

- Centralized view of many security sources → saves time
- No ads, trackers, or social media distractions
- Easy to follow many sites at once

Downsides
- Articles may appear too frequently → information overload
- complex setup
- Too much to read because of Quick updates on certain interest topics

#### e) Port scan
- Installing Nmap
  Nmap ("Network Mapper") is a free and open source utility for network discovery and security auditing.
  <img width="713" height="826" alt="Screenshot from 2025-11-18 05-20-11" src="https://github.com/user-attachments/assets/90619185-7681-4f5b-bc11-993261179628" />
  
- Port scan your own computer. Use "localhost" as the address.
  installed Nmap for localhost with command sudo nmap -A -v localhost
  <img width="718" height="921" alt="Screenshot from 2025-11-18 05-28-41" src="https://github.com/user-attachments/assets/e1345e8d-f8d5-4afb-9fbb-ca2756f095b4" />
  <img width="718" height="921" alt="Screenshot from 2025-11-18 05-28-53" src="https://github.com/user-attachments/assets/0bd05f1d-db1b-4fc9-aa96-c0d157d758ad" />
  Findings: Some local open ports were found
  
- Install a daemon apache2 and start apache2
  
  
- Port scan again

  <img width="718" height="901" alt="Screenshot from 2025-11-18 05-45-34" src="https://github.com/user-attachments/assets/2b9fb91a-e2f2-4b84-85b7-cf4aeab82856" />

- Analyze and explain the results
  - Before installing Apache:
    Only a few system ports were open (e.g., 22/ssh). Services were minimal.
  - After installing Apache:
    A new open port appeared: 80/tcp (Apache running).
Nmap also detected the server banner and version.
This demonstrates that installing services automatically exposes ports, and attackers could discover them via scans.
   


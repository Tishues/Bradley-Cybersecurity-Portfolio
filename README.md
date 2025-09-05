# Bradley-Cybersecurity-Portfolio
## Freelance Web Application Penetration Tester

Hi, I’m Brad — an aspiring **penetration tester** with a strong foundation in **Python programming** and a growing track record in **hands-on security labs**. This portfolio showcases my practical projects, learning journey, and the skills I bring to real-world security challenges.

---

## TryHackMe Learning Experience
I’ve completed a wide range of interactive labs and hands-on rooms on TryHackMe that have developed my practical skills in web application testing, infrastructure exploitation, and cybersecurity fundamentals.

### Web Application Exploitation
Gained hands-on experience identifying and exploiting common vulnerabilities in modern web applications, following OWASP Top 10 principles and manual testing techniques.

**Key rooms:**
- **Authentication Bypass** – Exploited broken login logic and weak session management.
- **IDOR (Insecure Direct Object Reference)** – Accessed unauthorized data by manipulating URL parameters.
- **SQL Injection** – Injected malicious queries to bypass login and extract data.
- **Command Injection** – Executed OS-level commands via insecure input handling.
- **File Inclusion** – Discovered and exploited LFI/RFI vulnerabilities to access sensitive files.
- **Intro to SSRF** – Used internal server requests to access protected resources.
- **Intro to Cross-site Scripting** – Injected scripts to hijack sessions and modify page behavior.
- **Content Discovery** – Found hidden files and endpoints through forced browsing.
- **Subdomain Enumeration** – Uncovered additional targets via DNS and subdomain fuzzing.
- **Walking an Application** – Mapped out application logic, user flows, and input points.
- **Burp Suite: The Basics** – Intercepted and modified HTTP requests to identify vulnerabilities.
- **Putting it All Together** – Connected web components into a full exploitation workflow.
- **How Websites Work** – Built foundational understanding of frontend/backend interaction.

### Supporting Skills – Infrastructure & Exploitation
Built complementary skills to support web testing by exploring Linux privilege escalation and Active Directory enumeration.

**Key rooms:**
- **Linux Privilege Escalation** – Identified misconfigurations (e.g., SUID, writable files, sudo abuse) to gain root access.
- **Active Directory: Basic Enumeration** – Explored AD structures and queried users, groups, and shares.
- **Race Conditions** – Demonstrated timing-based attacks to exploit concurrency vulnerabilities.

### Foundational Knowledge
Strengthened understanding of networks, protocols, and system design to support more effective testing and report writing.

**Key topics covered:**
- OSI model, LAN design, TCP/IP fundamentals
- Packets vs. frames and data transmission
- NAT, port forwarding, and basic routing

> I continue to grow my skills through hands-on labs, vulnerable machine walkthroughs, and real-world scenarios focused on offensive security.

---

## Walkthroughs & Writeups
Real-world practice and analysis of vulnerable machines and challenges.

- **Linux Privilege Escalation – TryHackMe**  
  Explored misconfigurations like writable `/etc/passwd`, abused SUID binaries, and leveraged `sudo` misuses to escalate privileges on a Linux machine. 
  
  🔗 [Read the full writeup](writeups/linux-privilege-escalation/README.md)

---

## Python Projects
In addition to hands-on security labs, I’ve built small Python projects to develop my scripting skills — useful for automating recon, analyzing data, and testing attack surfaces.
- **Static Site Generator**  
  Converts markdown to HTML; useful for testing web server configs & static site vulnerabilities.  
  [🔗 View Repo](https://github.com/Tishues/static_site_generator)

- **Maze Solver**  
  Navigates a text-based maze using pathfinding algorithms; demonstrates pathfinding and logic.  
  [🔗 View Repo](https://github.com/Tishues/Maze-Solver)
  
- **BookBot**  
  Analyzes book text for word frequencies and patterns; applies text parsing & frequency analysis.  
  [🔗 View Repo](https://github.com/Tishues/bookbot)

- **Asteroids Game**  
  Python clone of the classic arcade game using Pygame; shows object-oriented design & real-time logic.  
  [🔗 View Repo](https://github.com/Tishues/Asteroids)

---

## Offensive Security Toolkit
### Web App Testing Tools
- **Burp Suite** – Used Proxy, Repeater, and Intruder to intercept and manipulate HTTP traffic
- **Gobuster, FFUF** – For directory brute-forcing and content discovery
- **Wfuzz** – Parameter fuzzing to uncover hidden functionalities
- **Sublist3r, Dig** – For DNS and subdomain enumeration
- **cURL, Postman** – Manual testing of HTTP requests and APIs
- **Browser DevTools** – Analyzing frontend behavior and debugging requests
### Exploitation & Enumeration
- **Netcat** – For reverse shells and port listening
- **LinPEAS, sudo, SUID techniques** – Linux privilege escalation
- **Enum4linux** – Enumerating SMB shares and Active Directory
- **Nmap** – Service discovery and vulnerability scanning
- **Wireshark** – Packet inspection for deeper network analysis
- **Python** – Custom scripts for automation, payload crafting, and recon; see my [Python Projects](#python-projects).
### Environment & Workflow
- **Linux CLI** – Daily driver; comfortable with shell navigation and scripting
- **Git & GitHub** – Version control and project tracking
- **VS Code** – Primary code editor for scripting and analysis

## Skills
### Web Application Penetration Testing
(SQLi, XSS, IDOR, LFI/RFI, SSRF, Command Injection, Auth Bypass)
- Manual vulnerability discovery (logic flaws, parameter tampering)
- HTTP request/response analysis
- Authentication and session management testing
- Subdomain enumeration and virtual host discovery
- Directory brute-forcing and file discovery
- OWASP Top 10 familiarity through practical labs
- API testing (parameter fuzzing, HTTP method abuse)
- Linux privilege escalation (SUID, misconfigs, cron jobs)
- Basic Active Directory enumeration (SMB shares, user/group recon)
- Network fundamentals (TCP/IP, DNS, OSI model, routing)

## Platforms & Labs
- **TryHackMe:** Offensive & defensive security modules  
- **OWASP Juice Shop:** Web app hacking lab (OWASP Top 10)  
- **Boot.dev:** Python backend web development

---

## Goals & Next Steps

- [X] Create **writeups and walkthroughs** for vulnerable machines  
- [ ] Build and share **custom pentesting tools** in Python  
- [ ] Develop **automated recon and enumeration scripts**  
- [ ] Contribute to CTFs or open-source security tools  
- [ ] Earn an entry-level certification (e.g. CompTIA Security+, PNPT, or eJPT)  

---

## 📬 Contact Me
Feel free to connect or reach out:
- GitHub: [github.com/Tishues](https://github.com/Tishues)  
- Email: [brad.cybersec@outlook.com](mailto:brad.cybersec@outlook.com)
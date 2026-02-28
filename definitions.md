### Electronic Health Record (EHR)
Computer system that collects, stores and manages patient health data such as medical history, diagnoses, treatments and test results. This systen allows secure access and exchange between different medical centers

<img width="500" height="320" alt="image" src="https://github.com/user-attachments/assets/8b85da75-2180-46ac-83bc-7aa6b270cbef" />

An EHR database can contain several interconnected databases. One for patients (with personal data and other information), another for diagnoses, another for appointments, prescriptions, lab results etc. Eachr record is linked with a unique patient ID, allowing medical workers instantly see the whole medical history for their patient and update it securely after the visit. This way of storing information does not only improve the accuracy of medical data, but also ensures fast communication between different medical institutions.

Reference: https://www.iso.org/healthcare/electronic-health-records#:~:text=An%20electronic%20health%20record%20(EHR)%20is%20a%20digital%20repository%20of,%2C%20settings%2C%20treatments%20and%20conditions.

## Penetration test 
Simulating a hacker attack with different stages of knowlegde.
### Penetration testing execution standard 

### Black box penetration testing approach 
Tester has no provided information whatsoever, the tester follows the approach of an unprivileged attacker meaning the tester has no prior knowledge / no insider information.

Strengths: This scenario can be seen as the most authentic, demonstrating how an attacker with no inside knowledge would target and compromise an organisation, its the most realistic option 

Weaknesess: It is really costly since it requires more time and effort for discovery. The tester may miss deeper flaws from within the system.

### White box penetration testing approach
It involves sharing full network and system information with the tester, including network maps and credentials. Usefull for simulating a targeted attack on a specific system utilising as many attack vectors as possible.

Strengths: Allows in-depth analysis of code, architecture, and security controls. Its fast to uncover vulnerabilities and exploits

Weaknesess: Not realistic from an outsider threat. May be unrealistic since hackers don't normally have that much information

### Grey box penetration testing approach
Only limited information is shared with the tester. Usually this takes the form of login credentials. Grey box testing is useful to help understand the level of access a privileged user could gain and the potential damage they could cause.

Strengths: Grey box tests strike a balance between depth and efficiency and can be used to simulate either an insider threat or an attack that has breached the network perimeter.

Weaknesess: May overlook some external vulnerabilities or may miss very deep flaws only visible through complete code access.

Source: https://www.redscan.com/news/types-of-pen-testing-white-box-black-box-and-everything-in-between/

## Data integrity 
Data integrity is a concept and process that ensures the accuracy, consistency and validity of an organization’s data. Organizations not only ensure the integrity of the data but guarantee they have accurate and correct data in their database.
In a hospital, data integrity can include keeping patient's private information, health report, diagnostic reports, and other records. The management of such data is a difficult task for health professionals. Attackers specifically target healthcare sub‐domains to manipulate valuable data. 

Source: https://www.fortinet.com/resources/cyberglossary/data-integrity
https://pmc.ncbi.nlm.nih.gov/articles/PMC8136763/

## Rules of engagement
Rules of engagement describe a companies unified rules for users who want to do penetration testing on a companies online assets.They are the safety net that ensures security activities are effective, ethical, and legally sound. 
They safeguarde the companies infrastructure and customer data. RoE define the boundaries, expectations, and communication standards between all parties involved.

It consists of the following parts 
- scope definition (what systems, networks, and data can be tested or accessed)
- authorization ( f.x. not by the hospital director but by the chief of IT) 
- communication protocols (who needs to be informed before, during, and after activities) 
- testing methods and limitations (f.x you might be allowed to do phishing but not a Denial of service attack which can disrupt operations) 
- data handling and confidentiality ( how data uncoverd during penetration testing is stored, encrypted, shared, and eventually destroyed) 
- Incident handling procedures (If a tester discovers a live security breach unrelated to the current engagement) 
- exit criteria and reporting requirements (explaining what was done, what was found, and recommendations for remediation) 

https://www.microsoft.com/en-us/msrc/pentest-rules-of-engagement?msockid=32adca13ccda6ffc2263dc44cdb16e79 
https://isosecu.com/blog/rules-of-engagement  
## Open-source intelligence (OSINT)

the practice of collecting and analyzing information from publicly available sources to produce actionable intelligence

This involves gathering data from sources such as websites, social media, news outlets, and public records to identify patterns, assess threats, and inform decision-making in various fields, including cybersecurity, national security, and business. 

in the context of cybersecurity: Many organizations use OSINT as a cybersecurity tool to help gauge security risks and identify vulnerabilities in their IT systems. Cybercriminals and hackers also use OSINT techniques for social engineering, phishing and exposing targets for cyberattacks.


sources 

https://www.sans.org/blog/what-is-open-source-intelligence

https://www.ibm.com/think/topics/osint

## Search engine dorking
Using advanced search operators in the search engine to find publicly available information that should be private. This can include server credentials, private documents and databases that were incorrectly protected. This is similar to OSINT but designed to find information that was mistakenly made public. Originally, this technique was introduced to find insecurities in servers and prevent data breaches, but nowadays hackers exploit search engine dorking for malicious purposes. 

References:  

https://www.forbes.com/sites/technology/article/google-dorking/ 

## Network scanning

Network scanning is a proccess that involves finding active devices in a network by sending signals and checking the responses. It's mainly used for monitoring, management, and spotting vulnerabilities. This process is necessary to protect networks from cyberattacks, it's an essential network security tool and should be performed regularly since most of the time cyberattacks happen daily,

https://www.techtarget.com/searchnetworking/definition/network-scanning 

## Network mapping 

Network mapping is the process of developing visual representations of a network's physical and logical structure, including all of te devices that are connected.

Example of a network map;

<img width="1024" height="769" alt="image" src="https://github.com/user-attachments/assets/e110b318-9e57-45c7-aaad-aae067bedfbd" />

https://faddom.com/network-mapping-tools/#:~:text=Network%20mapping%20is%20the%20process,vulnerabilities%2C%20and%20troubleshoot%20issues%20efficiently.

## Network topologies 

Network topology refers to the logical and physical structure of a computer network's nodes and connections that control data flow between devices. Network topology is an important in network design and management since it affects network performance, security, and scalability.

Types:

- Point-to-point topology
- Bus topology
- Ring topology
- Star topology
- Tree topology
- Mesh topology
- Hybrid topology

<img width="1024" height="536" alt="image" src="https://github.com/user-attachments/assets/80a8245a-cb96-409b-bd4b-91d1bd042425" />


https://www.ibm.com/think/topics/network-topology
## Port scanning
A port is a point on a computer where information exchange between multiple programs and the internet to devices or other computers takes place.

A port scan is a common technique hackers use to discover open doors or weak points in a network. A port scan attack helps cyber criminals find open ports and figure out whether they are receiving or sending data. It can also reveal whether active security devices like firewalls are being used by an organization. 

Port scanning can provide information such as:

- Services that are running
- Users who own services
- Whether anonymous logins are allowed
- Which network services require authentication

https://www.fortinet.com/resources/cyberglossary/what-is-port-scan 

## OS detection 

OS detection is a technique that basically detects the OS (operating system) of a specific device using a target network usign the TCP/IP stack of a device that it would be like its fingerprint. By sending probes and examining the responses, these tools compare the results against a database of known OS fingerprints to determine the most likely OS, which is valuable for finding vulnerabilities and understanding a target system for network security and penetration testing.

1. Passive OS Detection(Pof

   
This method involves analyzing network traffic that is already flowing, without sending any new packets.

What it analyzes: The distinctive characteristics of the headers of packets sent by the target system. Key elements include:

TTL (Time To Live): The initial value of the TTL field (e.g., Windows often starts at 128, while many Linux systems start at 64).

Window Size: The size of the TCP window advertised by the host, which is often unique to a specific OS and version.

DF (Don't Fragment) Bit: Whether the system sets this bit, which differs between operating systems.

2. Active OS Detection (Nmap)
   
This method involves sending specially crafted network packets (often unusual or non-standard) to the target machine and analyzing how the target system responds.

What it analyzes: The responses to these unusual packets. Common tests include:

TCP Initial Sequence Number (ISN) Sampling: Analyzing how predictable the target's random number generation is for the ISN.

IP ID Sequence Generation: Examining the pattern of the IP ID field in fragmented packets.

TCP Options and Flags: Checking which non-standard TCP options the host supports or how it responds to unusual flag combinations

IN THE CONTEXT OF CYERSECURITY:

Operating System (OS) Fingerprinting is the process of analyzing data packets which originate from a network in an attempt to glean intelligence to be used in later attacks. By detecting which operating system a network operates on, hackers have an easier time targeting known vulnerabilities. OS Fingerprinting can also collect configuration attributes from remote devices. This type of recon attack is usually the first step in a larger, persistent effort. Networks running old, outdated, or unpatched Operating Systems became big targets when attackers spot their weakness.

How to prevent it:

The best way to prevent fingerprinting is to limit the types of traffic that your network accepts and responds to, as well as tightly control what information your network returns. By blocking timestamps, echo replies, and address masks, admins can greatly reduce the usefulness of information that attackers can exfiltrate. Our team of certified engineers can help you reduce attack surfaces on your network and ensure that your firewall and operating system are as stealth as possible.

IN THE CONTEXT OF A HOSPITAL: OS detection takes on a critical role in managing security, compliance, and interoperability across a wide array of specialized devices.

The operating systems in a hospital aren't just limited to desktop computers; they include everything from patient monitoring systems to diagnostic equipment.

OS Detection in Healthcare: Key Applications

1. Security and Vulnerability Management
   
This is the most critical use, especially since healthcare data is a prime target for cyberattacks.

Risk Assessment: Hospitals use OS detection to maintain an up-to-date inventory of all connected devices (often called the "asset inventory"). This allows the security team to identify devices running outdated or unsupported operating systems (like older versions of Windows embedded in medical devices).

Targeted Patching: Knowing the exact OS and version allows administrators to quickly and accurately deploy security patches only to the devices that need them, minimizing downtime for critical equipment.

Segmentation: By fingerprinting the OS of different devices, the network can be segmented (separated). If a piece of aging radiology equipment running an old OS can't be patched, it can be isolated on its own network segment to prevent it from becoming a bridge for malware to reach the main patient record system (EHR).



IMPORTANT CONCEPTS:

TCP (Transmission Control Protocol): Ensures reliable, error-free communication. It establishes a connection before sending data, divides it into packets, numbers them, and ensures that they all arrive correctly.

IP (Internet Protocol): Responsible for addressing and routing packets across different networks. 



sources

https://www.youtube.com/watch?v=dSgHEL-MO3I

https://www.firewalls.com/blog/security-terms/os-fingerprinting/#:~:text=There%20are%20two%20types%20of,or%20actions%20against%20the%20network.


## Vishing 
Vishing (voice phishing) is described as a phishing attack through telephone call services. Vishing shares the same characteristics as phishing, impersonating a company employee or an individual to retrieve personal information, but through a call. Vishing attacks can also persuade the user to perform transactions by deceiving them. The call can be live, or it can be an automated text-to-speech system. The attackers will commonly impersonate employees of important jobs like banks, police or internet providers and will commonly propose an urgent problem that gives the user no time to think of the veracity of the caller.  

In contrast with phishing in which malware is the most common attack, it is rare and difficult that through vishing attacks malware is downloaded, as it should persuade the user to search on the internet and mislead them into downloading malware. For this reason, vishing attacks ask for relevant personal information like credit card information.  

To avoid being tracked by authorities if catched, vishing fraudsters may try to cover their real IP and phone number, like by using called ID spoofing. 
<img width="1960" height="1240" alt="Vishing-980x620px-1252439291" src="https://github.com/user-attachments/assets/48a9ad40-7a6d-4793-a9ce-911839096cbe" />

References: 

https://en.wikipedia.org/wiki/Voice_phishing 
Image from: https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.textmagic.com%2Fwp-content%2Fuploads%2F2023%2F10%2FVishing-980x620px.png&f=1&nofb=1&ipt=c0935417c4d4e4fdfe306e88d6060775c6a29eb15f404fc058b7ec10d854b1d3

## Pretexting 
Pretexting is the use of a fabricated story, or pretext, to gain a victim’s trust and trick or manipulate them into sharing sensitive information, downloading malware or others,harming themselves or the organization they work for.
Healthcare data is often referred to as some of the most sensitive and valuable information in the world. This includes:
- Personal Health Information: Data such as medical records, test results, prescriptions, and diagnoses.
- Personally Identifiable Information: Information like names, addresses, social security numbers, and health insurance details.
- Payment and Insurance Information: Data related to insurance policies, billing, and payment history.
  
These attacks can lead to data breaches, loss of patient trust, legal ramifications, and significant financial losses. 

Examples of pretexting attacks in healthcare:

- Impersonating a doctor or nurse.
- Impersonating insurance representatives
- Fake internal requests for data access

Sources:
https://www.ibm.com/think/topics/pretexting

https://www.cyberly.org/en/how-do-pretexting-attacks-affect-healthcare-organisations-and-their-data-security/index.html

## Security posture assessment 

Security posture assesment is an examination of the internal (protection within the network, e.g., firewalls, access controls, employee security policies, internal systems) and external (protection agaisnt external threats, e.g., perimeter firewalls, intrusion detection, anti-DDoS systems, public-facing servers) security of an organization to asses how prepared the company is in terms of cybersecurity and its ability to protect its assets, data, and operations from cyber threats. Once the situation of the cybersecurity protection systems are analyzed improvements are reccomended to improve even further the security and protection.

https://www.picussecurity.com/resource/glossary/what-is-security-posture-assessment

## Social engineering attack 
A social engineering attack refers to a wide range of attacks that leverage human interaction and emotions to manipulate the target. During the attack, the victim is deceived into giving away personal/sensitive information or compromising security.

A social engineering attack usually takes place in multiple steps: The attacker will first research the potential victim and gather the necessary information about them. This information can be put to use to bypass security protocols or get information. Then the attacker will try to gain the Victim's trust before finally manipulating the victim into giving in to sensitive information or violating security policies.

Source: https://www.fortinet.com/resources/cyberglossary/social-engineering

## Network attack

A network attack is any intentional action taken to compromise security, availability, integrity or confidentiality of a computer network or the systems and data that are connected to that network. Usually, to execute a network attack, hackers exploit vulnerabilities in hardware, software or human factors to gain unauthorized access to the data. The goal of a network attack can be stealing sensitive data, disrupting services and infrastructure, modifying or falsifying information, establishing consistent access to the system (backdoor), gathering information for later attacks.

The most common types of attacks hackers execute are:

- Denial of Service (DoS) -> Distributed DoS – overwhelm resources to crash the servers
- IP / DNS spoofing – falsifying network identity
- Packet sniffing – capturing unencrypted traffic
- Port scanning – probing to discover services and vulnerabilities
- A man in the middle - it invlolves attackers intercepting traffic, either between your network and external sites or within your network

To prevent those types of attacks cybersecurity specialists, use strong security measures such as firewalls, intrusion detection systems, and encryption to protect data during the transit. They regularly update the software; in case there is a vulnerability in there. In a closed network, they usually limit user access through least privilege policies.

<img width="660" height="512" alt="image" src="https://github.com/user-attachments/assets/35117165-2265-491b-bdf3-9e8b72ffda4f" />

Reference: https://www.cynet.com/network-attacks/network-attacks-and-network-security-threats/

## Exploit development 
Exploit:
An exploit is a code that takes advantage of a software vulnerability or security flaw.

Exploit development is a specialized area within the field of cybersecurity that focuses on discovering and utilizing software vulnerabilities. At its core, it involves analyzing software to find weak spots and then crafting exploits. This could be to gain unauthorized access, escalate privileges, or achieve other objectives.

The process often begins with vulnerability assessment, where researchers or attackers identify potential weak points in software. Once a vulnerability is identified, the exploit developer crafts code to specifically target that vulnerability. The developed exploit is then tested and refined until it can reliably bypass security measures and achieve its intended effect.

<img width="667" height="500" alt="image" src="https://github.com/user-attachments/assets/54da8850-237c-4b79-9a6d-9ede7243c2e4" />

Structure or an exploit / context definitions:


<img width="614" height="273" alt="image" src="https://github.com/user-attachments/assets/6c7ced31-9ddc-40a2-859e-19b61ddb2c4e" />


Vulnerabilities
Vulnerabilities refer to weaknesses or flaws in a system, application, or protocol. They represent points where an attacker can insert or execute malicious code, bypass security measures, or perform unauthorized actions. Vulnerabilities can come from software bugs, inadequate security controls, misconfigurations, or even unintended features.

Exploit techniques
Exploit techniques define the 'how' of the exploitation process. Each technique provides a different method of leveraging a vulnerability to achieve a desired outcome. Familiarity with these techniques enables both the development of effective exploits and the creation of defenses against them.

Shellcode & payloads
Shellcode is a small piece of code used as the payload in the exploitation process. It often provides a command shell to the attacker, hence the name. Payloads, on the other hand, refer to the actual malicious data or actions that the attacker wants to deliver and execute on the target system.

Once a vulnerability is exploited, the shellcode or payload is what achieves the attacker's final objective. Whether it's creating a backdoor, initiating a ransomware attack, or stealing data, the payload dictates the endgame of the exploit. The shellcode serves as the bridge, facilitating the delivery and execution of this payload.


Sources:
https://www.offsec.com/cyberversity/exploit-development/
https://github.com/paulveillard/cybersecurity-exploit-development/blob/main/README.md


## SQL injection 
SQL stands for Structured Query Language, it communicates with the database.

SQL injection is a web-security vulnerability where an attacker manipulates an application’s input so that the application sends unexpected SQL to its database. 
https://cwe.mitre.org/data/images/CWE-89-Diagram.png<img width="680" height="591" alt="image" src="https://github.com/user-attachments/assets/914d26b2-452c-4df4-b55f-c834b8944caf" />
A succesful sql injection might allow the hacker to:

-read sensitive data from the database

-modify database data (Insert/Update/Delete)

-execute administration operations on the database

-issue commands to the operating system





sources:
https://owasp.org/www-community/attacks/SQL_Injection
https://cwe.mitre.org/data/definitions/89.html

## Cross-site scripting (X-SS)
https://www.google.com/url?sa=t&source=web&rct=j&url=https%3A%2F%2Fwww.spanning.com%2Fblog%2Fcross-site-scripting-web-based-application-security-part-3%2F&ved=0CBYQjRxqFwoTCMDh3sqD_ZIDFQAAAAAdAAAAABAH&opi=89978449![Uploading image.png…]()

Cross-site scripting(x-ss) is a security vulnerability presented by websites that allows attackers to inject malicous client-sided scripts into webpages that are vulnerable and frequently entered by clients, compormising the website and every data it is stored in the website. This security vulnerability is seeking to get private cookies from users, credentials, and personal information that are stored in the website by the users.

It is divided into 3 different steps.

1.INJECTION: that is when the attacker enters the website and inserts the malicious script (often javaScript)

2.EXECUTION: When a user enters the webpage and without the knowledege of the user the browser executes the malicious script without knowing.

3.EXPLOITATION:The attacker can then perform actions, such as stealing user cookies, redirecting users to malicious sites, or capturing login credentials.

TYPES OF X-SS

1.Reflected XSS Attacks:

Reflected attacks are those where the injected script is reflected off the web server, such as in an error message, search result, or any other response that includes some or all of the input sent to the server as part of the request.

2.Stored XSS Attacks:

Stored attacks are those where the injected script is permanently stored on the target servers, such as in a database, in a message forum, visitor log, comment field, etc. The victim then retrieves the malicious script from the server when it requests the stored information.

3.Blind Cross-site Scripting:

Blind Cross-site Scripting is a form of persistent XSS. It generally occurs when the attacker’s payload is saved on the server and reflected back to the victim from the backend application.

In the context of a Hospital:

The cybersecurity team should prevent XSS attacks in hospital systems because:

Patient Data Security: Attackers could steal or compromise sensitive patient data (Electronic Health Records, billing info, etc.), violating privacy laws.

Device Malfunction: If connected medical devices (like patient monitors, infusion pumps, or even diagnostic equipment with web interfaces) are vulnerable, XSS could lead to device malfunction or unauthorized control, directly endangering patient lives.

System Integrity: It could allow an attacker to impersonate staff, execute unauthorized commands, or disrupt hospital operations, which can be devastating in a critical care environment.

Sources:

https://owasp.org/www-community/attacks/xss/

https://en.wikipedia.org/wiki/Cross-site_scripting#:~:text=Cross%2Dsite%20scripting%20(XSS),forms%20of%20data%20injection%20attacks.

## Buffer overflow attack 

A buffer overflow attack happens when an attacker sends more data to a buffer (a temporary data storage area in memory) than it can hold. This overflow causes the excess data to overwrite adjacent memory, corrupting data, crashing the system, or allowing the attacker to execute malicious code in the program. This attack targets flaws in software that do not properly validate or limit input size before storage.

Programs allocate fixed-size buffers for data, but if the program does not check the size of the input before copying data into the buffer, an overflow occurs. An attacker exploits this by sending excess data that overwrites memory critical for the program's execution flow, redirecting the program to run malicious payloads.

Types of buffer overflow attacks:

Stack overflow: occurs when too much data is written to a buffer located on the stack, causing it to overwrite nearby memory. This allows attackers to redirect the program's flow 

Heap overflow: writes excess data into the heap memory area, corrupting dynamically allocated memory. Attackers can corrupt data structures, pointers, or function calls maintained by the heap

Integer overflow: Exploits vulnerabilities related to arithmetic operations that cause unexpected buffer sizes. Attackers use integer overflows to bypass bounds checks, trigger vulnerabilities, or force improper memory allocation

Sources:
https://www.fortinet.com/resources/cyberglossary/buffer-overflow

https://www.imperva.com/learn/application-security/buffer-overflow/


## Pasword cracking tools 

Password cracking tools are special software that automate attempts to crack or recover a password for an account. They use different techniques to match candidate passwords against a protected target such as authentication endpoint or a password hash (mathematical representation of the password with the hash function. It translates password like Password123 into a fixed length of string of characters). These tools can initiate from exhaustive search to using a list of common passwords and precomputed mappings (table with premade password and hash pair).

Common attack types

- Brute force - try every possible combination of characters until certain length. It is extremely long and time consuming. Only used for short or low-complexity passwords or with massive computing power for larger passwords.
- Dictionary attack – try words and phrases from a prepared list (often with common or leaked variations). This method is effective against very weak and human chosen passwords
- Hybrid attack – combination of dictionary attack and applying small modifications such as adding more characters like numbers, changing case, repeating characters.
- Rainbow-table/Precomputed attacks – use of precomputed tables mapping hashes to plaintext to speed up recovery. It’s effective only against weakly stored hashes or people with the same passwords (since hashes of the same passwords are also the same)
- Credential stuffing – use of leaked username and password pair from one site to attempt logins on another site. For example, a password was leaked from a facebook account, the software will try to use the same credential for google account etc
- GPU cracking – use of GPUs to achieve huge computing power. All the power is used to initiate parallel hashing. Since GPUs have a lot of simple cores optimized to do the same calculation many times in parallel, it is going to decrease the time taken to hash the password.

<img width="700" height="330" alt="image" src="https://github.com/user-attachments/assets/fc771029-ab92-4139-991b-a51cf472f9ce" />

This is a picture of a popular password cracking tool called THC-Hydra. It's main function is use of brute force to crack passwords) 

Defenses against password cracking tools

- Enable multi factor authentication – without a code that updates regularly a hacker can not have access to your account
- Rate limit or block repeated failed login attempts – monitor and alert on any suspicious activity (effective against brute force and hybrid attack)
- Use long and unrepeatable passwords – use a password with special symbols, numbers, characters and without any real words

References: https://www.beyondtrust.com/blog/entry/password-cracking-101-attacks-defenses-explained#:~:text=Password%20Cracking%20Defined&text=Password%20hacking%20uses%20a%20variety,to%20as%20'password%20crackers


## Privilege escalation

Privilege escalation is a cyberattack that is specifically designed to gain non authorized access to a system in which the attacker elevates or modifies their access in a target system, for example, by switching from a basic user account with less privilege to an administrator account with more privilege.  Privilege escalation works by first gaining access to low privilege account through different techniques such as credential theft or phising, once the attacker is in, the atacker look for ways to gain privileged access from inside the system.

Types:

Horizontal privilege escalation or lateral movement is the process through which an attacker gains access to an account with a similar level of permissions. Moving horizontally allows hackers to increase their reach in order to obtain more information and cause more harm, even while they do not obtain additional permissions.

Vertical privilege escalation or privilage elevation is changing from a basic user account to one with administrative powers, often in order to advance from lower to greater privileges. 

## System forensics 
System forensics is the process of collecting, preserving, analyzing, and presenting digital evidence from computer systems and networks to determine what happened during a security incident or crime.
System forensics branches off from digital forensics, its especially focused on operating systems, file systems, logs, and memory. 

Common Forensics sources--> Hard drives and file systems, event and audit logs, registry entries, memory dumps, network traffic captures.

Source: https://www.koenig-solutions.com/blog/system-forensics-incident-handling

## Security posture assessment 
A security posture assessment is an in-depth examination of an organization’s internal and external defenses to evaluate its overall cybersecurity readiness. It supports cybersecurity planning by identifying gaps, measuring the effectiveness of existing controls, and informing risk-based strategies.

The goal of doing a security posture assesment is to determine the organization's ability to protect its assests/data from cyberattacks and threats. By doing this you enhance the organization's cybersecurity resilience.

Relating to System forensics: 
Security posture assessment helps prevent incidents. System forensics helps investigate them when they happen.

Source: https://www.picussecurity.com/resource/glossary/what-is-security-posture-assessment#:~:text=A%20security%20posture%20assessment%20is,the%20likelihood%20of%20successful%20cyberattacks.

## Response plan 
A cyber-attack response plan is a strategy to follow to prepare for, detect, and respond to a cyber-attack. This is essential to minimize the damage caused by a cyber-attack. Without it, the employees won’t be prepared and combined with a lack of organization chaos might reign.  

The response plan sometimes starts before the attack, in prevention. This comes in the form of training, backups, failover systems, and emergency protocols, among others. 

A general structure for  the response plan is: 

 <img width="1156" height="349" alt="imagen" src="https://github.com/user-attachments/assets/a83d2dc3-45fe-40d9-8adb-b9753669faa1"/>

Incident detection: Incident detection and response are the process and activities involved in the identification, analysing, and reacting to potential security incidents within an organisation's IT infrastructure. Incident detection refers specifically to the continuous monitoring of an organisation's infrastructure to detect any signs of malicious activity.

Response startegies: Response strategies are planned approaches used to manage and mitigate risks identified during a risk assessment process. These strategies can involve various methods such as avoidance, reduction, sharing, or acceptance of risks, aiming to minimize the negative impact of potential threats on objectives. The selection of a specific response strategy often depends on the nature of the risk, its potential impact, and the resources available for management.

Recovery processes: The recovery process in Computer Science encompasses actions and mechanisms designed to restore systems to their natural state and operating configuration following disruptions, thereby ensuring system reliability, availability, and data integrity.
 
References: 

https://www.ncsc.gov.uk/collection/incident-management/cyber-incident-response-processes 

https://docs.tenable.com/cyber-exposure-studies/nis-2-directive/Content/IncidentDetectionAndResponse.htm

https://fiveable.me/key-terms/introduction-industrial-engineering/response-strategies

https://www.sciencedirect.com/topics/computer-science/recovery-process

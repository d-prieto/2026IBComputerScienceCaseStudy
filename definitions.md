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

## Vishing 

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

## Social engineering attack 
A social engineering attack refers to a wide range of attacks that leverage human interaction and emotions to manipulate the target. During the attack, the victim is deceived into giving away personal/sensitive information or compromising security.

A social engineering attack usually takes place in multiple steps: The attacker will first research the potential victim and gather the necessary information about them. This information can be put to use to bypass security protocols or get information. Then the attacker will try to gain the Victim's trust before finally manipulating the victim into giving in to sensitive information or violating security policies.

Source: https://www.fortinet.com/resources/cyberglossary/social-engineering

## Network attack

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

## Cross-site scripting (X-SS)


## Buffer overflow attack 

## Pasword cracking tools 

## Privilege escalation

## System forensics 

## Security posture assessment 

## Response plan 




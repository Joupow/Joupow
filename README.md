# Hi, I'm Julien 👋

**Systems & Network Administrator  ·  Career Transition  ·  Hands-on labs · Security Focus**  
Based in Lyon, France · Open to apprenticeship and entry-level opportunities

I build and test infrastructure to understand how it behaves in practice.

That means configuring services, generating failures, tracing traffic, understand the mechanics & protcols, checking system state, troubleshooting issues and validating fixes.

Most of what you'll find here is hands-on in homelabs
## 🧪 Homelabs

#### 🏢 Dunder MifflAD · Active Directory & Windows Server

Built around the skills that keep showing up in Windows sysadmin job postings.  
I intentionally break services to practice diagnosis, recovery and proving the fix.

Hands-on with:

- AD DS, DNS, DHCP and GPO
- Windows LAPS and account lifecycle
- Multi-site Active Directory
- File services, DFS Namespace and DFS-R
- PowerShell administration

**Things I Broke:**

- DC discovery through stacked DNS failures
- DHCP availability after taking a domain controller offline
- Inter-site replication after a DC renumbering
- SYSVOL replication while AD replication remained healthy
- Contractor account lifecycle controls

#### 🌐 Dunder MiffLAN · Network Portfolio

Started as a way to turn CompTIA Network+ objectives into something tangible.  
Building it exposed routing, redundancy and service issues I had to troubleshoot along the way.

Hands-on with:

- VLANs, trunks, STP and inter-VLAN routing
- HSRP, OSPF and DHCP relay
- ASA, DMZ, NAT/PAT and ACLs
- Spine-leaf architecture and ECMP
- VoIP, QoS and Wi-Fi

**Things I Had to Troubleshoot:**

- Broken return paths
- Router-ID collisions
- DHCP reachability issues
- TFTP asymmetry
- Routing and NAT sequencing problems

## ⚙️ Side project

#### ⚙️ The Prompt · Portable LLM Learning Engine

Started as a way to get more hands-on with Python, PowerShell and Linux instead of just reading about them.  It grew into a portable learning engine I had to design around persistence, progression and cross-LLM compatibility.

Hands-on with:

- Prompt and system design
- Local state management with `SAVE.json`
- Cross-LLM portability
- Skill progression and retention logic
- Modular commands and learning workflows

**Things I Had to Figure Out:**

- Keeping progression across sessions and context windows
- Moving the same learning state between ChatGPT, Claude and Gemini
- Separating the learning engine from the narrative layer
- Tracking understanding, execution, debugging and autonomy independently
- Keeping the whole system lightweight enough to run from a few text files

## 📜 Certifications & path completed

- 🎓 Certified CompTIA Network+ → [Digital Badge](https://www.credly.com/badges/3e8506ad-6324-4331-a2ab-19224def8bfc/)
* 📚 Studying for CompTIA Security+
- 🔓 TryHackMe → [Completed Rooms](https://tryhackme.com/p/Joupow/)    

## 🧭 How I Work

- **I learn by testing systems, not just configuring them.** In networking, that meant tracing return paths, Router-ID collisions and TFTP asymmetry. In Active Directory, it meant deliberately breaking DNS, DHCP, inter-site replication and SYSVOL, then diagnosing and restoring them. If I cannot explain why something failed and why the fix worked, I do not consider it understood.

- **I trust observable state more than green lights.** Routing tables, ACL counters, event logs, replication state, service registrations and actual user impact tell me more than a successful-looking configuration screen. I try to validate systems end to end, before and after a fix.

- **I treat documentation as a deliverable, not an afterthought.** My background in copywriting and 3D animation is useful here: clear structure, precise communication, and diagrams whenever they genuinely make a concept easier to understand.

## 📫 Get in Touch

* 💼 [Linkedin](https://www.linkedin.com/in/julien-seren-8057113b9/)
* 📬 [Contact me](mailto:juliencybersecu@gmail.com)

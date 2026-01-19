# CISSP-mnemonics (Extended Edition)

Oh no, not another one who thinks it's a good idea to make a set of CISSP mnemonics 

> **⚠️ DISCLAIMER:**
> This repository is a collection of community-contributed mnemonics and notes intended for educational purposes only. While every effort has been made to ensure accuracy, **this content may contain errors, oversimplifications, or outdated information.** >
> This material is **not** an official study guide and should not be used as a primary source of truth. Always verify information against official (ISC)² publications, current CBK (Common Body of Knowledge), and standard industry documentation. The authors are not liable for any exam results or professional decisions made based on this content.

Original Version: https://github.com/TAbdiukov/CISSP-Mnemonics 

# Domain 1

## Must-know
### The CIA Triad
* **C**onfidentiality
* **I**ntegrity
* **A**vailability

**Plus:**
* **Authenticity**: Verifying that data, transactions, communications, or documents are genuine and originate from the claimed source.
* **Non-Repudiation**: Undeniable proof that an action occurred (Subject cannot deny doing it).

**The Anti-Triad (The "DAD" Triad)**
* **D**isclosure (Opposite of Confidentiality)
* **A**lteration (Opposite of Integrity)
* **D**estruction (Opposite of Availability)

### Risk Management Formulas
*the only mathematics in CISSP*

![Hotel Mario 1](https://static.wikia.nocookie.net/cd-i/images/a/a6/STUFF%21.jpg)  | ![Hotel Mario 2](https://static.wikia.nocookie.net/cd-i/images/9/9f/Hotelmario.jpg) |
---- | ---- |
(🍺) ALE causes AROSLE | (up my) SLEAV-EF
ALE = ARO x SLE | SLE = AV x EF

#### "ALE CAUSES AROSLE"
🍺 = 😍 (get it?)
[ALE = ARO x SLE](https://github.com/TheRealBenForce/cissp-mnemonics#risk-management)  

#### "(up my) SLEAV-EF"
(up my) SLEAV-EF  
[SLE = AV x EF](https://github.com/TheRealBenForce/cissp-mnemonics#risk-management)  

#### Value of a Safeguard
(ALE before safeguard) – (ALE after safeguard) – (Annual cost of Safeguard) = **Value of Safeguard**

## Laws and regulations

* SOX (Sarbanes Oxley, 2002) – [say in British accent] ENRON really SOX. Its transaction flow really SOX. Financial reporting.

* Gramm-Leach-Bliley Act (GLBA) – banks, lenders, insurance. Think about some **fat banker** Gramm (or Graham). Financial Privacy.
    ![Banker](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a3/The_Banker%2C_by_Isidor_Kaufmann.jpg/201px-The_Banker%2C_by_Isidor_Kaufmann.jpg)

* COPPA – Protects minors 13 or younger online. If you are an **online pedo**, then you **cop it**

* FERPA – Protects Student data for over 18. Think about Phineas and **FerP**. They have to grow up eventually and go to college. It would be really unfortunate for Phineas and **FerP** fans if **FerP**'s student card is leaked to public!  
    *However, student ID leak won't trigger data breach laws.*

* FISMA – **U.S. Government information security** is under **prisma**. [NIST SP 800-53 is used for FISMA]

* PCI DSS – Credit Card Security – Visa, MasterCard and American Express. What else is a card other than a credit card? – Your PCI card.
    * Note: PCI DS**S** is a **Standard**, not a law.
    * Requires: Ongoing compliance, risk assessment, network segmentation, 12 requirements.

* Digital Millenium **Copyright** Act (DMCA) – **Copyright**. Prohibits attempts to circumvent copyright protection.

### U.S. Privacy & Rights

* 4th Amendment in American Constitution grants right to privacy. **Prevents law enforcement search without probable cause.**

* Computer Fraud and Abuse Act – CFAA 1986 – **First** major legislation to fight cybercrime. Think: **CFAA – F for First**.

#### ECPA, CALEA, USA PATRIOT Act

* Electronic Communications Privacy Act – ECPA 1986 – Makes it illegal to invade electronic privacy of an individual.
* Communication Assurance for Law Enforcement Act – CALEA 1994 – Amends ECPA to make wiretaps possible for law enforcement.
* USA PATRIOT Act of **2001** – Broadened wiretapping authorizations.

### U.S. Import and Export

* Export Administration Regulation (EAR) – restricting export of **civilian items that may have military applications**, such as **EARphones**.
* International Traffic in Arms Regulations (ITAR) – restricting export of **war items**. Think "**ITAR is war**".

### U.S. Healthcare

* **H**IPAA – **Health privacy and security** regulations in case you get **HIPAAtitis**. PHI/ePHI. Includes $ penalties.
* **HITECH** – **Hospitals security** go hi-tech! Health IT for economic and clinical health.

### EU

* GDPR – EU Privacy Laws – cause cookie banners.
    * **72 hours**: Breach notification timeline.
    * **Right to be forgotten**.
    * **Data Portability**.
    * **Fines**: Up to 4% global revenue.
    * **Roles**: Data Processor acts on behalf of Data Controller.

### Extras

* California Consumer Privacy Act – CCPA – in **California** only.
* HSA – Homeland Security Act (2002).

## Security and Risk in the U.S.

* US**PT**O – **P**atents and **T**rademarks
* LO**C** – **C**opyright – (Library of Congress)
* U.S. **C**ode(x) – **C**riminal and **C**ivil Law
* Code of **Federal** Regulations – Administrative Law on Federal scale

## Due Care vs Due Diligence
* **Due Care** = **Do**ing. Actually doing the reasonable security (Action). The "Prudent Person" rule.
    * *Mnemonic:* using a condom is **due care**.
* **Due Diligence** = **D**etecting/**D**eciding. Verifying it was done, establishing a plan, or doing research before a decision.
    * *Mnemonic:* taking the steps to decide whether to use the condom is **due diligence**.

## Risk 

![Roku](https://image.roku.com/developer_channels/prod/81b0180e7b151201a10d7006b048ccbc0ea5695d8fd20d78462d2a13a99f3485.png)  
Mnemonic: Risk T.V.  

**Risk** = **T**hreat x **V**ulnerability

### Risk Responses (AMTA)
*In exact order of preference/operation:*
1. **A**void
2. **M**itigate (Reduce & accept residual risk)
3. **T**ransfer
4. **A**ccept

*Mnemonic:* **AMTA**

### Types of risk
* **In**herent – **In**itial risk **in**put before treatment
* **Re**sidual – **Re**maining risk **residing** after treatment

## Risk – RMF – NIST SP 800-37 (Rev 2)

* [Useful nist.gov illustration](https://csrc.nist.gov/projects/risk-management/about-rmf)

### Steps
1. **P**repare
2. **C**ategorize (systems)
3. **S**elect (controls)
4. **I**mplement (controls)
5. **A**ssess (controls)
6. **A**uthorize (system)
7. **M**onitor

### Mnemonic device
**PCS-IAAM** (PC-s I aam) — Being non-human is RISKy.

## Security Planning Timelines
* **Strategic**: 5 years (long term), includes risk assessment.
* **Tactical**: ~1 year (mid term), goals.
* **Operational**: Monthly/Daily (short term), detailed.

## Zero Trust Tenets
1. Never trust, always verify.
2. Least privilege.
3. Per-session access.
4. Continuous monitoring.

## BCP and DRP

* BCP – Business
* DRP – Technical

### NIST SP 800-34
**DC I DD PP**
* Develop (policy)
* Conduct BIA
* Identify (preventative controls)
* Develop DRP strategies
* Develop IT contingency (plan)
* Plan Training
* Plan maintenance

## Recovery acronyms

* RPO – Recovery **Point** Objective – **Data Loss** tolerance. (Time from last backup).
* RTO – Recovery **Time** Objective – **Downtime** tolerance. (Time from disaster to recovery).
* WRT – Work Recovery Time (Technical staff configuration).
* MTD – Maximum Tolerable Downtime. MTD = RTO + WRT.

*Check:* **RPO < RTO** generally implies Data Loss is less acceptable than Downtime.

# Domain 2

## Data roles

* Data **O**wner – **O**verall responsible. Business unit. **Crowns** it (Classifies it).
* Data **P**rocessor – **P**rocesses on behalf of controller.
* Data **C**ustodian – **C**omputer / IT. **Guards** it (Implements controls).
* Data **S**teward – **S**yndicate/Business data quality.
* **A**dministrators – **A**ssign permissions.

## Data Classifications

**Government (Military)**
* Top Secret (Grave damage)
* Secret (Serious damage)
* Confidential (Damage)
* Unclassified

*Mnemonic:* **T**om **S**awyer **C**atches **U**nderwear.

**Commercial (Private)**
* Confidential
* Private
* Sensitive
* Public

## Data remanence

**"Cow, Pig, Sow" (CP SOW)**

* **C**learing -> **C**an be recovered (Overwriting)
* **P**urging -> **P**ermanent (Sanitizing)
* **S**anitizing -> **S**ame as purging
* **O**verwriting -> with **O**h's
* **W**iping -> is **W**riting

**Destruction Order (800-88)**: Clear (overwrite) -> Purge (degauss) -> Destroy (shred).

## Scoping, tailoring and supplementation
* **Scoping** is **Subtracting** (controls)
* **Tailoring** is **Tweaking** (controls)
* **Supplementing** is **Specifying** (names/extras)

## Data States
* At **Rest** (Storage)
* In **Transit** (Network)
* In **Use** (RAM/Processing)

# Domain 3

## Must-know

### Security rings,
(Zero) KODU – Kernel, OS, Drivers, Userspace

### Reference Monitor
* Tamper-proof
* Always invoked
* Small enough to verify

### Information flow security models
Integrity models have I in it, Confidentiality models don't.

#### No-{{Action}}-Arrow models

1. Bell-LaPadula – (**Confidentiality**) Like a BELL 🛎️: No Read Up↑, no Write Down↓.
   * *Mnemonic:* No**R**↑🛎No**W**↓.
   * Uses **Lattice** based access control.

2. B**i**ba – (**I**ntegrity) Opposite of Bell-LaPadula: No Read↓, no Write Up↑.
   * *Mnemonic:* No**R**↓**▽**No**W**↑.

#### Brewer&Nash, Clark-Wilson

3. Brewer&Nash: **Chinese Wall**. Walls off conflict-of-interest.

4. Clark-W**i**lson – (**I**ntegrity) **Clerk** uses **WinStone** software (Transformation Procedures - TPs) to access data.
   * Concepts: Well-formed transactions, Separation of duties.

#### 5. TAKE-GRANT
Take, Grant, Create, Remove.

## Cryptography Basics

### Symmetric (Same key)
* **AES**: Best. 128/192/**256** bit.
* **DES/3DES**: Legacy/Slow.

### Asymmetric (Key pair)
* **RSA**: Factoring large primes.
* **ECC**: Elliptic Curve. **Fastest**, best for mobile/low power.
* **Diffie-Hellman**: Key Exchange only.
* **ElGamal**.

### Hashing (Integrity)
* **SHA-256 / SHA-3**: Good.
* **MD5 / SHA-1**: Bad (Collisions).

### Block Modes (Worst -> Best)
**ECB** > **CBC** > **CFB** > **OFB** > **CTR**
* **ECB**: Electronic Cook Book. Pattern visible. The worst.
* **CTR**: Counter mode. Parallelizable, best performance/security balance.

## Fire Extinguishers

| Type | Application | Mnemonic |
| ---- | ---- | ---- |
| A | **A**sh, almanac, wood, paper | **A** Wood -> Water |
| B | **B**ubble, **B**oil Oil, Liquids | **B** Fuel -> CO2 |
| C | **C**ircuits, Electrical | **C** Wires -> Clean agent |
| D | **D**ent, **D**ural, Metal | **D** Metal -> Dry powder |
| K | **K**itchen | - |

**Clean Agents** (Data Centers): FM-200, Novec 1230, Inergen. (Halon is banned).

## Common Criteria – EAL

**Function > Structure > Method >> Semiformal > Semiformal-verified >> Formal**

* EAL 1: Functionally Tested
* EAL 2: Structurally Tested
* EAL 3: Methodically Tested and Checked
* EAL 4: Methodically **Designed**, Tested, and Reviewed (**Standard for commercial OS**)
* EAL 5: Semiformally Designed and Tested
* EAL 6: Semiformally Verified Design and Tested
* EAL 7: Formally Verified Design and Tested

## Modern OS Defenses
* **ASLR**: Address Space Layout Randomization (Randomizes memory locations).
* **DEP/NX**: Data Execution Prevention (Marks memory non-executable).

# Domain 4

## OSI Model
**Bottom to Top (1->7)**: **P**lease **D**o **N**ot **T**hrow **S**ausage **P**izza **A**way
(Physical, Data Link, Network, Transport, Session, Presentation, Application)

**Top to Bottom (7->1)**: **A**ll **P**eople **S**eem **T**o **N**eed **D**ata **P**rocessing

## Device Layers
* **Hub**: Layer 1 (Repeater, dumb)
* **Switch**: Layer 2 (Bridge, uses MAC)
* **Router**: Layer 3 (IP, separates subnets)
* **Gateway**: Layer 3+ (Protocol translator)

## Authentication protocols

* **Kerberos** – Windows/AD.
    * Flow: **AS** > **TGT** > **TGS** > **Service Ticket**.
    * *Mnemonic:* **KATANA** (KDC Authenticates, TGS Authorizes, Nginx Accepts).
    * **No password sent over wire**.
* **RADIUS** – VPN/ISP. **UDP**. Combines Auth + AuthZ.
* **TACACS+** – Cisco. **TCP**. Separates Auth, AuthZ, Accounting. Encrypts full session.

## Wireless
* **Strongest**: WPA3-Enterprise + 802.1X/EAP.

## IPSec
* **IPSec is 2**: IP + Sec.
* **ESP** (Encapsulating Security Payload): Confidentiality + Integrity + Auth.
    * *Mnemonic:* **E**very **S**ecret **P**rotected.
* **AH** (Authentication Header): Integrity + Auth (No encryption).
    * *Mnemonic:* **A**unt **H**elen only Authenticates.

## Firewalls
**Order of processing:**
Packet filter > Stateful > Proxy > WAF (most secure/deepest inspection)

**Port Status:**
* Open – Worst
* Filtered – OK (Firewall caught it)
* Closed – Best (Service not listening)

## RAID
* **RAID 0**: Striping (Speed, 0 redundancy).
* **RAID 1**: Mirroring (Redundancy).
* **RAID 5**: Striping + Parity (1 disk fail).
* **RAID 6**: Striping + Double Parity (2 disk fail).
* **RAID 10**: Stripe + Mirror (Best performance + redundancy).

# Domain 5

## Biometrics Errors
* **FRR** (False Rejection / Type 1): **Friendly** people **Rejected**.
* **FAR** (False Acceptance / Type 2): **Foe** **Accepted**.
* **CER**: Crossover Error Rate (Intersection). Lower is better.

## Federation / SSO
* **SAML**: XML-based. Enterprise Federation.
* **OIDC** (OpenID Connect): **Authentication** layer on top of OAuth. (Identity).
* **OAuth 2.0**: **Authorization** framework. (Access).

## Access Control Models
* **DAC**: Discretionary (Identity based, Data Owner decides).
* **MAC**: Mandatory (Labels/Clearance, OS decides).
* **RBAC**: Role Based (Job function).
* **ABAC**: Attribute Based (If/Then, Context aware).

# Domain 6

## SOC Reports
* **SOC 1**: **F**inancial Controls.
* **SOC 2**: **T**rust Services (Security, Availability, Integrity, Confidentiality, Privacy).
    * **Type 1**: Point in time.
    * **Type 2**: Period of time (Timeline).
* **SOC 3**: Public summary of SOC 2 ("Lite").

## Threat Modeling: STRIDE (Microsoft)
* **S**poofing
* **T**ampering
* **R**epudiation
* **I**nfo Disclosure
* **D**enial of Service
* **E**levation of Privilege

## Vulnerability Assessment vs Pen Test
* **Scan**: Automated, finds weaknesses.
* **Pen Test**: Manual, exploits weaknesses, verifies them.

## OWASP Top 1 (2023)
* **Broken Access Control** is usually #1.

# Domain 7

## Incident Response Steps

**NIST 800-61**:
Preparation > Detection/Analysis > Containment/Eradication/Recovery > Post-Incident

**Exam Mnemonic: DRMRRRL**
* **D**etection
* **R**esponse
* **M**itigation
* **R**eporting
* **R**ecovery
* **R**emediation
* **L**essons Learned

## Evidence
* **Chain of Custody**: Document every person who handled evidence.

### Order of Volatility (RFC 3227)
**Most Volatile -> Least Volatile**
1. CPU Cache / Registers
2. **RAM** (Routing tables, ARP cache, Process table, Kernel stats)
3. Swap / Paging file / Temporary File Systems
4. Disk (Data on HDD/SSD)
5. Remote Logs / Archival media

## Backups
* **Full**: Slowest backup, fastest restore.
* **Incremental**: Fastest backup, slowest restore. (Resets archive bit).
* **Differential**: Cumulative changes since last full. (Does NOT reset archive bit).

## Patch Management
Test > Approve > Deploy > Verify.

# Domain 8

## SDLC
**Waterfall**: Sequential, rigid docs.
**Agile**: Iterative, flexible changes.

**Mnemonic**: Please Fry Some Dead Animals To Catch The Right Man
(Plan, Functional reqs, System design, Dev, Acceptance, Test, Cloud/Release, Maintenance?)
*Alternative:* **Ur DC PC SR** (User Requests, Developer Changes, Policy Configures, Software Releases).

## Databases
* **Polyinstantiation**: Multiple rows with same key but different classification (used in MLS databases to prevent inference).
* **ACID**: Atomicity, Consistency, Isolation, Durability.

## Maturity Models (SW-CMM)
**IRDMO** (THIRDMOON)
1. **I**nitial (Chaotic)
2. **R**epeatable (Managed)
3. **D**efined (Standardized)
4. **M**anaged (Quantitatively Managed)
5. **O**ptimized (Continuous Improvement)

# Domain 9 (Meta & General)

## ISC2 Code of Ethics (PAPA)
*Strict Order:*
1. **P**rotect society, the common good, necessary public trust and confidence, and the infrastructure.
2. **A**ct honorably, honestly, justly, responsibly, and legally.
3. **P**rovide diligent and competent service to principals.
4. **A**dvance and protect the profession.

## General Exam Tips
* **PDC**: **P**revent > **D**etect > **C**orrect. (Priority of controls).
* **Physical Safety**: Human life is ALWAYS #1.
* **Manager vs Tech**: Think like a Manager. Fix the process, not just the router.
* **Entice vs Entrap**: Enticement is legal (Honeypot). Entrapment is illegal (Encouraging a crime).

## Why you will pass
Because you studied the **Concepts**, not just the questions. You got this.
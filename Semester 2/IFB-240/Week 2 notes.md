## IFB240 Cyber Security - Lecture 2 (Part A)

### Introduction
- **Information**: A crucial asset for individuals and organizations, stored, transmitted, processed, and displayed in various formats.
- **Information Security**: Protects information assets from damage or harm.
- **Cyber Security**: Protects the confidentiality, integrity, and availability (CIA) of digital systems, devices, and the information they contain.
- **Fundamental Concepts**:
  - **Confidentiality**: Prevent unauthorized disclosure of information.
  - **Integrity**: Prevent unauthorized modification or destruction of information.
  - **Availability**: Ensure resources are accessible when needed by authorized entities.

### Review of Terminology
- **Threat**: Any event with the potential to harm an asset by compromising security goals.
- **Vulnerability**: A weakness in a system that could lead to harm if acted upon by a threat.
- **Security Incident**: When threats and vulnerabilities coincide; if deliberate, it’s called an **attack**.

### Threats - Terminology
- **Threat Actor**: An entity whose actions impact or could impact information security (also known as a malicious actor).
- **Threat Action**: Actions intended to cause harm to information assets. Categories include:
  - Error
  - Environmental
  - Hacking
  - Malware
  - Misuse
  - Physical
  - Social

### Types of Threat Actors
- **External**:
  - **Cyber Criminals**: Motivated by money.
  - **Hacktivists**: Driven by ideology or a cause.
  - **Nation-State Attackers**: Political motives.
  - **Script Kiddies**: Thrill-seeking or bragging rights.
- **Internal**:
  - **Careless/Negligent Workers**: Unintentionally cause harm due to a lack of awareness.
  - **Malicious Insiders**: Motivated by money or the desire to disrupt.

### Threat Sources
- **External**: Threats originating outside the organization, e.g., unauthorized individuals needing physical or logical access.
- **Internal**: Threats from within the organization, e.g., authorized individuals misusing systems or exceeding their authorization.

### Threat Types
- **Natural Events**:
  - Examples: Earthquake, fire, flood, storm, etc.
  - Potential impact depends on the physical location of information assets.
  - Examples: 
    - Victoria, Australia storms (Feb 2024)
    - Turkiye & Syria earthquake (Feb 2023)
    - Brisbane floods (Feb 2022)
    - Australian bushfires (Dec 2019 - Jan 2020)
  
- **Human Action**:
  - **Accidental**: No intent to cause harm but actions result in potential harm. Examples include:
    - Accidental damage to equipment
    - Change management errors
    - Misdirected messages
  - **Deliberate**: Intentional actions to cause harm. Examples include:
    - Espionage, fraud, sabotage, theft
    - Malware (e.g., viruses, worms, trojans)
  - Example of Accidental Human Action:
    - Telstra cable cut (2018)
    - G20 Summit data breach (2014)
    - Prince William photo shoot (2012)
  - Example of Deliberate Human Action:
    - Apple employee theft of trade secrets
    - Malware compromising CIA through ransomware, keystroke logging, etc.

### Emerging Technologies
- The threat landscape evolves with emerging technologies, altering the nature and scope of threats.

### Summary
- **Threats**: There are many threats to information assets and systems.
- **Protection**: To protect information assets, understand the context:
  - What is the asset?
  - Where is it located, and what state is it in?
  - What are the potential threats?
- **Value**: Assess the value and criticality of the asset, and consider potential consequences if it’s harmed.
# IFB240 Cyber Security - Lecture 2 Part B Notes

## Vulnerabilities

---

### Overview of Vulnerabilities
- **Vulnerability Definition**: Characteristics or weaknesses in a system that, if exploited by a threat, could cause harm to information assets.
- **Components of an Information System**: Vulnerabilities can exist in:
  - Property
  - People
  - Procedures

---

### Vulnerabilities in Property

#### 1. Physical Assets
- **Components**:
  - **Buildings and Contents**
  - **Hardware**: Computer systems, data communication devices, data storage devices.
  - **Software**: Operating systems, applications.
  - **Data**: System and organizational data such as files, databases, and passwords.

- **Aspects to Consider**:
  - **Location**:
    - Vulnerability to natural disasters.
    - Proximity to flammable/corrosive materials or targets for disruption.
    - Accessibility to outsiders.
  - **Physical Security**:
    - Use of fences, walls, locks, gates, and internal partitioning.

- **Example**:
  - **February 2024 Fireworks Factory Explosion in India**: 8 dead, 80 injured.

- **Maintenance**:
  - Ensuring assets are in working condition.
  - Monitoring and logging of physical access using CCTV, intrusion detection systems, fire suppression systems, etc.
  - Dependence on other systems (e.g., telecommunications).

#### 2. ICT Hardware and Software
- **Aspects to Consider**:
  - **Reliability and Robustness**:
    - Susceptibility to environmental conditions (dust, heat, humidity).
    - Supporting infrastructure like power supply, air conditioning.
  - **Redundancy**:
    - Availability of alternative resources (e.g., Uninterruptible Power Supply (UPS)).
    - Equipment fail-states.
  - **Source of Software**:
    - Authorized, legitimate, and vendor-supported software.
    - Risks associated with outdated software (e.g., Windows XP, Windows 7).
    - Processes for software installation to avoid malware.

- **Design and Testing**:
  - Vulnerabilities in software design (e.g., buffer overflows, injections).
  - The importance of timely patching and upgrading software.
  - Dependency and compatibility issues with other systems.

- **Configuration/Misconfiguration**:
  - Appropriate implementation and setup of systems.
  - Security of default settings.

- **Examples**:
  - **2019/2020 Bushfires**: Loss of mobile phone coverage due to powerline destruction.
  - **2022 Floods**: Significant loss of services in flood-hit regions of Queensland and NSW.

---

### Vulnerabilities in People

#### 1. Lack of Awareness of Threats
- **Example**:
  - Vulnerability to social engineering.
  - **ACSC Definition**: Social engineering involves manipulating people to carry out specific actions or divulge information.
  - Lack of awareness increases vulnerability.

#### 2. Internal Organizational Vulnerabilities
- **Recruitment**:
  - Importance of background checks for staff suitability.
  - Monitoring access of employees, clients, and contractors.
  - Risks posed by disgruntled employees or contractors.

- **Training and Awareness**:
  - Inadequate training on threats, policies, and procedures.
  - Examples:
    - Providing information over email or phone.
    - Downloading software.
    - Configuration of products.

- **Examples**:
  - **Recruitment Failure**:
    - Source: Brisbane Business News - January 2012.
  - **Software Download**:
    - Student pirating software led to a Ryuk ransomware attack.

- **Key Personnel**:
  - Vulnerability if key personnel are unavailable or uncooperative.
  - Risk if procedures are undocumented and lack a backup.

- **Security in Contracts**:
  - Importance of including security conditions in contracts with consultants, contractors, and outsourcing.

---

### Vulnerabilities in Processes

#### 1. Access Control and Privilege Management
- **Processes**:
  - Management of keys, ID cards, passwords, etc.

#### 2. Backup Processes
- **Considerations**:
  - Who is responsible for backups?
  - Frequency and method of backups.
  - Storage and encryption of backups.

#### 3. Business Continuity Plans
- **Importance**:
  - Having a recovery plan for information assets post-disaster.
  - Ensuring the plan is known, rehearsed, and drilled.

#### 4. Communication Processes
- **Acceptable Use Policy**:
  - Guidelines for communication systems, message confirmation, and secure transmission.
  - Examples:
    - Should passwords be emailed?
    - Is it safe to log in using HTTP?

- **Examples**:
  - **Zoom Invite Phishing**: Fake Zoom invites leading to financial losses (NZ Herald, November 2020).

#### 5. Checks and Balances
- **Error Detection**:
  - Processes to detect and correct errors.
  - **Example**:
    - **Separation of Duties**.
  - **Staff Management**:
    - Processes for staff onboarding and offboarding.
    - Use of nondisclosure and confidentiality agreements.

- **Software Management**:
  - Auditing and application whitelisting.

- **Example**:
  - **Dividend Payment Error**: Samsung employee mistakenly issued a dividend equal to the value of 1000 shares per share instead of 1000 won per share.

---

### Summary
- **Protecting Information Assets**:
  - Understand the asset, its location, and value.
  - Identify possible threats and existing vulnerabilities.
  - Assess the likelihood and consequences of threats and vulnerabilities coinciding.

---

# Security Incidents and Attacks

## Overview
- **Security Incident**: Occurs when threats and vulnerabilities coincide, potentially harming information assets.
- **Attack**: A security incident involving deliberate human action.
- **Attacker**: A person who deliberately exploits a vulnerability to gain unauthorised access or perform unauthorised actions.

## Examples
- **August 2020 Data Breach Tasmania**: Data breach at University of Tasmania affected 20,000 students.

## Chain of Events in an Incident
1. **Personal Information Exposed**
   - **Vulnerability**: Misconfigured database containing personal information.
   - **Threat**: Unauthorized disclosure of personal information.
   - **Attack**: Unauthorized access and copying of information.
2. **Phishing the Students**
   - **Vulnerability**: Susceptibility to email phishing.
   - **Threat**: Malware installation via phishing email.
   - **Attack**: Opening a malicious email attachment.
3. **Malware Extracts Information**
   - **Vulnerability**: Inadequate antivirus protection.
   - **Threat**: Key logging malware captures credentials.
   - **Attack**: Recording and transmitting keyboard input.
4. **Stealing Money from Student Bank Accounts**
   - **Vulnerability**: Single authentication factor.
   - **Threat**: Unauthorized access to bank accounts.
   - **Attack**: Using stolen credentials to transfer funds.

## Types of Attacks

### Passive Attacks
- **Eavesdropping**
  - **Description**: Listening to conversations without consent.
  - **Examples**: Wiretapping, traffic analysis.
- **Shoulder Surfing**
  - **Description**: Observing confidential information entry.
  - **Examples**: PINs, passwords.
- **Network Monitoring and Eavesdropping**
  - **Description**: Monitoring network traffic.
  - **Examples**: Packet sniffers.

### Active Attacks
- **Denial of Service (DoS) Attack**
  - **Objective**: Make a resource unavailable to users.
  - **Methods**: Damage, interrupt communications, overload with requests.
  - **Examples**: Mirai malware attack on Deutsche Telekom.
- **Distributed Denial of Service (DDoS) Attack**
  - **Objective**: Similar to DoS, but uses multiple sources.
  - **Description**: Uses botnets to overload resources.
  - **Examples**: DDoS attack on German airports in February 2023.
- **Masquerade/Spoofing**
  - **Description**: Pretending to be another entity.
  - **Examples**: Caller ID spoofing, email spoofing, webpage spoofing.
- **Social Engineering**
  - **Description**: Manipulating individuals to gain information.
  - **Examples**: Impersonation, tailgating.
- **Phishing**
  - **Description**: Combining spoofing and social engineering to gain credentials.
  - **Examples**: Emails pretending to be from legitimate organizations.
- **Man-in-the-Middle (MITM) Attack**
  - **Description**: Attacker intercepts and manipulates communication.
  - **Examples**: Spoofing both communication endpoints.
- **Replay Attack**
  - **Description**: Capturing and retransmitting data to gain unauthorized access.
  - **Examples**: Replaying encrypted passwords.

## Case Study: Ransomware
- **Threat**: Restriction of access or publication of data upon payment.
- **Examples**: Cryptolocker, Locky, WannaCry.
- **Vulnerability**: Human error, processes.
- **Attack**: Active or passive, depending on interactions.
- **Example**: REvil ransomware attack on UnitingCare Queensland affecting hospitals and aged care centers.

## Summary
- Security incidents result from the intersection of threats and vulnerabilities.
- Types of attacks vary in method and impact.
- The severity of impact depends on the asset's value and criticality.
- Incidents can occur in isolation or as part of a chain of events.

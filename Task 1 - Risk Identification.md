# APT34 (OilRig/HelixKitten)

## APT34 history
APT34, also known as OilRig or HelixKitten, is a state-sponsored cyber espionage group that has been active since 2014. The group is believed to be associated with the Iranian government and primarily targets sectors across the Middle East.

## Nation/State Association
APT34 is strongly suspected to work on behalf of the Iranian government. Evidence supporting this includes 
- Infrastructure details that contain references to Iran
- Use of Iranian infrastructure
- Targeting patterns that aligns with Iran’s geopolitical and intelligence priorities

## Target Industries
APT34 targets a variety of sectors, including:
- Finance
- Government
- Energy

While their primary focus is the Persian Gulf region in the Middle Eat, APT34 has also conducted operations affecting organizations in the United States, United Kingdom, and Asia.

## Motives
APT34 conducts cyber espionage that aligns with Iran’s geopolitical interests. Their espionage usually includes 
- Gathering intelligence
- Undermining adversaries
- Disrupting infrastructure.

## TTPs
APT34 uses a variety of techniques, including 
- [Spear Phishing Attachment (T1566.001)](https://attack.mitre.org/techniques/T1566/001/) - Sends spearphising emails with malicious attachments using compromised and/or spoofed email accounts
- [Application Layer Protocol (T1071)](https://attack.mitre.org/techniques/T1071/) - Used HTTP and DNS for command and control (C2) communication 
- [Command and Scripting Interpreter (T1059)](https://attack.mitre.org/techniques/T1059/) - Used various types of scripting for execution.

Common attack types include malware, spear phishing, credential harvesting, and supply chain attacks.

## Defensive Security Measures
The following are some security measures to defend against cyberattacks conducted by APT34:
1. **User Account and Access Control**
    - Implement strong account management to control account creation, modification, and permissions
    - Reset or disable accounts associated with known or suspected breaches.
    - Enforce Multi-Factor Authentication (MFA)
    - Enforce the Principle of Least Privilege (PoLP)

2. **Network Hardening and Monitoring**
    - Reinforce network firewalls to filter ingress/egress traffic
    - Update signatures in Network Intrusion Prevention Systems (NIPS) to detect adversary activity
    - Segment the network into smaller, isolated zones to limit lateral movement
    - Disable unnecessary ports and services

3. **Employee Training**
    - Provide regular cybersecurity awareness training focused on phishing and social engineering

4. **Incident Response**
    - Maintain and regularly update the incident response plan (IRP)
    - Conduct periodic tabletop exercises to evaluate readiness and improve response procedures.

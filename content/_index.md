## Education
March 2022 - August 2023

: **Cybersecurity Diploma**; UCI
An intensive 24-week Cybersecurity Bootcamp with a multidisciplinary approach to information security
* Deepened understanding of information security principles and compliance frameworks, with a focus on NIST SP 800-53
* Enhanced abilities in identifying and exploiting vulnerabilities. Acquired expertise in employing Ansible to configure Docker containers
* Developed foundational skills in computer forensics using Autopsy. Gained exposure to essential Bash scripting and an introductory understanding of Splunk, broadening my skills in system management and data analysis

March 2021 - October 2021
: **OSED EXP-301**; Offensive Security
* Acquired proficiency in creating Python-based exploit scripts against susceptible binary targets, showcasing capabilities in penetration testing. 
* Developed techniques to bypass Windows' binary exploit mitigations, demonstrating advanced understanding of security systems. 
* Gained an in-depth comprehension of program memory layout, cementing a foundation for successful exploit development

## Projects
**Malware Analysis: Stealc**
Conducted in-depth analysis of the new and actively promoted Stealer malware known as "Stealc," which is being widely advertised in cybercrime forums.
* Utilized dnSpy to extract and examine the raw bytes of the Stealc binary from the .NET dropper, gaining access to the core components of the malware for further investigation. 
* Employed Ghidra's advanced capabilities to successfully neutralize the antidisassembly techniques employed by the malware's author. 
* Leveraged Cyberchef to decode base64 strings used by the malware to dynamically load libraries, providing valuable insights into the functionality and potential impacts of the loaded libraries. 
* Thoroughly analyzed C2 communication of Stealc using Wireshark, offering information on the nature and extent of the communication, enabling a better understanding of the malware's command structure and potential implications for infected systems.

**Fuzzing NFTables**
Utilized the AFL++ binary fuzzing platform to uncover a stack overflow vulnerability in the table data handling of nftables 1.0.4. This vulnerability was promptly triaged, reported, and subsequently patched in the subsequent version 1.0.5.
* Employed GDB+Gef to meticulously debug the application core dump, enabling a thorough analysis of the crash and efficient triaging of the bug to create a comprehensive report. 
* Compiled the binary with AFL++ and LibSanitizer, leveraging these tools to conduct effective fuzzing and generate clear crash output for in-depth analysis. 
* Prepared a detailed report on the identified vulnerability and promptly submitted it to Netfilter Bugzilla, ensuring proper documentation and communication of the bug to the delevoper.

Programming Languages

: **Perl** : Utilized Perl to develop software that aided in efficient malware categorization. Gained a strong understanding of regex for string matching and manipulation. 

: **C** : Developed binary analysis tooling, network and eBPF programs. Deep understanding of the language, able to conduct in-depth source code review.

: **Python** : Used with libraries like pwntools to develop exploits for vulnerabilities found in software and to also aid in the solving of CTF challenges.  

**Skills**
: **Reverse Engineering** : gdb w/ gef, ghidra, x64dbg, 010, CFF, pe-bear, dnspy
: **Intel** : MISP, Cortex w/ Hive, Maltego, Spiderfoot
: **Forensics** : Wireshark, Volatility

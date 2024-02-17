# Email Recon Tool - Educational Malware

![plot](https://github.com/TrojanNinja/FHPCKER/blob/main/Banner.jpg)

## Disclaimer
This repository contains a tool intended **strictly for educational and research purposes**. It's a demonstration of the mechanics behind certain types of malware, specifically targeting Linux boot files. The use of this tool is at your own risk, and should only be in environments that are safe, legal, and ethical. The author(s) of this tool disclaim any responsibility for misuse, damages, or legal consequences resulting from its use.

## Warning
**This tool is potentially harmful.** It simulates an email reconnaissance tool but carries a malicious payload that removes certain Linux boot files upon execution, leading to system restart and potential unbootability. It's designed to illustrate the risks of executing untrusted software and the importance of cybersecurity.

## Usage Guidelines
1. **Environment**: Use this tool only in a controlled, isolated LINUX environment, such as a virtual machine, without sensitive or personal data. **Do not use on any production or personal systems.**
2. **Execution**: Upon running, the tool prompts for an email address as part of its simulated functionality.
3. **Malicious Payload**: After email input, it modifies Linux boot files and initiates a system restart, demonstrating the payload's impact.
4. **Recovery**: Post-execution, the system may experience boot issues. This tool is for those who understand the risks and are prepared to manage them.

## Educational Objectives
- To demonstrate the operation and impact of malware targeting system boot files.
- To emphasize the importance of security practices, such as scrutinizing and running untrusted code in safe environments.
- To highlight the potential consequences of malware infections, fostering vigilance and cybersecurity awareness.

## Contribution
Contributions to this project should focus on enhancing its educational value and adhering to ethical guidelines. Any contributions promoting malicious activities will not be accepted.

##Note
Create Snapshot of Linux before running this tool.

## How to run?
1. sudo git clone https://github.com/TrojanNinja/FHPCKER
2. sudo chmod +x Email_Recon
3. sudo ./Email_Recon



## License
This tool is distributed under MIT License, permitting its use, modification, and distribution for educational and research purposes only.



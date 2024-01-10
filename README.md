# Linkedin
[![](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gauravss03/)
# Portfolio 
[![](https://img.shields.io/badge/Portfolio-255E63?style=for-the-badge&logo=About.me&logoColor=white)](https://gauravsuryawanshi.pages.dev/)
# Medium Page 
[![](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@gauravss3703/security-operation-center-lab-a18eeba5c3c2)


# Azure SIEM + Honeypot


![Untitled (1)](https://github.com/astroxhacker/siem-honeypot/assets/109857735/92628675-b613-4172-8015-2fbbe08c031c)


# Introduction:
  Explore the intricacies of cybersecurity with our project that revolves around building a mini honeynet in Microsoft Azure. This endeavor involves integrating various log sources into a dedicated Log Analytics workspace, where Microsoft Sentinel utilizes these logs to craft attack maps, trigger alerts, and generate incidents. Delve into the realm of live cyberattacks, incident response, and a deep understanding of attackers' tactics, techniques, and procedures.

![1_XQ-wmvoqiz1Yg-RFpxwb_A](https://github.com/astroxhacker/siem-honeypot/assets/109857735/7cdac129-8bdd-42c3-ab44-93ef84e61d44)


# For detailed Steps, visit the Medium Page [Here](https://google.com) 

# Objective:
1. Analysis and Study:
     * Analyze live cyberattacks in the honeypot
     * Conduct incident response and investigate event alerts
     * Study attackers to comprehead their intentions and methodologies
  
2. Transformation:
     * Transform the insecure environment into a secure one
     * Implement security controls such as firewall reconfiguration, Next-Generation Security, Azure Private Links, and compliance with NIST 800-53 and Microsoft Defender recommendations.

# Methodology:
1. Establishing the Honeypot:
   * Begin by disabling the firewall within the VM to create an initially insecure environment.
   * Allow all ports and traffic to be received by the Network Security Group (NSG).
2. Tracking and Examination:
   * Configure the Azure infrastrucutre to ingest log sources from diverse resources into a dedicated log analysis workspace.
   * Utilize Microsoft Sentinel to construct advanced attack maps, trigger alerts and generate incidents.
3. Tracking and Evaluating Security Metrics:
   * Monitor the unsecured environment for a 24-hour period to gather baseline security measurements.
   * Use this data for comparison and assessment.
4. Addressing and Resolving Security Incidents:
   * Resolve identified incidents and vulnerabilities through a comprehensive incident response.
   * Fortify the environment by implementing security best practices, Azure-specific recommendations, and regulatory compliance.
5. Analysis After Implementing Remediation Measures:
   * Reobserve the environment for another 24-hour period and evaluate security metrics post-implementation of remediation measures.
   * Compare the new data with the initial baseline to measure the impact of security controls.
6. Architecture Before Implementing Security Controls:
   * Analyze the architecture where all resources were exposed to the internet, with open network security groups and permissive built-in firewalls.
   * Identify vulnerabilities in this initially insecure setup.
7. Architecture After Implementing Security Controls:
   * Fortify network security groups to block all traffic except for that from the administrative workstation.
   * Strengthen resources using built-in firewalls and private endpoints.
   * Implement security controls such as firewall reconfiguration, Next-Generation Security, and Azure Private Links.
8. Attack Maps Before Hardening / Security Controls:
   * Explore visual representations of attack attempts on a publicly accessible Microsoft SQL server and Linux virtual machine.
   * Understand the intensity and origin of attacks through color-coded maps.
9. Metrics Before Hardening / Security Controls:
   * Collect comprehensive metrics during the initial 24-hour period to establish a baseline for security events.

# Resources Used:
  Explore the integration of various Azure resources, technologies, and regulations including Azure Key Vault, Storage Account, Log Analytics Workspace, Network Security Group (NSG), Microsoft Sentinel, Microsoft Defender, PowerShell, Virtual Machines, Virtual Network, and compliance with NIST SP 800–53.

# Conclusion:
  In the journey from an insecure environment to a secure one, this project meticulously measured security metrics before and after implementing security controls. Witness a significant decrease in the frequency of security events and incidents after fortifying the infrastructure, demonstrating the effectiveness of the applied security measures. The project contributes valuable insights into cybersecurity, incident response, and the continual quest for a resilient and secure network environment.

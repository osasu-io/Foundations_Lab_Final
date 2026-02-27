# Foundations Lab Final

**Osasu Imariagbe*  
Course: Cybersecurity
Instructor: George Robbins 
Institution: The Knowledge House
Date: February 26, 2026  

# Security Philosophy

My lab environment utilizes a Type 2 hypervisor to create an isolated virtual machine (VM) that functions independently of the host operating system. This virtualization architecture is fundamental to maintaining the CIA Triad (Confidentiality, Integrity, and Availability) by establishing a logical boundary between the host hardware and the guest environment.

## Confidentiality

Virtualization ensures confidentiality by restricting the guest VM’s access to the host's memory, files, and network traffic. By isolating the lab environment, I ensure that testing activities remain contained within the virtual instance, preventing sensitive host data from being exposed or accessed by processes running within the VM.

## Integrity

The lab setup supports integrity by preventing unauthorized or accidental modifications to the host system. When executing verification scripts or testing software, the changes are restricted to the virtual disk. If a process compromises the system state, it does not affect the host OS, thereby maintaining the integrity of the primary workstation.

## Availability

Virtualization enhances availability through the use of snapshots and rapid recovery. If the virtual environment becomes unstable due to configuration errors or malware testing, the system can be reverted to a known good state instantly without impacting the availability of the host computer, ensuring consistent access to resources.

---

# References

National Institute of Standards and Technology. (n.d.). *Computer Security Resource Center Glossary*. https://csrc.nist.gov/glossary  

Rouse, M. (2022). *What is virtualization?* TechTarget. https://www.techtarget.com/searchdatacent/definition/virtualization

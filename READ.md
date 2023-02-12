# The best computer forensics tools


# Digital evidence can exist on a number of different platforms and in many different forms. Forensic investigation often includes analysis of files, emails, network activity and other potential artifacts and sources of clues to the scope, impact and attribution of an incident.

Due to the wide variety of potential data sources, digital forensics tools often have different specialties. This list outlines some of the most common and widely used tools for accomplishing different parts of a computer forensics investigation.

# Disk analysis: Autopsy/the Sleuth Kit
Autopsy and the Sleuth Kit are likely the most well-known forensics toolkits in existence. The Sleuth Kit is a command-line tool that performs forensic analysis of forensic images of hard drives and smartphones. Autopsy is a GUI-based system that uses The Sleuth Kit behind the scenes. 

The tools are designed with a modular and plug-in architecture that makes it possible for users to easily incorporate additional functionality. Both tools are free and open-source, but commercial support and training are available as well.


# Image creation: FTK imager
Autopsy and The Sleuth Kit are designed to examine disk images of hard drives, smart phones and so on. The benefit of analyzing an image (rather than a live drive) is that the use of an image allows the investigator to prove that they have not made any modifications to the drive that could affect the forensic results.

Autopsy does not have image creation functionality, so another tool needs to be used. While the majority of the AccessData Forensics Toolkit items are paid tools, its FTK Imager is a free product. This can be used to create disk images that can then be analyzed using Autopsy/The Sleuth Kit.


# Memory forensics: volatility
Tools like The Sleuth Kit focus on the hard drive, but this is not the only place where forensic data and artifacts can be stored on a machine. Important forensic information can be stored in RAM, and this volatile memory must be collected quickly and carefully to be forensically valid and useful.

Volatility is the most well-known and popular tool for analysis of volatile memory. Like The Sleuth Kit, Volatility is free, open-source and supports third-party plugins. In fact, the Volatility Foundation holds an annual contest for users to develop the most useful and innovative extension to the framework.


# Windows registry analysis: Registry recon
The windows registry acts as a database of configuration information for the Windows OS and the applications running on it. These applications can store a variety of different data in the registry, and the registry is one of the common locations where malware deploys persistence mechanisms.

It is possible to open and view the Windows registry via the built-in Windows application regedit, and registry analysis is built into some forensics platforms. However, specialized tools like Registry Recon are available as well. Registry Recon is a commercial tool that is designed to rebuild Windows registries from a forensic image and includes the ability to rebuild deleted parts of the registry based upon analysis of unallocated memory space.


# Mobile forensics: Cellebrite UFED
Mobile adoption is constantly growing, and many organizations allow employees to use these devices at work either via BYOD programs or corporate-owned devices. Additionally, these devices are a growing target of cyberattacks, such as phishing, making them a likely source of valuable forensic information.

With the growing importance of mobile forensics, a mobile-focused forensics tool might be a useful acquisition. Cellebrite UFED is widely regarded as the best commercial tool for mobile forensics. It supports a number of different platforms (not just mobile devices) and boasts exclusive methods and tools for mobile device analysis.


# Network analysis: Wireshark
Many forensics tools focus on the endpoint, but this is not the only source of useful data in a forensics investigation. Most cyberattacks occur over the network, and analysis of network traffic captures can help with the identification of malware and provide access to data that may have already been deleted and overwritten on the endpoint.

For network traffic analysis, Wireshark is the most popular and widely-used tool. Wireshark is free and open-source, offers dissectors for many different types of network traffic, has a clear and easy-to-use GUI for traffic analysis and includes a wide range of functionality under the hood. It supports live traffic capture or can ingest network capture files for analysis.


# Linux distributions: CAINE
Many of the tools presented here (and many other digital forensics tools besides them) are free and open-source. While this makes them easy to acquire, installation and configuration can be complex. To simplify this process, a number of different Linux digital forensics distributions are available as virtual machines. These VMs include a number of tools pre-installed and preconfigured.

The Computer Aided Investigative Environment (CAINE) is one example of such a tool. This Linux distribution includes many of the most widely used computer forensics tools and may include third-party plugins for tools like Autopsy.

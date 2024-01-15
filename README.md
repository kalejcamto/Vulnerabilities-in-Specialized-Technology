# Vulnerabilities-in-Specialized-Technology
In the modern era, it is common to use specialized technologies that are designed for specific purposes. These technologies include the Internet of Things (IoT), mobile devices, embedded systems, and supervisory control and data acquisition (SCADA). Each of these technologies serves a distinct purpose and is tailored to meet specific needs.

After completing this exercise, you will have further knowledge of:

  Mobile Technology
  Internet of Things
  Embedded Systems
  Real-Time Operating Systems
  System-on-Chip
  Physical Access Control
  Building Automation Systems
  Autonomous Vehicles
  Drones
  Supervisory Control and Data Acquisition (SCADA)

Here the explanation: 

## Mobile
The Open Web Application Security Project (OWASP) performs extensive research and has released to the Top 10 Mobile Threats in 2016.

Here is the list of Top 10 Mobile Threats:

### 1. Improper Platform Usage
Certain features may be built on mobile apps that are meant only for the developers. However, if the hacker knows these features, the entire mobile app is at risk of exploitation.

### 2. Insecure Data Storage
Sometimes, developers do not efficiently handle data in storage. For example, a hacker may be able to extract data from a cache if it is not cleared or encrypted.

### 3. Insecure Communication
Insecure communication relates to several vulnerabilities, such as:

poor handshaking / weak negotiation - A handshake between the client and the server using a weak protocol, such as SSL instead of TLS, which has replaced SSL.
Incorrect SSL version usage - Using an older version of SSL, such as version 1.1, which has security weaknesses.
Certificate issue - Use of expired certificates.
Cleartext communication of sensitive information - use of HTTP protocol instead of HTTPS when exchanging sensitive information. The HTTP protocol sends information in clear text that can be intercepted and read by hackers. HTTPS sends information in an encrypted format.
Even though developers may be cautious about encrypting data at reset, they can forget to encrypt the data in transit. This means that data is being sent in cleartext, which can be captured, read, or modified by a hacker.

### 4. Insecure Authentication
Most mobile apps use offline authentication, which does not require the user to authenticate with an online server. A hacker can use a custom tool to bypass the local authentication method to gain access to the data stored in the app. Insecure authentication also includes improper session management. The sessions, if not closed properly, can allow the hacker to gain access to the mobile app and its data.

### 5. Insufficient Cryptography
If a developer does not implement sufficient or proper cryptography, which is a method to conceal information in a format that no one other than the intended party can understand, the hacker can decrypt the insufficient cryptography to gain access to data. This problem can arise due to poor cryptography or flawed encryption/decryption procedures implemented in the mobile app code.

### 6. Insecure Authorization
Insecure authorization refers to the server-side vulnerabilities during authorization. If permissions are not checked properly when a user accesses a feature, it can also allow the hacker access to exploit features.

### 7. Client Code Quality
Client code quality refers to mistakes made by developers in the mobile app code. The two most common errors to client code are buffer overflow and memory leaks. In buffer overflows, a program attempts to write more data to the buffer than it can handle. In memory leaks, an application does not release the memory that it had consumed but is now no longer required. These can allow the hacker to gain control over the mobile app. This can lead to data theft and control over mobile devices.

### 8. Code Tempering
After a mobile app is downloaded to a device, its code is resident on the mobile. A hacker can perform code tempering, which is modifying the code, stealing information, change the Application Programming Interface (API), which allows two applications to connect or access premium features of the mobile app, which otherwise would be locked. In the worst-case scenario, a piece of malicious code could be added to the mobile app’s code. The modified mobile app could then be distributed through genuine mobile app stores.

### 9. Reverse Engineering
Mobile apps can be reverse engineered. A hacker may reverse engineer a mobile app to study its functionality and find vulnerabilities that may exist in the code. For example, if the developer has included user credentials as a backdoor, then the hacker can use it for data theft. Backdoor malware is used to create an entry in a fully functional system. Typically, developers leave hardcoded credentials within an application to later connect with it in case there is an issue in connecting with the application. Similarly, if the hacker discovers a backdoor, it allows the attacker to remotely control the user’s system without his or her knowledge. The attacker has the full control of the system.

### 10. Extraneous Functionality
During the development of a mobile app, the developers often include features that can help them during testing. However, these features are not always removed when the app is released to production, but they are hidden from the users. When looking for extraneous functionality, the hacker does not interact with the user’s mobile device or its apps. The app is downloaded locally to his or her mobile device by the hacker and then analyzed for the extraneous functionality. Once any type of extraneous functionality is found, it is then used to exploit the user devices.

There are various types of mobile malware, such as:

Spyware - When invoked in a user’s system, spyware sits quietly without alerting the user and gathers information without their consent. The attacker controlling the spyware captures the information by logging the keystrokes generated by the user.
Madware - It is a form of aggressive advertising on Android mobiles and tablets. It is intrusive and can download spyware on the device. The spyware can steal the user’s sensitive information.
Virus - A virus is a type of malware that either inserts or attaches itself to a legitimate program and infects it. A virus is designed to cause damage to a system. For example, it can corrupt installed applications.
Trojan Horse - Trojan horse is a malware that masquerades itself as a legitimate application to hide its real function, which is to steal information from a computer system. The user cannot tell the difference between a trojan or a normal application. When the user triggers the trojan application, it causes damage to the data and the system.
Browser exploits - It is a type of malicious code that alters the Web browser’s security settings. Its main intent is to exploit the vulnerabilities that may exist within the operating system or any installed application.
Methods
Drive-by-downloads - Is a method using malicious code that is downloaded to mobile devices or a system. When a user visits an infected Website, a small piece of code, which is inserted by the hacker, is executed. This piece of code connects to another system and downloads the remaining code on your system. Using the downloaded code, the hacker can connect to your system remotely.

Phishing - Phishing itself is not malware, but instead a method that is used to deliver malware to a user’s system. In phishing, an E-mail carries a malicious file to the user’s mailbox. When the user opens or executes the malicious file, it triggers the malware on the user’s system.

There can be different distribution methods, such as:

 * Email
 * Instant Messaging
 * Bluetooth
 * Memory cards
 * Wi‐Fi

A common method used to spread malware is by infecting an app, which is stored in Play Store or any other trusted app repository. When the users download and install this app, their mobile devices are infected.

When a mobile device is infected with malware, it can:

Monitor the mobile device and activities performed
Capture any kind of messaging, such as Email and text messages, being sent or received
Record conversations in silent mode when the phone is not being used
Cause disruptions to the mobile device operating system and installed apps
Delete data, such as contacts
Mobile Application Vulnerabilities
Some of the key issues with mobile applications are:

Data Storage Formats: When a mobile app is developed, developers do not tend to encrypt data stored within the app. Instead, the data is stored in a clear text or XML format. If someone gains access to the mobile device, the data can be easily read and extracted.

Malware: This is more of an issue with Android-specific apps. Apple uses stringent practices to verify an app before it is submitted to their repository. Android, on the other hand, uses a Play Store, which allows anyone to submit an app. Unless you have an antimalware installed on your mobile device, you cannot be sure that you are downloading a safe app from the Play Store.

Unauthorized Access: Users often do not put a lock or password on their mobile devices. In case that a device is stolen or lost, it can lead to unauthorized access to sensitive information. Another example can be of malware, which can access sensitive information stored on mobile devices.

Lack of Encryption: Several apps use the synchronization feature to upload user data to their servers. However, if data is not encrypted during transmission, it is prone to unauthorized access.

Threats to Bluetooth Devices
Bluetooth is an open standard wireless technology that is used to exchange information and files between two devices. Bluetooth works only with short‐range radio frequencies. When two devices connect using a Bluetooth connection, they create a Wireless Personal Area Network (WPAN).

Some threats to Bluetooth devices are:

Bluejacking - Sends an unsolicited message to another device that has its Bluetooth connection open.
Bluesniping - Uses a directional antenna to establish connections with Bluetooth‐enabled devices. Bluetooth has a distance limitation, which may prevent a hacker from establishing a connection. In this situation, the hacker can use a directional antenna to establish connections for up to a mile (1.6 kilometers).
Bluesnarfing - Uses the Bluejacking method to connect to the device, then gain access to the address book, contact information, email, and text messages.
War Nibbling/Bluecasing - A hacker tries to find unsecured or unpatched Bluetooth connections, then steal information. War Nibbling is similar to War Diving, which is performed on a wireless network.
Internet of Things (IoT)
An IoT device is hardware that can communicate with other devices and send data over the Internet. Each IoT device has an IP address that can be used for communication with other IoT devices, as well as remote monitoring and controlling. At present, IoT devices are being used across various industries, such as consumer electronics, travel, energy, healthcare, agriculture, and security.

Even though the use of IoT devices has increased over the last few years, there are some vulnerabilities that put devices at risk. Just like mobile vulnerabilities, OWASP has also released the top 10 vulnerabilities for IoT. These vulnerabilities are as follows:

1. Weak, Guessable, or Hardcoded Passwords
IoT devices can have hardcoded passwords, or use default passwords are either weak or guessable. Hardcoded passwords can be defined for backdoor entry into IoT devices. However, these passwords can be brute forced. In some cases, the default password cannot be changed.

2. Insecure Network Services
IoT devices use insecure network services that are exposed to the Internet. The insecure network services can compromise the integrity, confidentiality, availability, and privacy of the information being exchanged.

3. Insecure Ecosystem Interfaces
Insecure interfaces, such as Application Programming Interfaces (APIs), can lead to the compromise of the information, where integrity, confidentiality, availability, and privacy, can be lost for the information. The APIs or interfaces do not use secure encryption methods or authentication.

4. Lack of Secure Update Mechanism
With the IoT devices, there is an issue in a secure update of the device’s firmware. There is no validation being performed on the firmware, and also there is no method to rollback to the previous firmware.

5. Use of Insecure or Outdated Components
The IoT devices also suffer from the components that are either insecure or outdated, which can include the operating system and software that is running. Insecure or outdated software or operating systems are bound to have vulnerabilities and, therefore, can be exploited.

6. Insecure Privacy Protection
A user’s personal or collected information can be compromised if the device is hacked. The information is stored in an insecure fashion or exchanged with other devices without user permission.

7. Insecure Data Transfer and Storage
Data is not encrypted when it is in storage or transmission.

8. Lack of Device Management
There is no proper device management. There is no asset management or secure method of commissioning or decommissioning of devices.

9. Insecure Default Settings
Most IoT devices are shipped with insecure default settings. It could also be possible that there are no possible methods to change a default configuration. Users, in most cases, use the IoT devices with the default configuration.

10. Lack of Physical Hardening
Unlike a system or a laptop, there is hardly any physical hardening of IoT devices, which allows them to be controlled remotely by an attacker. This could lead to the compromise of sensitive information.

Embedded Systems
Embedded systems are devices that can perform certain functions on their own with the help of a central processing unit (CPU), an operating system, and applications that they run. Some of the key examples of an embedded system are:

Automatic Teller Machine (ATM)
Printers
Thermostats
Digital watches
Digital cameras
Automobiles
If an embedded system has the capability of connecting to the Internet, then it becomes part of IoT devices. This is quite common nowadays, where an embedded system is an IoT device. If it is, then the same IoT vulnerabilities may apply.

Other than IoT vulnerabilities, an embedded system can also have the following vulnerabilities:

It can be overloaded with more tasks if not secured properly. The overload of tasks may cause scheduling problems
Can be attacked as there is no built-in security
Can be prone to power drain attack in which the battery of a device is drained
Real-Time Operating System (RTOS)
A Real-Time Operating System (RTOS) is designed to work with the real-time applications that require instant results as soon as they make a request. Certain applications cannot use the buffer to store their requests for later and such need instant responses. Such applications are designed to work with the RTOS, which, without buffering the requests, processes the data on an immediate basis. Some of the key examples are:

Air Traffic Control Systems
Networked Multimedia Systems
Command Control Systems
Military systems
Automobiles
Just like any other system, RTOS is also prone to various vulnerabilities. Some key vulnerabilities are:

Remote code execution
Insecure permissions
Privilege escalation
Denial of Service (DoS)
Buffer overflow
Most of these vulnerabilities can cause information leakage within RTOS.

System-on-Chip
A System-on-Chip (SoC), is a platform in which an integrated circuit (IC) integrates various chips to function as a complete system. The entire system is integrated into one single chip that can include various components, such as:

CPU
Input and output ports
Memory
Some of the key examples of SOC are:

Smartphones
Cameras
Tablets
Various vulnerabilities can exist with SOC:

Information leakage
Physical tampering
Side-channel attacks
Reverse engineering
Buffer issues
Physical Access Control
Almost all organizations, small or large, will have some sort of physical access controls deployed. These physical access controls are designed to prevent several misuses of a physical environment.

There can be different types of threats in the physical access control. Some of these threats are namely:

Abuses: this is about forcing the doors to open. It is also the bypassing the access controls or picking the locks
Masquerading: is using someone else’s security card to enter a door that has an access control system implemented.
Piggybacking: is about the following someone without authenticating yourself or showing the security card. The entry is gained with the credentials of someone ahead of you.
Building Automation Systems
The building automation systems are automation methods that help you manage a building’s heating, ventilation, air conditioning (HVAC). The idea is to increase the efficiency in managing HVAC, reduce cost, and also reduce human dependency. There are different components of a building automation system, such as sensors, controllers, output devices, communication protocols, and a terminal interface. It is important to understand that each one of the components is controlled either by firmware or software.

Just like any other software or automation systems, building automation systems are also prone to various vulnerabilities. Most of these vulnerabilities are the same as the other automation or software systems.

Some common vulnerabilities found in building automation systems are:

Buffer overflow
Hardcoded secrets
Device misconfigurations
Cross-site scripting
Path traversal
Arbitrary file deletion
Authentication bypass
Most of these vulnerabilities are pretty common with Web applications. It is not uncommon to have these vulnerabilities in the building automation systems as they can be managed by a Web application or a mobile app, which, if not tested for security, will have these vulnerabilities.

Autonomous Vehicles
An autonomous vehicle is a self-driven vehicle that does not require any human intervention. These are mostly known as driverless vehicles or rather driverless cars. The autonomous vehicles contain millions of lines of code, which is nearly impossible to make it bug-free. It can be estimated that there can be around 300 million lines of code.

More lines of code can indeed lead to the possibility of introducing more bugs and security flaws, which can be exploited by the attackers. Moreover, in some cases, a smartphone app is used to control the autonomous vehicle, which itself can lead to several security flaws. For example, even if the code for the autonomous car is functional and bug-free, the attackers may exploit a vulnerability in the smartphone app that is controlling it.

There can be various types of attacks that can be done on autonomous vehicles if there are bugs and vulnerabilities. Various components can be exploited, such as:

Global Positioning System (GPS)
External Networks, such as V2X Network
Attacks that can exploit various vulnerabilities are:

Onboard diagnostics attack
Engine Control Unit (ECU) Firmware tampering attack
Rogue Updates
Physical access to the ECU
Remote access
Drones
A drone is a blanket term for an un-crewed aerial vehicle or UAV. It is a small aerial vehicle that is used for various purposes, such as surveillance. It can fly with a controlled flight plan and is controlled through sensors and GPS.

A drone works with two different signals: rising and downlink signals. The rising signals are received by the drone. The rising signals can be in the form of radio command or GPS signals. However, these can be replaced by the lure signals that are sent by an attacker. The lure signals replace the rising signals to allow the attacker to take control of the drone.

Downlink signals are sent by the drone. The signals may contain flight information or video transmission, both of which can be intercepted by an attacker. Video transmission is typically being transmitted in an unsecured manner that is susceptible to interception.

Downlink and rising signals are not protected or rather encrypted. Therefore, both signals can be intercepted and allow the attacker to modify the transmission or take control.

Supervisory Control and Data Acquisition (SCADA)
Supervisory Control and Data Acquisition (SCADA) systems are known as the industrial control systems (ICS), which means that they have a specific purpose of providing supervisory-level control over industrial or machinery that is meant to serve a specific purpose. They are used for managing the machinery or its related system. An example use case of the SCADA system can be in the electrical domain, where SCADA systems manage the distribution of the electricity over a large geographical area.

SCADA systems across the world have been attacked multiple times. The inherent vulnerabilities have been exploited. Some of the common vulnerabilities are:

Unmonitored systems: SCADA systems are typically unmonitored. There are no active monitoring systems that perform continuous monitoring for suspicious activities. Since there is no continuous monitoring, it is difficult to detect an attack when it takes place.
Passwords: Each SCADA system is built with some level of authentication. However, the human-errors lead to poor authentication with the SCADA systems. Humans tend to use poor and simple passwords or sharing of passwords, which leads to the compromise of the SCADA system authentication.
Poor update mechanism: SCADA systems are large most of the time, and they should be updated with the latest firmware and software from time to time. However, the lack of poor update management also causes an issue as there can be inherent vulnerabilities with the software or firmware. Therefore, once these vulnerabilities are known to the attacker, he or she can easily exploit them.
Inadequate input validation: SCADA system applications may need some type of user inputs. However, in some cases, such as WebAccess SCADA from Advantech did not validate the user input, which gave the attacker an opportunity to execute arbitrary code.
There are different components of a SCADA system that can be a target for the attacker. Some of the key components are:

Human Machine Interfaces (HMIs): Are used to present the data to the users after collecting it from various sensors. If not secured properly, they can be a target for the attackers.
Mobile and Web Applications: SCADA systems can be either accessed using a mobile or a Web application. Just like in any industry, both the mobile and the Web application can have bugs, which can be exploited by the attackers.
Protocols: SCADA systems use various protocols, such as Modbus and Profinet, which lacks a strong security mechanism. The data traveling over these protocols can be intercepted and altered by the attacker.

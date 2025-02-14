# O.MG Cable Installation and Setup Lab Sheet
## Research Content of O.MG
-	Understanding 
-	Concept
-	Features and Functionalities
-	Materials
-	Installation/setup
-	Payloads Scripts

## O.MG Cable Introduction
O.MG in as much as it is the name given to this Cable, is also an acronym for the phrase 'OH My God' that is used when things go wrong. What a coincidence right?
O.MG cable which is like every other type of our charging cable cannot be physically differentiated not even by a Tech professional. Not even when used until harm is caused with it before anyone can identify that something has gone wrong.
The O.MG Cable is a specialized security research and penetration testing tool that resembles a standard USB charging or data cable. However, it features embedded hardware that enables it to execute various network and security-related tasks. (Hak5, 2025).
According to (Damola O. Lawal, 2022), The application of mobile phones when using O.MG cable make it not to be suspected.

## Features of O.MG Cable
•	Keystroke Injection – There is no need to recompile or reprogram payload, just have to click.
•	Global Keymaps – It can target machines across the world with the 192 built in Keymaps.
•	Built in IDE – It provides total control and gives feedback on syntax errors when building payloads.
•	Lots of Payload Slots – It allows for up to 200slots of payloads for the Elite and for the basic, it has up to 8slots.
•	Easy Wi-Fi Control – It have full control your System or mobile web browser.
•	Self-Destruct – The O.MG can ensure sensitive payloads and loots are gone making it motionless.
•	Wi-Fi Triggers – It have the capability to trigger from a long distance.
•	Stealth – The behaves like the regular USB cable until the payload is deployed.
•	Mobile Payload – With the use of the USB-C active end or the Directional C to C cable, you can to mobile device.
•	Encrypted Network C2 – Can access and control OMG from anywhere using an encrypted connection.
•	Geo-Fencing – The O.MG triggers actions and payloads based on the location (HAK5, 2025)

## Core Functionalities:
### Network Capabilities
- Can act as a Wi-Fi client or access point
- Remote command execution
- Geofencing options
- Payload triggering based on various conditions

### Keystroke Injection
- Can emulate a USB HID (Human Interface Device)
- Capable of typing commands automatically
- Support for multiple keyboard layouts
- Scriptable actions

### Data Collection
- Keylogging capabilities
- USB traffic monitoring
- Network reconnaissance

### Remote Management
- Web-based interface
- Command line interface
- API access
- Remote payload deployment.

## Types of O.MG Cable Active End Port
- USB A
- USB C
- Directional C To C

![Screenshot (184)](https://github.com/user-attachments/assets/194a6918-a0f5-48aa-a126-cfb79be1da52)

## O.MG Setup Pack
- O.MG Cable either USB-A, USB-C or Directional C to C
- O.MG Programmer
- Regular USB Cable
- O.MG Adapter
- Device (Laptop, Phone, Notepad, etc.)

## Physical Setup
The device is designed to appear identical to standard USB cables, such as Lightning or USB-C, making it indistinguishable from ordinary peripherals. Internally, it contains an embedded Wi-Fi module, internal memory, and a chip, allowing for advanced functionality. It powers itself directly through the USB connection, eliminating the need for an external power source.

## Configuration
### Initial Access
When plugged into a USB port, the device powers on automatically. It can either create a standalone Wi-Fi network or connect to an existing one, allowing remote access. The web interface, accessible at a specific IP address, provides control over its functions. During the first setup, it is crucial to change the default credentials to enhance security.

### Payload Management
The device supports multiple payloads with conditional execution based on various factors, including target operating system detection, time-based triggers, physical location, or specific hostname matching. Payloads can range from simple keystrokes and shell commands to specialized scripts tailored for specific attack scenarios.

## Operational Modes
### Stealth Mode
To maintain discretion, the device mimics genuine USB behavior with configurable LED indicators and customizable device identifiers. Traffic obfuscation techniques further help disguise its presence.

### Storage Mode
The device can function as a legitimate storage device, allowing users to configure storage capacity, manipulate auto-run functions, and customize the file system to blend seamlessly with standard USB drives.

### Debug Mode
For troubleshooting and optimization, the device offers detailed logging capabilities, performance monitoring, and error tracking. Network diagnostics tools help assess connectivity and operational efficiency.

## Process:
Plug the regular USB cable into the system, then plug the cable to the PC side of the O.MG programmer, the PWR light and the USB light will lite up. Connect the active end of the O.MG cable to the O.MG port side of the O.MG Programmer. The O.MG light will light up making it three lights to show that the cable connected to the device is successful and recognized by the device. 
Proceed to your browser and type or
- [Click Here](https://o.mg.lol/setup/OMGCable/)

- Click on WEBFLASHER
  ![Screenshot (177)](https://github.com/user-attachments/assets/5d8ef9b7-84df-41ea-b9ba-00d3594ac655)

- Scroll through to read through the Agreement
![Screenshot (178)](https://github.com/user-attachments/assets/fdaefb8b-6ee1-423b-8773-69e7e7fc5011)

- Click on 'I Agree'
![Screenshot (179)](https://github.com/user-attachments/assets/5ad87c82-4103-444e-b494-3cdbc1541bc8)

- First connect your O.MG Programmerto the device/computer
- Then, connect the active end of the O.MG cable to the O.MG programmer
- Click on the Continue Button after doing the above
![Screenshot (181)](https://github.com/user-attachments/assets/a5316012-0a43-4d90-81f2-8a76108bfd4f)

## Implementation Best Practices:
### Payload Structure
•	Implement appropriate delays
•	Integrate error handling
•	Ensure cleanup routines
•	Include logging mechanisms
### Execution Flow
•	Begin with minimal privileges
•	Escalate only when necessary
•	Validate each step thoroughly
•	Perform cleanup after execution
### Data Management
•	Use secure storage locations
•	Encrypt sensitive data
•	Ensure proper data removal
•	Maintain access logs
### Key Considerations
•	Always test payloads in isolated environments first
•	Document all testing procedures
•	Obtain and maintain proper authorization
•	Adhere to security testing protocols
•	Perform thorough cleanup after testing

## Security Features
Authentication Methods include multi-factor authentication support, SSH key management, custom certificate implementation, session management, and role-based access control.
Encryption Options focus on securing data through end-to-end payload encryption, secure communication channels, custom encryption keys, and traffic encryption protocols.
Hardware Interfacing enables USB power negotiation, data line manipulation, signal timing control, and hardware-level protocol emulation.
Operating System Interaction ensures cross-platform compatibility, OS fingerprinting, driver manipulation, and system service interaction.
Data Exfiltration Methods involve covert channel creation, data compression, custom protocol implementation, and staged exfiltration for efficient data transfer.

## Best Practices for Security Testing
Documentation is essential, requiring detailed logs, configuration records, test scenario documentation, and thorough tracking of findings and results.
Testing Environment should be carefully managed with an isolated network setup, controlled test conditions, active monitoring systems, and well-defined recovery procedures.
Risk Mitigation includes impact assessments, scope definition, authorization verification, and robust incident response planning to address potential threats.
Compliance Considerations demand adherence to legal requirements, clearly defined testing boundaries, proper documentation, and fulfilment of reporting obligations.


## Basic Payload Types
### Open Notepad and Type a Message
``` DELAY 500  
STRING Hello, this is an auto message.
ENTER
```

### Open Command Prompt and List Files
``` DELAY 500  
STRING cmd  
ENTER  
DELAY 500  
STRING dir  
ENTER
```

### Open a Website in Browser
``` DELAY 500  
STRING start https://example.com  
ENTER  
```

### Turn Off the Computer
``` DELAY 500  
STRING shutdown /s /t 5  
ENTER  
```

### Display a Message Box (Windows)
``` DELAY 500  
STRING powershell -command "msg * Hello, this is a test!"  
ENTER  
```

### Open Calculator
``` DELAY 500  
STRING calc  
ENTER  
```

### Open Task Manager
``` DELAY 500  
STRING taskmgr  
ENTER  
```

### Enable Caps Lock (Even if It's Off)
``` DELAY 500  
CAPSLOCK  
```

### Open Notepad and Write Random Text Repeatedly
``` DELAY 500  
STRING notepad  
ENTER  
DELAY 500  
STRING This is a test...  
ENTER  
STRING This will repeat...  
ENTER  
STRING Over and over!  
ENTER  
```

### Open File Explorer
``` DELAY 500  
STRING explorer  
ENTER  
```

### Open the Run Dialog Box
``` DELAY 500  
GUI R  
```

### Quick System Access
REM Fast User Access
``` DELAY 500
GUI r
DELAY 200
STRING notepad
ENTER
DELAY 500
STRING System accessed for testing
ENTER
```

Observations:
1. THE DEVICE THE CABLE IS PLUGGED ON, THE SCRIPT CAN BE EXECUTED ON
2. ATTACK CAN COME FROM DIFFERENT DEVICES AS LONG AS IT IS CONNECTED TO THE OMG WIFI AND THE OMG CABLE ACTIVE END IS PLUGGED IN A DEVICE.

Important Security Considerations
These devices emphasize the critical role of USB security within organizations, underscoring the need for strict security measures. They should only be utilized in authorized security testing scenarios to prevent misuse. Their existence highlights the importance of implementing robust USB security policies and reinforces the necessity of employee security awareness training to mitigate potential threats.
Key Defensive Measures
To enhance security, organizations should adopt preventive measures such as using USB data blockers when charging from untrusted sources. Implementing USB device whitelisting helps restrict unauthorized access, while deploying endpoint protection solutions adds an additional layer of defense. Establishing clear USB usage policies further ensures that employees follow best practices for maintaining security.

Conclusion:
Create Payload script to start launching attacks on the device. You can get written payload script by clicking https://github.com/hak5/omg-payloads
Warring!!! Make sure there are no sensitive information on the device the OMG Cable is plugged into.

References
Damola O. Lawal, D. W. (2022). Facilitating a Cyber-Enabled Fraud Using the O.MG Cable to Incriminate the Victim. World Academy of Science, Engineering and Technology International Journal of Computer and Systems Engineering, Vol:16, No:9, pg 367-372.
Hak5. (2025, February 12). Retrieved from HAK5: https://shop.hak5.org/products/omg-cable?srsltid=AfmBOop1Lgi6J65ack-gc0jh76GgsLGZo2YxgT8h23rXIXjU2pTZY49

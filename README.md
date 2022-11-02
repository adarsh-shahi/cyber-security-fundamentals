# cyber-security-fundamentals
Notes about Introduction to Cyber Security and Terminologies

Cyber Security Notes
    
The Definition of Computer Security:
Security is a state of well-being of information and infrastructures in which the possibility of successful yet undetected theft, tampering, and disruption of information and services is kept low or tolerable
Security rests on confidentiality, authenticity, integrity, and availability

1. Confidentiality: 
The degree of confidentiality determines the secrecy of the information. The principle specifies that only the sender and receiver will be able to access the information shared between them. Confidentiality compromises if an unauthorized person is able to access a message. 
For example, let us consider sender A wants to share some confidential information with receiver B and the information gets intercepted by the attacker C. Now the confidential information is in the hands of an intruder C.

2. Authentication: 
Authentication is the mechanism to identify the user or system or the entity. It ensures the identity of the person trying to access the information. The authentication is mostly secured by using username and password. The authorized person whose identity is preregistered can prove his/her identity and can access the sensitive information.

3. Integrity: 
Integrity gives the assurance that the information received is exact and accurate. If the content of the message is changed after the sender sends it but before reaching the intended receiver, then it is said that the integrity of the message is lost.

4. Availability: 
The principle of availability states that the resources will be available to authorize party at all times. Information will not be useful if it is not available to be accessed. Systems should have sufficient availability of information to satisfy the user request.

# Security Policies
Security policies are a formal set of rules which is issued by an organization to ensure that the user who are authorized to access company technology and information assets comply with rules and guidelines related to the security of information. It is a written document in the organization which is responsible for how to protect the organizations from threats and how to handles them when they will occur. A security policy also considered to be a "living document" which means that the document is never finished, but it is continuously updated as requirements of the technology and employee changes.
Need of Security policies-

1) It increases efficiency.
The best thing about having a policy is being able to increase the level of consistency which saves time, money and resources. The policy should inform the employees about their individual duties, and telling them what they can do and what they cannot do with the organization sensitive information.

2) It upholds discipline and accountability
When any human mistake will occur, and system security is compromised, then the security policy of the organization will back up any disciplinary action and also supporting a case in a court of law. The organization policies act as a contract which proves that an organization has taken steps to protect its intellectual property, as well as its customers and clients.

3) It can make or break a business deal
It is not necessary for companies to provide a copy of their information security policy to other vendors during a business deal that involves the transference of their sensitive information. It is true in a case of bigger businesses which ensures their own security interests are protected when dealing with smaller businesses which have less high-end security systems in place.

4) It helps to educate employees on security literacy
A well-written security policy can also be seen as an educational document which informs the readers about their importance of responsibility in protecting the organization sensitive data. It involves on choosing the right passwords, to providing guidelines for file transfers and data storage which increases employee's overall awareness of security and how it can be strengthened.



# Security Layers:

![Screenshot from 2022-10-29 20-58-46](https://user-images.githubusercontent.com/60755364/198842660-5e3eebdb-cb44-4813-bba4-9d69092108c4.png)

# Security Techniques:
1. Access Control: The access to the data and computer is controlled. If the user misuses the privileges given to her/him then the access to such user is denied.
2. Backup of data: We can secure our data by taking regular backup. We can secure our data by storing another copy of data at another location.
3. Antivirus software: No. of antivirus software are available which provides security to our the system from malicious software.
4. Firewall: Firewall is used to protect internal networks from external attacks. It is acting like a security door to our network
5. Encryption: It is the cryptographic technique used to protect information. There are two methods of encryption symmetric and asymmetric encryptions

# Types of Attacks(Classification)
1. Active Attacks: Active attacks are the type of attacks in which, The attacker efforts to change or modify the content of messages. Due to active attack system is always damaged and System resources can be changed. The most important thing is that, In active attack, Victim gets informed about the attack.

![Untitled-Diagram-261](https://user-images.githubusercontent.com/60755364/198842843-111bda3b-13ba-4ef6-a3e1-b7410c9a53fc.png)

2. Passive Attacks: Passive Attacks are the type of attacks in which, The attacker observes the content of messages or copy the content of messages. Passive Attack is a danger for Confidentiality. Due to passive attack, there is no any harm to the system. The most important thing is that In passive attack, Victim does not get informed about the attack.

![Untitled-Diagram-271](https://user-images.githubusercontent.com/60755364/198842877-a439c78f-b7d2-43b6-b9b2-84a2cdadedc5.png)

![activePassiveAttacks](https://user-images.githubusercontent.com/60755364/198843150-7af905e7-4141-4760-b932-825842128e62.png)

# Symmetric Key Encryption
Encryption is a process to change the form of any message in order to protect it from reading by anyone. In Symmetric-key encryption the message is encrypted by using a key and the same key is used to decrypt the message which makes it easy to use but less secure. It also requires a safe method to transfer the key from one party to another.

![Screenshot from 2022-10-29 22-17-36](https://user-images.githubusercontent.com/60755364/198843385-59c498e9-3b2f-4c61-b680-0b57fd71c3ab.png)
![Screenshot from 2022-10-29 22-22-21](https://user-images.githubusercontent.com/60755364/198843558-8ff90835-6cce-437d-bca7-cc3d2423fa68.png)


# Asymmetric Key Encryption
Asymmetric Key Encryption is based on public and private key encryption techniques. It uses two different key to encrypt and decrypt the message. It is more secure than the symmetric key encryption technique but is much slower.

Types of Security Mechanisms
Types of Security Mechanism are :

1. Encipherment :
This security mechanism deals with hiding and covering of data which helps data to become confidential. It is achieved by applying mathematical calculations or algorithms which reconstruct information into not readable form. It is achieved by two famous techniques named Cryptography and Encipherment. Level of data encryption is dependent on the algorithm used for encipherment.

2. Access Control :
This mechanism is used to stop unattended access to data which you are sending. It can be achieved by various techniques such as applying passwords, using firewall, or just by adding PIN to data.

3. Notarization :
This security mechanism involves use of trusted third party in communication. It acts as mediator between sender and receiver so that if any chance of conflict is reduced. This mediator keeps record of requests made by sender to receiver for later denied.

4. Data Integrity :
This security mechanism is used by appending value to data to which is created by data itself. It is similar to sending packet of information known to both sending and receiving parties and checked before and after data is received. When this packet or data which is appended is checked and is the same while sending and receiving data integrity is maintained.

5. Authentication exchange :
This security mechanism deals with identity to be known in communication. This is achieved at the TCP/IP layer where a two-way handshaking mechanism is used to ensure data is sent or not

6. Traffic Padding − The insertion of bits into gaps in an information flow is known as traffic padding. This provide to counter traffic analysis attempts.

7. Routing Control − Routing control allows selection of specific physically secure routes for specific data transmission and enables routing changes, particularly when a gap of security is suspected.

8. Digital Signature - This security mechanism is achieved by adding digital data that is not visible to eyes. It is form of electronic signature which is added by sender which is checked by receiver electronically. This mechanism is used to preserve data which is not more confidential but sender’s identity is to be notified.

# Categories of Security Services
 ## 1. Authentication 
 Authentication is the process of verifying the identity of a user when that user logs in to a computer system
  Single-Factor authentication
   Advantages of the Single-Factor Authentication System: –
    It is a very simple-to-use and straightforward system.
    it is not at all costly.
    The user does not need any huge technical skills.
   The disadvantage of the Single-Factor Authentication 
    It is not at all password secure. It will depend on the strength of the password entered by the user.
    The protection level in Single-Factor Authentication is much low.

  Two-Factor Authentication:
   Advantages of the Two-Factor Authentication
    The Two-Factor Authentication System provides better security than the Single-factor Authentication system.
    The productivity and flexibility increase in the two-factor authentication system.
    Two-Factor Authentication prevents the loss of trust.
   Disadvantages of Two-Factor Authentication
    It is time-consuming.

## 2.Authorization

    Authorization is a process by which a server determines if the client has permission to use a resource or access a file.
    Authorization is usually coupled with authentication so that the server has some concept of who the client is that is requesting access.
    The type of authentication required for authorization may vary; passwords may be required in some cases but not in others.
    In some cases, there is no authorization; any user may be use a resource or access a file simply by asking for it. Most of the web pages on the             Internet require no authentication or authorization.




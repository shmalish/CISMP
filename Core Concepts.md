Information security means protecting information and information systems from unauthorised access, use, disclosure, disruption, modification, perusal, inspection, recording or destruction.

Information assurance is tightly coupled with many aspects of business management including information technology infrastructure library 

Asset: Anything that has value to an organisation 
	If it has value to you, it has value to them
Information security protects:
	People
	Processes
	Reputation
	Buildings
	Information
	Hardware and software

There are many different assets such as:
	Information:
		Stored on paper i.e contracts, manuals and electronically i.e hdds, usb, video, phones, databases
	Software:
		Programs, operating systems, applications, dev tools
	Services:
		Service that the computer systems depend upon such as heating, cooling, power, lighting etc
	People:
		Employees, owners, managers who carry all the skills and information regarding how the company operates 
	Intangibles:
		Reputation and image
Examples are 
	Secret plans for a new product
	Reputation of the company in providing a highly available communication service


Principles of information security

Confidentiality:
	Non-disclosure, access on a need to know basis, least privilege. 
	It ensures that information is not disclosed to unauthorised people or processes.
	Requirement information is protected to prevent intentional or unintentional unauthorised disclosure i.e disgruntled employee
> Refers to limits on who can get what kind of information. i.e protecting secrets and personal data. 

Integrity:
- Protects the accuracy and completeness of assets. 
- Information is only useful if it is complete and accurate. 
- Modifications are not made to data by unauthorised personnel or processes
- Unauthorised mods are not made to the data even by authorised personnel or processes
- Data is internally and externally consistent. 

Availability:
	Reliable and timeless access to data or IT resources by appropriate people. 
	Guarantees systems are up and running when they are needed. 
	Hardware maintenance, software patching/upgrading and network optimisation ensures availability

Non Repudiation 
+ Holds individuals to account by knowing who did what and when they did it. 
	+ Proving someone sent an email
	+ Proving an online transaction took place
	+ Refers to the presentation of evidence that cannot be forged whereby the message can be proven as being sent or received. 
	+ If something is disputed, then important identity actions can be challenged or jeopardised. When this occurs, proof is determined by a 3rd party where neither the sender or receiver can dispute the action.
> The ability to prove the occurrence of a claimed event or action and its originating entities
> Proving someone actually sent the email to their employer/manager.
> Proving someone performed a transaction i.e ordering from the internet. 

# Getting the balance right 
 > Resources are limited
 > Confidentiality, integrity, availability are often in conflict.

Confidentiality is more important when the value of information depends on limiting access to it i.e way more important than integrity and availability in the case of trade secrets. Confidentiality is most important when the information is a record of peoples personal data. 

Integrity is more important in financial information. Changes in finance records can lead to issues in accuracy, consistency and value of the information. I.e banks are more concerned about integrity of financial records with confidentiality being 2nd priority. Some people leave receipts at the ATM. This shows how confidentiality is typically 2nd even if the receipt says data i.e name and amount deposited/withdrawn. 

# Defence in Depth & Breadth

## Defence in depth
There are layers of security that build on one another. It is impossible to protect all information assets to the highest degrees possible cos it costs too much gwap. Also because some information assets need to be freely available to staff in order for them to do their job. Other information is more critical and sensitive so they get priority for protection. 

## Defence in breadth
Coined phrase that came due to all the connections to any networked system. Networks these days are getting super complex and difficult to manage. 

This concept of understanding the breadth of the network is critical --> at its weakest link it will break. 

In a complex network, a criminal will try to break in via the lowest level of security point. Malware can travel through a network, finding holes or legitimate services can make the intruder seem as a trusted user. 

Defence in depth and breath is a strategy to leverage security to provide redundancy, to buy time to detect and enact a response and to span the wide reaching end points and variety of security systems to provide a timely synchronised response. 

### AAA
Authentication (verify the identity of a person), authorisation (verify the persons has the correct permissions to access something) and accounting (recording the persons access by logging their activities) .


# IAAA framework
## Identity
Information that unambiguously distinguishes one entity from another one in a given domain.

Creating unique usenames. Not sharing usernames. Unique system to make sure it's all unique.

Your username is the identity by which the system can account for your actions. Identities are used to uniquely name system processes so that the system can establish which processes are performing which tasks. 

## Authentication 
The provision of assurance that a claimed characteristic of an entity is correct. 
	A user logs into a system with a username and password. 
	Device authentication, a smart card authenticated to a card reader. 

> The most common form of an entity being authenticated is that of a user but it may be a system process, remote computer, or a web service. 

> ID&A --> identity and authentication 

If you claim to be an entity, you must identify yourself via authentication to prove you are who you say you are. 

## Access control and authorisation 

This is a means to ensure that access to assets is authorised and restricted based on business and security requirements. 

Rules to decide whether to grant access to requests

Access rights allow authorised users to perform only authorised actions. 

> A means to ensure that access to assets is authorised and restricted based on business and security requirements 

To authorise is to define an access policy so the system can decide whether access request from authenticated entities are granted or denied. 

> Example, system authorises HR staff to access employee records but normal users can't. 

## Logging

>  Records actions that are recorded and can be tracked back to the party responsible, whether things a user does to an object is recorded. 

Looking at the audit trail is helpful when things fail. I.e seeing what time a stock trader performed a large trade, where and how. 

An audit log is a document that records an event in an information technology system. Entries usually include destination, source address, timestamp and user login information.

## Audit

> Systematic, independant and documented process for obtaining audit evidence and evaluating it objectively to determine the extent to which the audit criteria are fulfilled. 

- Shwoing the files opened or software executed
- Physical security check

Closely associated with accountability and in reality has a wide scope. Checking that processes, policies and procedures are followed. Checking security controls are functioning as expected and inspecting audit trails within computer systems to establish what actions given users were performing. 

I.e details of what files were opened or who executed a particular software application 

Check that the team is following physical security procedures for controlling access to your secure data centre. 

## IAAA process and accountability 

> Accountability is the ability to hold individuals, groups, companies and other organisations accountable for their actions. To help deter malicious or risky behaviour. 

Ensures that the actions of an entity may be traced uniquely to the entity. 

IAAA - Identification, authentication, authorisation, accountability/auditing 


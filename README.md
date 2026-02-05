# Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 

# AIM:

To use Google for gathering information and perform enumeration of targets

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various Google hacking keywords and enumeration tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified:
Information Gathering.

Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

site: This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain sony.com

### OUTPUT:

<img width="1918" height="1030" alt="image" src="https://github.com/user-attachments/assets/4ccf130e-156c-48f1-b7c8-730d9a2b1977" />


filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com

### OUTPUT :

<img width="1919" height="1028" alt="image" src="https://github.com/user-attachments/assets/4df889cf-81a4-4481-aba5-de48b4c1be3a" />


intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.

### OUTPUT :

<img width="1919" height="1031" alt="image" src="https://github.com/user-attachments/assets/987c0f71-333b-42d7-989e-0fbc6456cc4f" />


inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.
### OUTPUT :

<img width="1919" height="1029" alt="image" src="https://github.com/user-attachments/assets/17f0ffb7-b886-4c5d-bcd6-8c2bf5ced9c9" />

intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.
### OUTPUT :

<img width="1919" height="653" alt="image" src="https://github.com/user-attachments/assets/22457257-83ed-4ef6-b503-e863052210eb" />

link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.
### OUTPUT :

<img width="1919" height="1031" alt="image" src="https://github.com/user-attachments/assets/e5ced576-f9c4-4040-957f-3d2b7097642a" />

cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.
### OUTPUT :

<img width="1919" height="1028" alt="image" src="https://github.com/user-attachments/assets/75ef810f-c642-4a9e-8e35-d6d9c934e24f" />

 
# DNS Enumeration


## DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion
## OUTPUT:

<img width="946" height="230" alt="image" src="https://github.com/user-attachments/assets/77533a59-167e-4b83-b211-17755cae1be1" />







## dnsenum
Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:

Get the host’s addresses (A record).
Get the namservers (threaded).
Get the MX record (threaded).
Perform axfr queries on nameservers and get BIND versions(threaded).
Get extra names and subdomains via google scraping (google query = “allinurl: -www site:domain”).
Brute force subdomains from file, can also perform recursion on subdomain that have NS records (all threaded).
Calculate C class domain network ranges and perform whois queries on them (threaded).
Perform reverse lookups on netranges (C class or/and whois netranges) (threaded).
Write to domain_ips.txt file ip-blocks.
This program is useful for pentesters, ethical hackers and forensics experts. It also can be used for security tests.

### OUTPUT :

<img width="924" height="808" alt="image" src="https://github.com/user-attachments/assets/268323db-9d68-420c-b4a6-84a8f895c78a" />

## smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.


In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same

### OUTPUT :

<img width="750" height="395" alt="image" src="https://github.com/user-attachments/assets/1f730e46-76c5-41d4-ac33-00b4a35b88ca" />

# Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands
  
 ## Output
  <img width="774" height="455" alt="image" src="https://github.com/user-attachments/assets/b621ea8a-915a-4ec9-982c-2b614275fe12" />

  

## nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.


## OUTPUT:

<img width="623" height="195" alt="image" src="https://github.com/user-attachments/assets/476029aa-c5c4-4de9-a0c2-f29ce598637a" />


## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully


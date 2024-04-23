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
Following searches for all the sites that is in the domain yahoo.com
## output:
![image](https://github.com/skiruthika648/Enumeration/assets/128348968/2caf89ce-bb75-44e9-92ed-c66dcfd1de08)


filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com
## output:
![image](https://github.com/skiruthika648/Enumeration/assets/128348968/662da306-44ec-4204-90da-04dd6f9ec60a)


intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.
## output:
![image](https://github.com/skiruthika648/Enumeration/assets/128348968/bdd8fd0a-c039-4673-8a8a-0e0a69d28911)


inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.
## output:
![image](https://github.com/skiruthika648/Enumeration/assets/128348968/75719451-b054-4d13-8250-b14667148ced)


intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.
## output:
![image](https://github.com/skiruthika648/Enumeration/assets/128348968/78f04213-6ee2-4166-bd8e-c85b1989db34)


link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.
## output:
![image](https://github.com/skiruthika648/Enumeration/assets/128348968/7fd7b052-8a6c-4a58-8906-045c8106cd12)


cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.

## output:
![image](https://github.com/skiruthika648/Enumeration/assets/128348968/32f51a2a-ba74-4089-8011-25865d88712b)


 
## DNS Enumeration


## DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion

## OUTPUT:

![image](https://github.com/skiruthika648/Enumeration/assets/128348968/aaf54cc1-0f6b-40ce-a77f-7f88f6236b30)


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
## output:
![image](https://github.com/skiruthika648/Enumeration/assets/128348968/15c82e37-edf6-4481-b24b-26143268c648)



## smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.


In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same

![image](https://github.com/skiruthika648/Enumeration/assets/128348968/d1aa2ea1-4abc-46f3-888d-8881ee2eda2a)

# Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands

 ## Output
  ![image](https://github.com/skiruthika648/Enumeration/assets/128348968/f753528b-2341-41b7-afac-fe3eb6e73ca8)

## nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.

## OUTPUT:
![image](https://github.com/skiruthika648/Enumeration/assets/128348968/9f1ddcce-47a7-4dac-8144-320d2b7bb3da)


## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully


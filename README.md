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
Following searches for all the sites that is in the domain google.com

<img width="955" height="930" alt="image" src="https://github.com/user-attachments/assets/aed1aaea-9290-45b1-9488-bece458fee98" />

filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain google.com

<img width="955" height="930" alt="image" src="https://github.com/user-attachments/assets/2f5b987d-3ac2-41ac-b379-19c858a3588d" />



intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.

<img width="955" height="930" alt="image" src="https://github.com/user-attachments/assets/6f9b29ff-04d9-4a01-8e35-6ed59c752f58" />


inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.

<img width="955" height="930" alt="image" src="https://github.com/user-attachments/assets/ed1e101c-e249-475d-a0aa-8c389aa6d547" />


intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag:

<img width="955" height="930" alt="image" src="https://github.com/user-attachments/assets/756473eb-de79-4311-b872-d84fbb77f0a6" />


link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.
<img width="955" height="930" alt="image" src="https://github.com/user-attachments/assets/7afd5584-be34-4c03-a514-b585f3d6edb9" />


cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.

#DNS Enumeration


##DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion
## OUTPUT:
<img width="957" height="1018" alt="image" src="https://github.com/user-attachments/assets/2346be61-3324-4947-9050-d6d9571a8198" />



##dnsenum

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
<img width="947" height="950" alt="image" src="https://github.com/user-attachments/assets/39c5935e-22a1-4bdf-9a70-abe19a3ba3bf" />

##SMTP User Enumeration – smtp-user-enum
## Create username list and VRFY enumeration


<img width="907" height="452" alt="image" src="https://github.com/user-attachments/assets/52d40d96-9a74-493c-8f31-fc646a181537" />

## RCPT enumeration

<img width="827" height="422" alt="image" src="https://github.com/user-attachments/assets/2ee0739f-00cd-46d1-8ad1-d5b48fcc9fbf" />

##EXPN enumeration

<img width="875" height="376" alt="image" src="https://github.com/user-attachments/assets/b437e936-a13e-480d-a65e-54d650a5f12b" />



##Telnet for SMTP Enumeration

<img width="872" height="420" alt="image" src="https://github.com/user-attachments/assets/e92a6996-f997-4a6f-b18a-dc432c31a4d6" />


##Nmap – smtp-enum-users.nse


<img width="667" height="232" alt="image" src="https://github.com/user-attachments/assets/8e4831e9-c70b-4a74-abe5-299a50394d09" />



## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully


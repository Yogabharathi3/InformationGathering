# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

# Pen Test Tools Categories:

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.

http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:
![238300689-505c1008-6602-4c30-a18f-a19831193609](https://github.com/Yogabharathi3/InformationGathering/assets/118899387/c236a03a-783f-4672-8198-fc1d89f37aef)
# Finding IP address:

ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```
# OUTPUT:
![238300810-18c141eb-f997-4e6a-970b-1278bf0f085f](https://github.com/Yogabharathi3/InformationGathering/assets/118899387/f01c8d65-d1f3-4884-ac6c-1221a981ee49)
# Finding Hosting Company

get further detail by using ip2location.com website.

# OUTPUT:
![238302790-ad2a8edd-7197-44ae-9f54-94375c7114a9](https://github.com/Yogabharathi3/InformationGathering/assets/118899387/05d5a8ee-63ef-4b4b-bfd6-dc0b24c8566c)
# History of the website:
# Output:
https://web.archive.org/
![238300893-192a1d85-246e-45ad-bcd0-0a70e209c601](https://github.com/Yogabharathi3/InformationGathering/assets/118899387/1482edf7-d787-4f4b-a812-bf045b356d0d)

# Webserver Fingerprinting:
# Netcat:
```
nc 172.17.52.118 80
```
# OUTPUT:
![238301333-7c38b307-51d1-45b5-85ec-751ed930ba9b](https://github.com/Yogabharathi3/InformationGathering/assets/118899387/8fe7adae-cd0a-4678-9aab-987b11a215e2)
# nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
# OUTPUT:
![238301531-4631c0fd-1296-4c74-82fa-8950c48c5a61](https://github.com/Yogabharathi3/InformationGathering/assets/118899387/c4445aac-e9ce-41a9-beaa-ff673946aa68)
# Whatweb:
```
whatweb infosys.com
```
```
whatweb zoho.com
```
```
whatweb -v -a 3 172.17.52.201
```
# OUTPUT:
![238301746-ab6e52ed-b1c2-4c7c-b4cb-edc75d6de5e6](https://github.com/Yogabharathi3/InformationGathering/assets/118899387/6e501834-cf5d-4b47-beda-241fdf8760b8)
![238302016-3daa0d6f-df5d-4571-bf8b-c2fe63bbc3cc](https://github.com/Yogabharathi3/InformationGathering/assets/118899387/d9a65600-8a89-417e-9a57-8895db7fa0b4)
# httprint:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
# OUTPUT:
![238301937-a70e6db5-d324-4bee-80f9-9dfdf9b37338](https://github.com/Yogabharathi3/InformationGathering/assets/118899387/72f9c6f3-7f75-4f89-8131-a915edea0a13)
# Tracing the Location
# TCP Traceroute:
```
sudo traceroute -T www.saveetha.ac.in
```
# OUTPUT:
![238302091-8c7b84b9-8045-45c3-ba6a-f2af47f40e5e](https://github.com/Yogabharathi3/InformationGathering/assets/118899387/439068ab-66f2-43a6-8d92-1a7b8504893d)
# ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
# OUTPUT:
![238302109-00a45edd-a2df-4cc6-858c-87d5b4a6b659](https://github.com/Yogabharathi3/InformationGathering/assets/118899387/318c47a4-284b-454a-bdb5-f1928542102d)

## RESULT:
The information gathering techniques tools/procedure were  identified successfully

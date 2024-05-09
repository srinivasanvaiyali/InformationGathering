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


## OUTPUT:
![image](https://github.com/srinivasanvaiyali/InformationGathering/assets/145117665/0bc678c8-82eb-4c7f-8aab-7190b169e6e0)

## Finding Ip:
ping saveetha.ac.in

## Output
![image](https://github.com/srinivasanvaiyali/InformationGathering/assets/145117665/5ddc377c-5764-48cf-bd74-c9beb582fb57)

## Finding the host of the company:
![image](https://github.com/srinivasanvaiyali/InformationGathering/assets/145117665/76eda13f-4b53-470e-aa71-8cb727665cdc)
## History of the website:
## Output:
![image](https://github.com/srinivasanvaiyali/InformationGathering/assets/145117665/46e7bac7-d88f-4cb9-b670-14fb744fc6b1)
## Webserver Fingerprint:
![image](https://github.com/srinivasanvaiyali/InformationGathering/assets/145117665/8a1a7639-3229-4175-8b1c-82e8b50e77ef)

## nmap:
## OUTPUT:
![image](https://github.com/srinivasanvaiyali/InformationGathering/assets/145117665/52b7f44b-5dbf-48b7-bc96-3f29892cc33a)

## Whatweb:
whatweb infosys.com

whatweb zoho.com

whatweb -v -a 3 172.17.52.201

## Output:
![image](https://github.com/srinivasanvaiyali/InformationGathering/assets/145117665/c37edadc-ea57-473c-85ca-53945b75f1cf)

## httprint:
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more

## Output:
![image](https://github.com/srinivasanvaiyali/InformationGathering/assets/145117665/3dcec240-9bf6-4c55-b526-1e8f70af839a)

## UDP Traceroute:
sudo traceroute -T www.saveetha.ac.in

## output:
![image](https://github.com/srinivasanvaiyali/InformationGathering/assets/145117665/5c89b4b1-bb13-4128-8c6e-a9c617f64fd0)

## ICMP Traceroute:
sudo traceroute www.saveetha.ac.in

## output:
![image](https://github.com/srinivasanvaiyali/InformationGathering/assets/145117665/ef653eaa-bc15-4d72-9488-05b6f133b56b)




## RESULT:
The information gathering techniques tools/procedure were  identified successfully

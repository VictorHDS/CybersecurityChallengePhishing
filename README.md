# Phishing to Capture Facebook Credentials:
### Tools:
- Kali Linux
- setoolkit
### Step-by-Step:
- Root access: ``` sudo su ```
- Starting setoolkit: ``` setoolkit ```
- Type of attack: ``` Social-Engineering Attacks ```
- Attack Vector: ``` Web Site Attack Vectors ```
- Attack method: ```Credential Harvester Attack Method ```
- Attack method: ``` Site Cloner ```
- Getting host address: ``` ifconfig ```
- URL for clone: http://www.facebook.com
### Results:
#### Tests in the Default Browser:
The first tests done on Brave showed encrypted credentials, probably because the browser is very secure.

![testPhishingEncrypted](https://github.com/VictorHDS/cibersecurity-desafio-phishing/assets/30830415/5a06534c-9512-45f7-abb5-4fdae70acae2)
#### Tests in an Alternative Browser:
I did another test, this time through Microsoft Edge and it worked, this time the prompt displayed the credentials in plain text.

![testPhishingWorking](https://github.com/VictorHDS/cibersecurity-desafio-phishing/assets/30830415/6c3d85b5-c786-483f-a625-d5c509cf3eca)

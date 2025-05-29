[![GitHub stars](https://img.shields.io/github/stars/jkerai1/Security-Toolbox?style=flat-square)](https://github.com/jkerai1/Security-Toolbox/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/jkerai1/Security-Toolbox?style=flat-square)](https://github.com/jkerai1/Security-Toolbox/network)
[![GitHub issues](https://img.shields.io/github/issues/jkerai1/Security-Toolbox?style=flat-square)](https://github.com/jkerai1/Security-Toolbox/issues)
[![GitHub pulls](https://img.shields.io/github/issues-pr/jkerai1/Security-Toolbox?style=flat-square)](https://github.com/jkerai1/Security-Toolbox/pulls)

# Security-Toolbox

The concept behind this project is to leverage Github Workflows for Security related Tasks. Security Teams may not always have access to a terminal (e.g. A nightime callout) to validate a finding.  

# Guidelines  

⚠️**DO NOT** leverage this repo for malicious intent. Only perform IP/domain scans on assets you have permission to.  

⚠️**DO NOT** excessively use github runners for bulk tasks.  

# Current Workflows Available  
> Workflows missing from this table are experimental

| Workflow| Description | Source
| --- | --- | --- |
| CMSeeK  | CMS Detection suite - Scan WordPress, Joomla, Drupal and over 180 other CMSs |https://github.com/Tuhinshubhra/CMSeeK
| DNSTwist | Find lookalike domains that adversaries can use to attack you. Can detect typosquatters, phishing attacks, fraud, and brand impersonation|https://github.com/elceef/dnstwist
| GetTopWordsFromWebsite | Get Top Words from website | https://github.com/jkerai1/GeneratePasswordListFromWebsite
| Get Entra Tenant ID from Azure Subscription ID| Get Azure/Entra Tenant ID for a given Azure Subscription ID | https://www.lieben.nu/liebensraum/2020/08/get-tenant-id-using-azure-subscription-id/
| GoBuster | BruteForce Gobuster is a tool used to brute-force URIs (directories and files) in web sites. | https://github.com/OJ/gobuster
| Holehe | check if the mail is used on different sites like twitter, instagram | https://github.com/megadose/holehe    
| Ignorant | check if a phone number is used on different sites like snapchat, instagram| https://github.com/megadose/ignorant
| IPInfo | Get Information on IP address | https://ipinfo.io/
| Microburst Azure Domain Enumeration | EnumerateAzureSubDomains given a string such as company name | https://github.com/NetSPI/MicroBurst/tree/master
| Nikto | web server scanner | https://github.com/sullo/nikto
| PyWhat | Classify Strings | https://github.com/bee-san/pyWhat
| Ransomwatch | Grab data from ransomwatch | https://github.com/joshhighet/ransomwatch
| RustScan | Port Scanner in Rust | https://github.com/RustScan/RustScan
| SQLMap | Automatic SQL Inject Scanner | https://github.com/sqlmapproject/sqlmap
| WPSSCan | WordPress Security Scanner | https://github.com/wpscanteam/wpscan

# Experimental Workflows
| Workflow| Description | Source
| --- | --- | --- |
| Ciphey | Input encrypted text, get the decrypted text back | https://github.com/Ciphey/Ciphey


# Instructions  

1. Fork The Repo  
2. Go to Actions Tab from the forked repository
3. Dismiss the Warning
   
4. Select the workflow  

![image](https://github.com/jkerai1/Security-Toolbox/assets/55988027/81d4dd84-2a28-4fbb-be8d-011b72292672)

5. Hit Run Workflow
![image](https://github.com/jkerai1/Security-Toolbox/assets/55988027/732b9b26-42b1-4f9a-b5fe-2233004de35b)

6. Fill in the required fields, in this case its email address
![image](https://github.com/jkerai1/Security-Toolbox/assets/55988027/c3d9d267-f79d-4f29-8ed0-3e33657d7aa2)

7. After the flow has run select the workflow
![image](https://github.com/jkerai1/Security-Toolbox/assets/55988027/69907a8f-bb1b-4e49-9868-3e7988d45cfc)

8. Expand the job

![image](https://github.com/jkerai1/Security-Toolbox/assets/55988027/dd3b79f2-6117-45f6-a1c1-08ff5b4e5792)

9. Find the section where the job ran, the output of the command will be there. At current there is NO github commit from the action  

![image](https://github.com/jkerai1/Security-Toolbox/assets/55988027/a1497849-5f0d-4488-bb32-0c7086b9c310)

# Further Possible Additions to the ToolBox

Hundreds of Offensive and Useful Docker Images for Network Intrusion - https://houdini.secsi.io/  

CloudSecTools is a curated collection of open-source cloud security tools, helping security professionals, researchers, and engineers find the best resources for securing cloud environments - https://cloudsectools.com/

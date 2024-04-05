---
Grant-Number: "N/A",
Name: "Teonite",
Service-Provider: "",
Status: "In progress",
Grant-Link: "",
Website: "https://teonite.com/",
Grant-Size: "Large",
Total-Milestones: "5",
Current-Milestone: "M4",
M1: "11.09.2023","Complete",
M2: "25.09.2023","Complete",
M3: "02.10.2023","Complete",
M4: "14.08.2023","Complete",
M5: "21.08.2023","In review",
Twitter: "",
Public-Project-Chat: "",
Casper-PM: "https://github.com/piotr-dziubecki",
Project-GitHub-Repo: "",
---
<!--lang:en--> 
CSPR Live Block Explorer (or in fact any other Casper open-source block explorers) do not implement any services for smart contracts source code and deployment validation or smart contract source code browsing and interacting.
Our aim is to create: 
a) source code storage, validation, and browsing service that will expose an API for interacting with any service that would like to incorporate this functionality (CSPR Live or any other block explorer) and will have enterprise-grade security (with Hardware Security Modules - HSM - proposed: Nitro HSM 2)
b) distributed build system supporting a defined library of Rust compilers and casper-contract smart contract library versions in order to quickly produce WASM builds for further validation
c) extend casper-client (as a pull request) with functionalities for submitting the source code to the validation service
d) example web service (and React components library) - that will use the validation service and based on the submitted deploy hash can state if the deployment is validated - if so, enable to browsing the validated deploy source code
All milestones are in detailed outlined (and calculated in terms of budget and schedule) based on the following Work Breakdown Structure:
https://docs.google.com/spreadsheets/d/14FUmM3eBE2Gx10eGbtxVqkH7nC8QUEGN3KglSJdru1U
Smart Contract source code validation and browsing is a core and fundamental functionality in any block explorer (already implemented in various blockchains) - but Casper is lacking it.
The deployment code browsing is also critical for end users in terms of building trust, transparency, and peace of mind for anyone that would like to interact with the deployed smart contract - as they can read the code.
But there also is a huge opportunity in building a service that will have access to all smart contracts source codes (and validations), that will be the foundation for future additional services, like:
contract history (changes over time) view - what has changed over a selected time span
developer validation service - since Casper is an enterprise blockchain it would be of much value to implement the functionality of developer validation, exposing not only the source code validation but also detailed information about the developer who is responsible for the deployment (and source code).
Developer validation functionality can be simple - eg. enable the developer to sign the validated source code with the same private key (as the deployment) matching and verifying that the deployment is done by the same developer that submitted the validation - but also can implement KYC for developer validation, organization validation - enabling potential premium services like get detailed information of developer/organization responsible for the deployment
AI/Machine Learning service for analyzing the source code to find  scams and suspicious smart contracts (based on source code, and reports from security companies that did the code validation and testing) 
data statistics and analytics on the source code
premium validation services that could expose security analysis (which the security researcher has  audited the source code, and access to security report data)

<!--lang:es--] 

<!--lang:de--] 

<!--lang:fr--] 

<!--lang:pl--] 

<!--lang:uk--]

[!--lang:*-->  

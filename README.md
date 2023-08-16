# Public Repository for Casper Ecosystem
## Repository containing information about projects, services, service providers, and code repositories.

The [casperecosystem.io](https://casperecosystem.io) site uses the stored data in this repository to visualize the Casper Ecosystem.

## Casper Ecosystem

All entries reside in the `casperecosystem-io-data/ecosystem` subdirectory. 

When adding a new entry, we create a unique directory name and add `data.md` file inside.

### Example `data.md` file contents

```
--- 
Name: "Project name", 
Website: "https://projectsite.com/", 
Twitter: "https://twitter.com/projecttwitter", 
Tag: "Project Tag",
Contact: "hello(at)project.name",
contract-hashes-casper: "86f2d45f024d7bb7fb5266b2390d7c253b588a0a16ebd946a60cb4314600af74",
contract-hashes-casper-test: "e375d42c29c0e4b2baefa63cf2d70af34439eda851e08129d8515515d63bd6a9",
--- 
<!--lang:en--> 
Project description
```

Additionally, we can add the logotype for the project into the `assets` subdirectory and name it `logo.png`.

## Process Flow 

There are two ways in which a Project Owner can add their Project to Casper Ecosystem's list of projects.

- Option 1 - Submit a request from casperecosystem.io website
- Option 2 - Self Serve, i.e.
    - 2.1 - Clone this repo
    - 2.2 - Create the Project entry in the cloned repository
    - 2.3 - Raise a Pull Request to add the changes 

In both options 1 and 2, the Casper Association Ecosystem Team, along with the Casper Association Project Management and Community Review Volunteer teams, will review the request.

Upon successful review and approval, the required entry will be created by the automated project entry creation process.

Should the reviewer team require further information to process the request, they will notify the requestor to provide required information.

In case of any insufficient data/information or should the reviewer team consider the request cannot be processed, the user will be notified on the review outcome and the project will not be created/listed on the Casper Ecosystem.

Please find the details in the process flow diagram below;

![Project Intake Process Flow](https://github.com/casper-ecosystem/casperecosystem-io-data/raw/569fe61b7418ccf81532db03b077e1afb3dd52e9/.github/images/project_intake_process.png "Project Intake Process Flow")


## Contribution guide
We only accept contributions to the casperecosystem.io through GitHub. Contribute to the next release by submitting PRs (Pull Requests) to the main branch.


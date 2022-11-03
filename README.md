# Public repository for Casper ecosystem containing information about projects, services, service providers, and code repositories.

The https://casperblockchain.io site uses the stored data in this repository to visualize the Casper ecosystem.

## Casper Ecosystem

All entries reside in the `casperblockchain-data/ecosystem` subdirectory. 

When adding a new entry, we create a unique directory name and add `data.md` file inside.

### `project.md` file contents

```
--- 
Name: "Project name", 
Website: "https://projectsite.com/", 
Twitter: "https://twitter.com/projecttwitter", 
Tags: "Tag1, Tag2",
Contact: "hello(at)project.name",
contract-hashes-casper: "86f2d45f024d7bb7fb5266b2390d7c253b588a0a16ebd946a60cb4314600af74",
contract-hashes-casper-test: "e375d42c29c0e4b2baefa63cf2d70af34439eda851e08129d8515515d63bd6a9",
--- 
<!--lang:en--> 
Project descritpion
```

Additionally, we can add the logotype for the project into the `assets` subdirectory and name it `logo.png`.

## Contribution guide
We only accept contributions to the casperblockchain.io through GitHub. Contribute to the next release by submitting PRs (Pull Requests) to the main branch.



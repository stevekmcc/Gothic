# Gothic
Git repository demonstrating 12 different scenarios on how MetaEdit+ supports co-evolution of domain-specific modeling languages, tools and models. Each scenario is own version in Git. 

## Getting Started

1. Install MetaEdit+. 
MetaEdit+ user guide is available at: https://metacase.com/support/55/manuals/ and integration with VCS detailed at https://metacase.com/support/55/manuals/meplus/Mp-3_5.html. If in Linux ensure you have xterm installed, as the Git integration use it. 

2. Fork the https://github.com/mccjpt/Gothic repository into your own GitHub (or download repository for other VCS/locally). In your ~/metaedit directory, mkdir git. Add this new directory and your Git account URL (without /Gothic suffix) to a ~/metaedit/.vcsPaths file like this:
```
gitBaseDir=/home/myuser/metaedit/git
gitBaseURL=https://github.com/myuser
```
3. Run the following command to get a local clone of your online repo:
```
metaedit textForMERL: "_vcsInitClone('Gothic')" logoutAndExit
```
You'll be prompted for your GitHub/BitBucket password in an xterm, and assuming all goes well you can close the xterm at the end.

4. Start MetaEdit+, login to repository 'Gothic' and open the project 'Gothic Security'. 
You have now all 12 versions/scenarios been implemented. 

## Inspecting co-evolution scenarios individually
To see or conduct any particular scenario, checkout the version for your Git
1. Choose **Repository | Changes & Versions** and then checkout the wanted version by selecting **Extra VCS Commands | CheckOut**. 
2. Enter the name for the new MetaEdit+ repository to be created (enter e.g name of the scenario). 
3. Enter Git hash to check out the wanted version or enter hash of version 0 to start from the beginning.
   - MetaEdit+ starts and opens the repository asking for login (by default 'user'). Open the project to conduct the wanted co-evolution scenario.

## Prerequisites
MetaEdit+ 5.5 SR1, https://metacase.com/download

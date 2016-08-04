Using the repository template
=============================

In order to create a new repository using this template:

1. Create the repository on GitHub
  - Create the new repository manually on the GitHub website ensuring that you have created it under the gs-lab 
organisation. Set the repository's privacy setting appropriately and do not add either a .gitignore or README.md file.

2. Extend permissions to other GSLAB members
  - Within the new repository, navigate to **Settings** > **Collaborators & teams**. 
  - On this page, add **RA** as a Team.
  - Assign **RA** the  "Admin" permission level. 

3. Remove yourself as a repository collaborator
  - While you are still on **Settings** > **Collaborators & teams**, click the "X" to the right of your username
    under **Collaborators** to remove yourself as a repository collaborator. As a member of **RA**, you will retain 
    your Admin permissions. 

4. Prohibit merge commits so that the repository only permits squash merges
  - Within the new ewpository, navigate to **Settings** > **Options**. 
  - Under **Merge button**, deselect "Allow merge commits" and ensure that "Allow squash merging" is selected. 

5. Initialise the new repository with the template
  - Clone the template repository to the local directory where you would like to store the new directory.
  - At the command line, set your working directory to the template clone and enter the command 
    `source repo_maker.sh`; this will initialise your repository. 


Pre-requisites:
 - Stata MP (installed and added to path)
 - R (installed and added to path)
 - scons (installed -- 'pip install scons' if pip is available)
 - Latex and Lyx (installed and added to path)
 - Metropolis beamer theme (installed)
 - git and git-lfs (installed)


 To run:
  - In the root directory, type 'scons'. This should run everything that is flagged as being modified or with dependencies that have modified.


README.md template
==================

template

Overview
--------

Briefly describe your directory here. 

Notes
-----

Record notes pertaining to your directory here. 

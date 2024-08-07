<img width="479" alt="UNL_Logo" 
src="https://ucomm.unl.edu/images/brand-book/Our-marks/nebraska-n.jpg">

# Bioinformatics for pathogen evolution and ecology
## University of Nebraska-Lincoln, Department of Plant Pathology
### Instructor: Teddy Garcia-Aroca, PhD.

# Description

This GitHub repository serves as a resource for students enrolled in the course



| **CONTENTS**                                         |
| -----------------------------------------------------|
| 1. [INSTRUCTIONS](#instructions)                |
|												  |
| 2. [DATA](#data)                        |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[datasets](#datasets)                      |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[manuscripts](#manuscripts)                      |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[metadata](#metadata)                      |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[RStudio](#RStudio)                      |
|												|
| 3. [OBJECTIVES](#objectives)                |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[a. Build a phylogenetic tree](#phylogenetics)                      |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[b. Distribution of isolates per host](#Distribution_per_host)                      |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[c. Distribution of resistance genes](#Distribution_resistance_genes)                      |
|																			
|
| 4. [DATA ANALYSIS TOOLS](#data-analysis-tools)                             |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Donwloading genomes **(Done)**](#downloading_genomes) |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Assembling genomes **(Done)**](#assembling_genomes) |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Annotating genomes **(Done)**](#annotation)                                           |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Core genome alignment **(Done)**](#core_genomes)                                           |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Tree Building](#tree-building)                                        |
|																			
|
| 5. [VISUALIZATION TOOLS](#visualization-tools)                              |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Visualizations with R](#visualizations-with-r)                                |
|                                                                   |
| 6. [HOW TO VIDEOS](#how-to-videos)                              |



# 1. INSTRUCTIONS

The following tutorial describes what you will be expected to do in order to complete this course. We will be using version control to update your code and files in this repository.


1. [Fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo) this repository from the top right.

<img width="479" alt="fork_repo_image" src="https://docs.github.com/assets/cb-34352/mw-1440/images/help/repository/fork-button.webp">

2. Then, clone this repository to your laptop/desktop computer.

`
git clone https://github.com/teddyaroca/fungalecology.git
`

3. Make changes, add, or edit current files and commit those changes to your copy of this 
repository:

| Command | Description |
| :--- | :------------------------------------- |
| `git status` | You should be able to see the changes you made (new files/folders) in red |
| `git add .` | To add all the changes to the current repository |
| `git commit -m "I changed/added x,y,z files"` | To commit those changes back to github |
| `git push` | To push the changes back to your forked repository |

Note: If you are having troubles when you try `git push`, follow [these](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token) instructions to add your personal token in the command line.

4. Once you have pushed your changes, [submit a pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests):

Your changes will be reviewed by the repository owner (teddyaroca or collaborators) and accepted or denied depending on the accuracy/usefulness of the proposed changes.
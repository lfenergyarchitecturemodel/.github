<!--
SPDX-FileCopyrightText: 2017-2022 Contributors to the lfenergyarchitecturemodel project

SPDX-License-Identifier: CC-BY-4.0
-->

# How to Contribute

We'd love to accept your patches and contributions to this project. There are just a few small guidelines you need to follow before making a change.

## Filing bugs and change requests

You can file bugs against and change request for the project via github issues. Consult [GitHub Help](https://docs.github.com/en/free-pro-team@latest/github/managing-your-work-on-github/creating-an-issue) for more information on using github issues.

## Modelling Guidelines
In order to maintain consitency in the model whilst facilitating collaboration and contributions from all parties, a set of modelling guidelines have been created.

### LF Energy Metamodel 
If you wish to contribute to the model, please follow the LF Energy Meta model. 

![Metamodel](https://user-images.githubusercontent.com/3628277/162908393-2bf3f2f6-ff0e-4ae5-a7a5-860b99028293.jpg)

The latest version can be found in [lfenergyfunctionalarchitecturemodel -> Views -> Metamodel](https://lfenergyarchitecturemodel.github.io/lfenergyfunctionalarchitecturemodel/?view=EAID_D62F533C_10E4_423a_9996_336A8012D5EE)

### Contribute using a feature branch
If you wish to contribute to the model, (e.g., Create new diagrams or edits to existing diagrams) please create a new branch from the main model. When your draft is stable, create a pull request to merge your development branch into the master branch. The lfenergy functional architecture team will review the pull request and accept/edit the contribution from the development branch via github.

The lfenergy functional architecture team will review draft branches on a monthly basis and merge them into the master branch.

### Adding a new lfenergy project (X)
Please add a sub-folder for each lfenergy project in the 'Views' folder. (See [OpenSTEF](https://lfenergyarchitecturemodel.github.io/lfenergyfunctionalarchitecturemodel/?view=id-77677b343b234fa0bb0196a8272fc554) as an example).
In this sub-folder, create two diagrams:
- X Detailed. This diagram describes the behavior (functions and data flows) of each lfenergy project.
- X Realized. This diagram relates the lfenergy project to the generic reference archietcure by pointout out which generic functions are realized by the lfenergy project.

Any model object that is specific and exclusively used by a specific LFenergy project should be stored in the folder for that project. If such a folder does not already exist, please create it under the Applications folder (e.g., see the Open STEF folder as an example).

### (Re-) using model objects
When creating diagrams, re-use model objects wherevere possible, to avoid creating duplicate objects for the same concept. Existing  generic model objects are stored in the subfolders of the Application folder:
1. Generic Application Components
2. Generic Application Functions
3. Generic Application Service / Data Exchange Standard
4. Generic data objects

(https://github.com/lfenergyarchitecturemodel/.github/blob/main/images/ApplicationFolderStructure.png)
In #2 you will find the functions, and in #4 you will find the data objects that have been created for generic modelling. Please re-use these wherever possible, and only create a new object if the concept has not already been modelled. Every object must have a definition when it is created in order to help users to understand the meaning of a model object.

## Pull Request Process for maintainers
At this moment contributions from maintainers can be be submitted directly to main branch without submitting a Github pull requests. To prevent merge conflicts, please always refersh the model in Archi before you make any changes. When you ready with your change, please commit your change directly and don't forget to also publish your changes. If you run into a merge conflict, please use the slack channel to align with the other maintainers. 

## Pull Request Process for contributors
Contributions for contributors should be submitted as Github pull requests. See [Creating a pull request](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request) if you're unfamiliar with this concept.

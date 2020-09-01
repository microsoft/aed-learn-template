
# Learn Template

So you want to write Microsoft Learn content for a novice audience? Great! Here is a guide to doing that.

## Module or Learning Path?

Explain module vs learning path briefly and the fact that modules dont have to be in learning paths or could be added to lps

## Target Audience

Talk a bit about the student audience and what we expect

## Requirements

Talk about the general process:
- Do your research:
    - Does this content already exist? What are you bringing new?
    - Will this work on a student account? (not a deal breaker if not, but would be nice)
    - Will this work on Mac and PC? How about browser (with CodeSpaces)?
- Propose to Shana (who is making sure content fits within our existing content)
- Decide on a timeline for project completion
- Decide what you're building (module, lp) 
- Outline it and share with Shana to ensure it is the right size
- Clone this template repo
- Write your content
- Work with Shana to fill in the yml files
- Get someone to review it 
- Deliver the repo to Shana 
- Respond to PR/DevOps requests from Aquent in the Learn repo
- Review the content once it's live
- Participate in a monthly bug bash (if necessary for your content, Shana will let you know)

# Learning Path

So you decided to build a Learning Path! Awesome! Here's what you will need:

## Files

The file structure is fairly straightforward:
LP Folder
  - README.md: Contains the LP title and the Module Titles for quick view
  - index.yml: Contains the outline of the content and the actual titles, descriptions, etc
  - Module Folder (for each module): See Below

# Module

So you want to write a module on it's own or part of a learning path, great! 

## Files

- Module Folder:
    - index.yml: Contains the outline of hte content and the actual titles, descriptions, etc
    - unit.yml (for each unit): Contains the outline of hte content and the actual titles, descriptions, etc
        - Each module should have an introduction.yml and summary.yml file
    - summary.yml: Additionally contains the knowledge check questions (see below)
    - Media Folder
        - README.md: Table containing the file, URL, Date Accesses, and Copyright information if taken from the web for an easy legal review if necessary
        - All images/media to be used throughout the module
    - Includes Folder
        - unit.md (for each unit): Contains the actual content for each unit
        - Each module should have an introduction.md and summary.md file

## Knowledge Check

We recommend having at least 2 knowledge checks per module. Knowledge checks are:
- Multiple choice
- Should actually contribute to learning
- Need to have the correct answer indicated
- Need to have explanations for why each answer is either correct or incorrect

# Getting Started

If you are going to build modules as part of a learning path, we recommend starting from the learning-path-1 folder and deleting the module-1 folder from your repo. Copy the lp1-module-1 folder for each module you want to create and the learning-path-1 folder for each learning path you want to create.

If you are going to build a module on it's own, we recommend starting from the module-1 folder and deleteing the learning-path-1 folder from your repo. Copy the module-1 folder for each module you want to create.

Don't Forget:
- Rename folders and files to match YOUR content. 
- Change the contents of this README to only have the following:


# TITLE THE PROJECT

This repo contains new Microsoft Learn content for....< DESCRIBE YOUR CONTENT >

## Timeline

< TO BE FILLED IN WITH SHANA >

| Item | Owner | Status | Deadline | 
|------|-------|--------|----------|
| Propose content | < YOUR NAME > | Not Started | < DATE > |
| Get content into Learn and with the vendor | @shanama | Not Started | < DATE > |
| Request art assets | @shanama | Not Started | < Date > |
| Write Content | < YOUR NAME > | Not Started | < DATE > |
| Review Content | < YOUR REVIEWER(S) NAME(S) > | Not Started | < DATE > |
| Content to Aquent | < YOUR NAME > | Not Started | < DATE > |
| Content Draft on Learn | Aquent | Not Started | < DATE > |
| Sign off on Content on Learn | < YOUR NAME > | Not Started | < DATE > |
| Publish Content | @shanama | Not Started | < DATE > |
| Review Live Content | < YOUR NAME > | Not Started | < DATE > |

## Content Overview

< Description of content here >

| Type | Title | Description | Duration | 
|------|-------|-------------|----------|
| Learning Path | My LP 1 | This LP is so cool | 30 mins |
| Module | My M1 as part of LP1 | This module is awesome | 10 mins |
| Module | My M2 as part of LP1 | This module is awesome | 10 mins |
| Module | My M2 as part of LP1 | This module is awesome | 10 mins |
| Learning Path | My LP 2 | This LP is so cool | 30 mins |
| Module | My M1 as part of LP2 | This module is awesome | 10 mins |
| Module | My M2 as part of LP2 | This module is awesome | 10 mins |
| Module | My M2 as part of LP2 | This module is awesome | 10 mins |

## Promotion and Marketing

[Link to marketing plan](TBD): Sarah will have a template for this

## Other Information

< Any comments you want to add here, brainstorming, research, etc >


# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

# Legal Notices

Microsoft and any contributors grant you a license to the Microsoft documentation and other content
in this repository under the [Creative Commons Attribution 4.0 International Public License](https://creativecommons.org/licenses/by/4.0/legalcode),
see the [LICENSE](LICENSE) file, and grant you a license to any code in the repository under the [MIT License](https://opensource.org/licenses/MIT), see the
[LICENSE-CODE](LICENSE-CODE) file.

Microsoft, Windows, Microsoft Azure and/or other Microsoft products and services referenced in the documentation
may be either trademarks or registered trademarks of Microsoft in the United States and/or other countries.
The licenses for this project do not grant you rights to use any Microsoft names, logos, or trademarks.
Microsoft's general trademark guidelines can be found at http://go.microsoft.com/fwlink/?LinkID=254653.

Privacy information can be found at https://privacy.microsoft.com/en-us/

Microsoft and any contributors reserve all other rights, whether under their respective copyrights, patents,
or trademarks, whether by implication, estoppel or otherwise.


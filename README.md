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
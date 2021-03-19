
# Learn Template

This repo is designed to help you create and scaffold your Student/Step 0 content for Microsoft Learn.

If you've found this repo, but haven't yet:

1. Read our [Student/Step 0 content strategy doc](https://microsoft-my.sharepoint.com/:w:/g/personal/shanama_microsoft_com1/EWcQMH7tyKNNstzafKABeTwB7TVKhOm5AUoWcBjIvwA3kg?e=zXatFa)
2. Reached out to *TBD (Justin Garrett until determined)*

Please take those steps before starting on your content creation journey.

## Requirements

Talk about the general process:
- Do your research:
    - Does this content already exist? What are you bringing new?
    - Will this work on a student account? (not a deal breaker if not, but would be nice)
    - Will this work on Mac and PC? How about browser (with CodeSpaces)?
- Propose to *TBD (Justin Garrett until determined)* with [these instructions](./module-proposal.md)
- Decide on a timeline for project completion
- Decide what you're building (module, lp) 
- Outline it using [this module design template](./module-design-template.md) and share with Shana to ensure it is the right size and format
- Review the [Learn content requirements](https://review.docs.microsoft.com/en-us/learn-docs/docs/content-requirements?branch=master)
- Clone this template repo
- Write your content
- Work with *TBD (Justin Garrett until determined)* to fill in the yml files
- Get someone to review it 
- Deliver the repo to TBD (Justin Garrett until determined) 
- Respond to PR/DevOps requests from Aquent in the Learn repo
- Review the content once it's live
- Participate in a monthly bug bash (if necessary for your content, *TBD (Justin Garrett until determined)* will let you know)

# Module

So you want to write a module on it's own or part of a learning path, great! 

## Files

- Module Folder:
    - index.yml: Contains the outline of the content and the actual titles, descriptions, etc
    - unit.yml (for each unit): Contains the outline of the content and the actual titles, descriptions, etc
        - Each module should have an introduction.yml and summary.yml file
    - summary.yml: Additionally contains the knowledge check questions (see below)
    - Includes Folder
        - unit.md (for each unit): Contains the actual content for each unit
        - Each module should have an introduction.md and summary.md file

## Knowledge Checks

All modules are **required** to either have at least one knowledge check or at least one hands-on exercise unit that uses the sandbox in some way. Having both is better.

We recommend having at least one knowledge check per module, even if you do have hands-on exercises that use the sandbox. Knowledge checks are:
- Multiple choice (no True/False)
- Don't have "All/None of the above" as an option
- Should actually contribute to learning
- Need to have the correct answer indicated
- Need to have explanations for why each answer is either correct or incorrect
- Are not automatically randomized (so you shouldn't always put the correct answer first, for example)

Knowledge checks can be embedded in a unit or a standalone unit. If embedded, knowledge checks should be 2-3 questions. If standalone, they must be the second-to-last unit in a module and must be 3-5 questions. They should not be combined with the Summary unit, instead they should come right before.

# Learning Path

So you decided to build a Learning Path for your Modules! Awesome!

## Files

Learning paths are defined by a single index.yml file. 

LP Folder
  - index.yml: Contains the title and description for the learning path and the UIDs for all modules included.

# Localization

All of our content will begin localization into the 18 Azure languages ([described here on the Learn GitHub repo](https://review.docs.microsoft.com/en-us/help/contribute/localization-azure-docs?context=/learn-docs/context/lg-context&branch=master)) the date of the English publication. It takes approximately 2 weeks to localize. 

Please check the [Learn GitHub docs](https://review.docs.microsoft.com/en-us/help/contribute/localization-azure-docs?context=/learn-docs/context/lg-context&branch=master) to ensure these are still up to date.

|Locale | Locale Name |
|-------|-------------|
| de-DE | German - Germany |
| es-ES | Spanish - Spain (Traditional Sort) |
| fr-FR | French - France |
| it-IT | Italian - Italy |
| ja-JP | Japanese - Japan |
| ko-KR | Korean - Korea |
| pt-BR | Portuguese - Brazil |
| ru-RU | Russian - Russia |
| zh-CN | Chinese - People's Republic of China |
| zh-TW | Chinese - Taiwan |
| cs-CZ | Czech - Czech Republic |
| pl-PL | Polish - Poland |
| tr-TR | Turkish - Turkey |
| hu-HU | Hungarian - Hungary |
| nl-NL | Dutch - Netherlands |
| pt-PT | Portuguese - Portugal |
| sv-SE | Swedish - Sweden |
| ar-sa | COMING SOON |

# Getting Started

If you are going to build a module on it's own, we recommend starting from the module-1 folder and deleteing the learning-path-1 folder from your repo. Copy the module-1 folder for each module you want to create.

If you are going to build modules as part of a learning path, copy the module-1 folder for each module you want to create and use the learning-path-1 folder for your learning path. Module folders do not live within a Learning Path's folder structure.

*Don't forget to rename folders and files to match YOUR content.*

# Special notes for partnership content

For all future flagship partnership Learning Paths / Modules and select modules created in FY20 or FY21 H1 like CMU Cloud Computing and Oxford Edge AI Engineering, we plan to create a multi-modal learning experience, driving users to Learn, that specifically includes:
- A 2-3 minute video that introduces and gives an overview of the Learning Path / Module available on-demand on Channel 9
- A 15-30 minute video walking through each module available on-demand on Channel9.

We will also create light connective tissue from Learn to these other modalities. e.g.:
- Starting in *TBD*, when the learning path intro videos/images feature is released, flagship partnership Learning Paths will show a short introduction video inline on the Learning Path’s index page.
  - If a video is not (yet) available, we will substitute in a high-quality image provided by the partner.
- Flagship partnership Modules and Learning Paths will include text (**formatted as tip**) indicating that this content is part of a multi-modal learning experience.
- Ensure all partnership content can be localized to all Azure languages listed above. If they cannot, they need to be in a separate folder outside of `student-evangelism`. 

### Learning Path Special Guidance 
Learning path index page intro text will follow this format. See [example here](https://docs.microsoft.com/learn/paths/optimize-basketball-games-with-machine-learning/).
1.	Learning Path title includes partner name (“…inspired by <partner>” or “…in partnership with <partner>”). Note: if author attribution on index pages ships in H2, we will utilize this feature instead. **NOTE: the URL should not contain partner name.**
2.	Inline introduction video (15-30 minute video on Channel 9) supported by the learning path intro videos/images feature 	
3.	Intro text which introduces partnership, including partner-supplied copy and linking to partner website if required, and hints at technical topics covered.
4.	Additional paragraph(s) to explain technical topics covered
5.	Bulleted list of Learning Path objectives (exists, required by Learn)
6.  Connective-tissue text (**formatted as tip**): 
    ```
    > [!TIP]
    > This learning path is part of a multimodal learning experience. Start the first module to see how you can follow along!
    ```
    as described in the previous section.
7.  Copyright information from partnership if necessary.
8.	Bulled list of Prerequisites (exists, required by Learn) 

### Module Special Guidance 
Module index page intro text will follow the same format as the Learning Path index pages with the following exceptions:
- Module title does NOT include partner name, unless relevant to module 
- Module index pages will not contain a video or image (platform constraint)
- Module index page text will briefly re-introduce the partnership, similar to Learning Path
- Connective-tissue text (**formatted as tip**):
  ```
  > [!TIP]
  > This module is part of a multimodal learning experience. Start the module to see how you can follow along!
  ```
  with no link. This is true even if there is one video for multiple modules in a learning path. See [example here](https://docs.microsoft.com/learn/modules/predict-basketball-player-efficiency-ratings/).

Additionally, Module markdown intro and summary files should have the following connective tissue:
- Intro unit:
  ```
  > [!TIP]
  > This module is part of a multimodal learning experience. [Follow along with a video walkthrough of the module](https://URL?azure-portal=true) in a new tab. 
  ```
  Links to a 15-30 minute technical walkthrough video on the Microsoft Developer YouTube Channel. See [example here](https://docs.microsoft.com/learn/modules/predict-basketball-player-efficiency-ratings/1-introduction)
- Summary unit:
  ```
  > [!TIP]
  > Remember, this module is part of a multimodal learning experience. [Follow along with a video walkthrough of the module](https://URL?azure-portal=true) in a new tab.
  ```
  Links to a 15-30 minute technical walkthrough video on the Microsoft Developer YouTube Channel. See [example here](https://docs.microsoft.com/learn/modules/predict-basketball-player-efficiency-ratings/12-summary)


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


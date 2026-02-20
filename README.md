# Presentation

## Description
The goal of this project is to automatically maintain all my public project information easily when I backup my collection of notes.
## Implementation
This is achieved through the  use of a GitHub Actions workflow which run a script to parse through my notes for all the presentably tagged documents. This information is then pulled out by the script and pushed to the respective repositories.

### Steps
1. set up obsidian git to push to my vault repo.
	1. set up personal access key. (done previously)
	2. this will also give me a nice version history for my projects in one location.
2. make github actions workflow parse through /projects and pull out the #presentable documents.
	1. "on push" action which runs the python script. This then Parses the markdown and then a second job to build and push to other repos
	2. #presentable documents have a specific structure where with an attached writeup, mimicking the concept of abstract classes.
3. Output files are made with variable levels of detail depending on which repo they are being bulled to (a brief one for my README, a complex one for my Portfolio).
4. the information put together and the last git actions job to push to the respective repos goes through, the rest is then handled further in [[Portfolio Website]] which takes the project information and displays it appropriately.
### Future changes
- make it so that the skeleton structure has room for hyperlinks that the projects can point towards.
- Make it so that the frontmatter is parseable for a skills tag, which can then be passed along with the project information.
- Make the portfolio portion of the backup scripts
	- make it so that the script produces a md file which is given to the [Portfolio repo](https://github.com/BenHorleyOwen/BenHorleyOwen.github.io) which is then parsed through during the build automation workflow to create the projects html by jekyll
- create a skeleton structure generator obsidian plugin/template for quick initialisation
- differentiate between project tagged presentations such that other significant files like [[Hackathons]] can also be automatically displayed, this would mean i need to change from parsing /projects directly to the entire notes vault, which would impact operation time. 
- the github repo will be a collection of reusable actions and workflows both for the website deployer to call when it is pushed to and for when the notes repo is pushed to

---

# Presentation
## Description
modified a tool which takes full backups of the service I use for journaling and instead made it work by taking partial backups and updating the previously created HTML documents. The modified tool uses the API put up by the service to take the last entry ID when run

---


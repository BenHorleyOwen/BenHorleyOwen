Cyber Security and Digital Forensics graduate with First-Class Honours and a broad foundation; combining security operations, forensic investigation, and software development. All of which I have a passion in pursuing, which presents itself in the many projects I find myself entangled in.
Experienced with SIEM analysis, digital forensic tooling, containerised environments, and secure system design. 
Demonstrated ability to apply security principles through hands-on labs, hackathons, and personal projects. Highly motivated with strong problem-solving and communication skills


The following section is automatically generated from my personal notes as a method of future proofing for whenever I make something new.
## Presentable Projects:

### [incremental journal backup](https://github.com/BenHorleyOwen/Incremental-Journal-Backup)

I modified a tool which takes full backups of the service I use for journaling and instead made it work by taking partial backups and updating the previously created HTML documents. The modified tool uses the API put up by the service to take the last entry ID when run





---

### [Automated Portfolio Deployment](https://github.com/BenHorleyOwen/Automated-portfolio-deployment)

The goal of this project is to automatically maintain all my public project information easily when I backup my collection of notes. 
Project information and indexes containing subprojects can both be displayed, as well as an abstract structure made with OOP to allow for future customisable tagged sections.





---

### [Compose Templates](https://github.com/BenHorleyOwen/Compose-Templates)

this is an index of compose stacks that I have either set up as templates or for quick deploy across my devices. 
Contains a workflow to automatically hyperlink the submodules and any future additions.

- [API Template](https://github.com/BenHorleyOwen/API-template): This project is a quick compose file made during a hackathon to quickly initialise a database and API serving container network on the local network.

- [Node Template](https://github.com/BenHorleyOwen/Node-Template): This compose file mounts a given directory and serves it as a node js web server.

- [Jekyll Host](https://github.com/BenHorleyOwen/Jekyll-Host): This compose file builds a mounted directory and serves the webpage locally. 
This was utilised as a local development environment while i was designing my portfolio webpage.

- [Database Node](https://github.com/BenHorleyOwen/Database-Node): Orchestrates a database and a website API to access it. Repo was designed with an init.sh for fast setup. This project was developed deployed as a submodule for my submissions to [ETHOxford2026](https://github.com/BenHorleyOwen/ETH2026) and [ODI/FRC2026](https://github.com/BenHorleyOwen/ODIFRC-hackathon).





---

### [Maps manhunt](https://github.com/BenHorleyOwen/Map)

A largescale manhunt game made for my friends which runs a containerised NodeJS webserver to maintain a synced map between participants using browser GPS calls to websockets.





---

### [Portfolio Website](https://benhorleyowen.github.io)

webpage deployed on github pages, contains a collection of my projects and skills which is [automatically generated](https://github.com/BenHorleyOwen/Automated-portfolio-deployment) from my personal notes when I back them up. Locally tested with one of my [Compose Templates](https://github.com/BenHorleyOwen/Compose-Templates) as a dev environment.





---

### [Music Index](https://github.com/BenHorleyOwen/Music-Index)

overarching index repo to hold my different music subprojects, I have a lot of different things I like to make pertaining to music.

- [Music Server](https://github.com/BenHorleyOwen/Music-Server): A container stack to automate the ingest of music into my home music server. The stack is made up of Navidrome (server backend), Slskd (for ingest) and beets (for automatic tagging and organisation). This backend architecture is ten further accessed by other projects under my music index through dockers internal network.

- [Robot Karaoke](https://github.com/BenHorleyOwen/Karaoke): personal copycat of [Jbrew's robot karaoke player](https://github.com/jbrew/robot-karaoke-player); "a web player for karaoke songs with procedurally generated replacement lyrics". Modified to interact with my music server as a backend. Currently, the project only works as regular karaoke.





---

### [Gestural Mouse](https://github.com/BenHorleyOwen/Gestural-Mouse)

a fun, small, subproject to control my computer across my room





---

### HomeLab setup

This is a collection of the different services I run at home, links under this category go to the original repositories.

- [Tailscale VPN](https://github.com/tailscale/tailscale): VPN to network my devices together, also allows me to access my services when away from home.

- Dashboard: homelab dashboard which holds connections to each of my other services, routed using tailscale's DNS and docker networks

- [Tandoor](https://github.com/TandoorRecipes/recipes): Recipe archive, accessible on my local network and through my tailscale network.

- [Penpot selfhost](https://github.com/penpot/penpot): I have a local version of Penpot which I intend to extend for a future project.

- [Music Server](https://github.com/BenHorleyOwen/Music-Server): A container stack to automate the ingest of music into my home music server. The stack is made up of Navidrome (server backend), Slskd (for ingest) and beets (for automatic tagging and organisation). This backend architecture is ten further accessed by other projects under my music index through dockers internal network.

- [Obsidian Host](https://github.com/BenHorleyOwen/Obsidian-Server): I created a compose for my home lab which hosts my obsidian notes over my local network.





---

### [Leetcode Automation](https://github.com/BenHorleyOwen/Leetcode-Synchroniser)

This is an implementation of a GitHub action written by dos-m0nk3y to collect leetcode submissions, using a modified version by HoneyHabib for language support.
The automation is used to gather the leetcode challenges I have completed with the accepted submission.





---


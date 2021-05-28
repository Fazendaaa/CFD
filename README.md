<!-- ⚠️ This README has been generated from the file(s) "blueprint.md" ⚠️--><h1 align="center">CFD</h1>

<p align="center">
  <img src="https://raw.githubusercontent.com/Fazendaaa/CFD/master/assets/img/logo.svg" alt="Logo" width="150" height="150" />
</p>

<p align="center">
		<a href="https://saythanks.io/to/lucas.carotta%40outlook.com"><img alt="Say Thanks!" src="https://img.shields.io/badge/Say%20Thanks-!-1EAEDB.svg?longCache=true&style=for-the-badge" height="20"/></a>
<a href="https://golang.org/"><img alt="Made With Go" src="https://img.shields.io/badge/Made%20with-Go-1f425f.svg?style=flat-square" height="20"/></a>
<a href="https://www.docker.com"><img alt="Made With Docker" src="https://img.shields.io/badge/Made%20with-Docker-important?style=flat-square" height="20"/></a>
<a href="https://code.visualstudio.com/"><img alt="Made With VSCode" src="https://img.shields.io/badge/made%20with-vscode-blueviolet?style=flat-square" height="20"/></a>
	</p>


<p align="center">
  <b>Container tooling For Developers</b></br>
  <sub><sub>
</p>

<br />


Welcome to Fazendaaa's CFD. This is version 0.0.0!


[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/water.png)](#idea)

## ➤ Idea

Currently, in the company that I work for we have a CLI (Command Line Interface) made in [Python](https://www.python.org/) called `estat`. As this tool have grown so much and making it available as FOSS (Free and Open-Source Software) was always the idea but the project still in development and not having a properly defined scope, I decided to break its main features in other projects:

- [Succubus](https://github.com/Fazendaaa/Succubus): universal project manager based on cloud-native
- [Jinn](https://github.com/Fazendaaa/Jinn): universal cloud-native project setup tool
- [Baba Yaga](https://github.com/Fazendaaa/BabaYaga): universal cloud-native manager built to expand Jinn and Succubus capabilities
- [Wendigo](https://github.com/Fazendaaa/Wendigo): universal project translator from cloud-native projects to other infra technologies
- [Shōjō](https://github.com/Fazendaaa/Shojo): LaTex package manager
- [Hellhound](github.com/Fazendaaa/Hellhound): VSCode extension to integrate CFD
- [Crocotta](github.com/Fazendaaa/Crocotta): SOC assisted guider
- [Changeling](https://github.com/Fazendaaa/Changeling): Recipes for Succubus and Baba Yaga
- [Rakshasa](https://github.com/Fazendaaa/Rakshasa): CI/CD translator
- [Oni](https://github.com/Fazendaaa/Oni): A CLI tool to unify CFD projects

The tools currently works in Python, [R](https://www.r-project.org/), [Node.js](https://nodejs.org/en/) and [Julia](https://julialang.org/) projects. So far, so good. But the turning point is the following: **I DON'T HAVE ANY OF THOSE LANGUAGES INSTALLED IN MY MACHINE**

All the company projects have a `Dockerfile` in it; so the CLI does the following:

1. Build the current Dockerfile as a helper container
2. Bind the current project to the helper container, installs the mentioned packages in it
3. Adds the packages to the project package description file and truncates its version

You may find the concept it similar as [npm](https://www.npmjs.com/) which this tool is heavily based on.

The main advantage of this approach is to help avoid errors during development, especially because in any project you might find yourself using:

1. A different language version
2. Different Operational Systems (OSes)
3. Forgetting to list all packages used in the project
4. Also forgetting to list OS-based dependencies
5. And also forgetting to list environment variables
6. etc.

The idea is for the development process to be *frictionless*; as all the developers can switch branches and projects and start to work on them without having to worry to install any dependency or figuring out what the other developer did to that project to work.

Besides this, for that matter, this will work as well for other projects based in:

- Python
- Julia
- npm/yarn -- Node.js, Vue, React, etc.
- etc.

As the main idea is to work as a abstraction layer to handle projects the language, its version, and OS related packages should not matter only the what is described in the Dockerfile.

And as npm allows us to run the project and test it so `estat` does it as well. Each project that contains a `docker-compose.yml` file is executed when running a simple `estat run`, avoiding that developers no familiarized with [docker-compose](https://docs.docker.com/compose/) forget to add the `--build` flag to it and, besides that, the tool also goes trough the process of checking each listed image in it for updates as also checking the base image for updates before running it -- sometimes developers forget to check them for updates that might fix their problems.


[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/water.png)](#what-is-cfd)

## ➤ What is CFD?

Container tooling for Developers (CFD) acts just as a *"ground zero"* so you can grasp the whole idea behind the environment in which `estat` flourished upon and then share some possibilities of how those same environments can be linked to your needs right now.

This project will only uses those tools listed here and then acts like platform to publicize it.


[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/water.png)](#author)

## ➤ Author

Only [me](https://github.com/Fazendaaa) because the aforementioned project was implemented by yours only. By knowing each line of that code wrote doing the port would be more easily done this way.


[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/water.png)](#contributing)

## ➤ Contributing

Check more about this in [CONTRIBUTING.md](CONTRIBUTING.md). Here we have a list of some of our contributors:


[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/water.png)](#contributors)

## ➤ Contributors
	

| [<img alt="Fazendaaa" src="https://avatars2.githubusercontent.com/u/12137236?s=460&u=75ec76d6f0c577de2ebfa4eae77cc4c4ad17ec06&v=4" width="100">](https://twitter.com/the_fznd) | [<img alt="You?" src="https://joeschmoe.io/api/v1/random" width="100">](https://github.com/andreasbm/web-config/blob/master/CONTRIBUTING.md) |
|:--------------------------------------------------:|:--------------------------------------------------:|
| [Fazendaaa](https://twitter.com/the_fznd)        | [You?](https://github.com/andreasbm/web-config/blob/master/CONTRIBUTING.md) |



[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/water.png)](#todo)

## ➤ TODO


[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/water.png)](#references)

## ➤ References


[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/water.png)](#license)

## ➤ License
	
Licensed under [AGPL-3.0](https://opensource.org/licenses/AGPL-3.0).

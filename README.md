<!-- ⚠️ This README has been generated from the file(s) "blueprint.md" ⚠️--><h1 align="center">CFD</h1>

<p align="center">
  <img src="https://raw.githubusercontent.com/Fazendaaa/CFD/master/assets/img/logo.svg" alt="Logo" width="150" height="150" />
</p>

<p align="center">
		<a href="https://github.com/badges/shields"><img alt="Custom badge" src="https://img.shields.io/badge/custom-badge-f39f37.svg" height="20"/></a>
<a href="https://saythanks.io/to/lucas.carotta%40outlook.com"><img alt="Say Thanks!" src="https://img.shields.io/badge/Say%20Thanks-!-1EAEDB.svg?longCache=true&style=for-the-badge" height="20"/></a>
<a href=""><img alt="" src="" height="20"/></a>
<a href=""><img alt="" src="" height="20"/></a>
<a href=""><img alt="" src="" height="20"/></a>
<a href=""><img alt="" src="" height="20"/></a>
<a href=""><img alt="" src="" height="20"/></a>
<a href=""><img alt="" src="" height="20"/></a>
	</p>


<p align="center">
  <b>Universal project translator from cloud-native projects to other infra technologies </b></br>
  <sub><sub>
</p>

<br />


Welcome to Fazendaaa's CFD. This is version 0.0.0!

Made with:

- [Go](https://golang.org/)
- [Docker](https://www.docker.com/)


[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/water.png)](#ideia)

## ➤ Ideia

Currently, in the company that I work for we have a CLI (Command Line Interface) made in [Python](https://www.python.org/) called `estat` that you can read more about it right [here](https://github.com/Fazendaaa/Succubus). But one of its features is porting Docker-based projects to other plataforms just like:

- Kubernetes (K8s): through HELM charts
- VM
- Bare metal: throufh ISOs
- etc.

As `estat` have grown so much and making it available as FOSS (Free and open-source software) was always the idea but the project still in development and not having a properly defined scope, I decided to break its main features in other projects:

- [Succubus](https://github.com/Fazendaaa/Succubus): universal package manager based on cloud-native
- [Jinn](https://github.com/Fazendaaa/Jinn): universal project manager built to expand Succubus capabilities
- [Baba Yaga](https://github.com/Fazendaaa/BabaYaga): universal cloud-native manager built to expand Jinn and Succubus capabilities
- [CFD](https://github.com/Fazendaaa/CFD): universal project translator from cloud-native projects to other infra technologies
- [Shōjō](https://github.com/Fazendaaa/): LaTex package manager
- [Hellhound](github.com/Fazendaaa/Hellhound): VSCode extension to integrate Jinn recipes
- [Crocotta](github.com/Fazendaaa/Crocotta): SOC assisted guider


[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/water.png)](#components)

## ➤ Components

### port

```shell
wend port
```


[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/water.png)](#installing)

## ➤ Installing

You don't need to install Go to run this tool, just Docker. And to do so to give it a try, you can do it just by running the following line in your terminal:

```shell
alias wend='docker run -it --volume $(pwd):/project --workdir /project fazenda/CFD'
```

And then running the following to check whether or not is working properly:

```shell
wend --help
```


[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/water.png)](#running)

## ➤ Running


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

# KnizniVypisky.cz

[![Licence](https://img.shields.io/github/license/Ileriayo/markdown-badges?style=for-the-badge)](./LICENSE)
- The app is deployed <a href="https://akela.mendelu.cz/~xastapen/"></b>Here</a><br>
<br>

- KnizniVypisky.cz is a web application that allows users to find information about books and create their own notes.
- It also allows user to group books into collections and generate or manually create tests for books in those
  collections.
- The application is mainly aimed at high school and college students.
- It uses data from Google and gets information about books from **Google Books API**.

## Table of Contents

* [Authors](#authors)
* [Technology stack](#technology-stack)
* [Features](#features)
* [Setup](#setup)
* [Usage](#usage)

## Authors

👤 **Martin Navrátil**<br>
@: <a href="mailto:martinacek.n@gmail.com">martinacek.n@gmail.com</a><br>
@: <a href="mailto:xnavra18@mendelu.cz">xnavra18@.mendelu.cz</a><br>

👤 **Daniil Astapenko**<br>
@: <a href="mailto:xastapen@.mendelu.cz">xastapen@.mendelu.cz</a><br>
@: <a href="mailto:astapenko.daniil.03@gmail.com">astapenko.daniil.03@gmail.com</a><br>

👤 **Petr Chatrný** <br>
@: <a href="mailto:xchatrny@mendelu.cz">xchatrny@mendelu.cz</a><br>

👤 **Lucie Pacáková**<br>
@: <a href="mailto:xpacako1@mendelu.cz">xpacako1@mendelu.cz</a><br>

## Technology stack

| Field       | Technologies                                                                                                                                                                                                                                                                                                                                                                                                                            |
|-------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Environment | <img src="https://img.shields.io/badge/Node%20js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" /> <img src="https://img.shields.io/badge/Yarn-2C8EBB?style=for-the-badge&logo=yarn&logoColor=white" /> <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" />                                                                                                    |
| Backend     | <img src="https://img.shields.io/badge/firebase-ffca28?style=for-the-badge&logo=firebase&logoColor=black"/> <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white" />                                                                                                                                                                                                        |
| Frontend    | <img src="https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D" /> <img src="https://img.shields.io/badge/Vuetify-1867C0?style=for-the-badge&logo=vuetify&logoColor=white" /> <img src="https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E" /> <img src="https://img.shields.io/badge/Webpack-8DD6F9?style=for-the-badge&logo=Webpack&logoColor=white" /> |
| Deployment  | <img src="https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white" /> <img src="https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white" />                                                                                                                                                                                                                       |

## Features

![Use case diagram](docs/usecase-diagram.svg)

## Setup

### Ordinary

```bash
git clone https://github.com/navratilmartin/knizni-vypisky.git
cd knizni-vypisky

yarn install
```

### Docker

```bash
git clone https://github.com/navratilmartin/knizni-vypisky.git
cd knizni-vypisky

docker image build -t knizni-vypisky .
docker run --name knizni-vypisky -p 8080:8080 -d knizni-vypisky
```


## Usage

- `yarn run dev` - starts development Vite server
- `yarn run build` - builds the project and outputs to **./dist** directory
- `yarn run preview` - starts a local web server that serves built code from **./dist** directory (production-like
  preview)

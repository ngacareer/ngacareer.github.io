# TechPrimers Open Source

[![Build Status](https://travis-ci.com/ngacareer/ngacareer.github.io.svg?branch=master)](https://travis-ci.com/ngacareer/ngacareer.github.io)
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/ngacareer/ngacareer.github.io.svg)](https://github.com/ngacareer/ngacareer.github.io/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/ngacareer/ngacareer.github.io.svg)](https://github.com/ngacareer/ngacareer.github.io/network)
[![GitHub issues](https://img.shields.io/github/issues/ngacareer/ngacareer.github.io.svg)](https://github.com/ngacareer/ngacareer.github.io/issues?q=is%3Aissue+is%3Aopen)
[![Contributors](https://img.shields.io/github/contributors/ngacareer/ngacareer.github.io.svg)](https://github.com/ngacareer/ngacareer.github.io/graphs/contributors)

This repository is the source code of https://ngacareer.github.io/public

This repo contains:
- Conferences Links `/content/conferences`
- New Open Source Contributors `/content/contributors`

This is a opensource repository which you can fork.
Raise a Pull Request by adding your name to get featured in https://ngacareer.github.io/public/contributors/

Youtube video on [Hugo Example](https://www.youtube.com/watch?v=yjdJGhV6gbg)

## Contributors

This project exists thanks to all the people who contribute.
<a href="https://github.com/ngacareer/ngacareer.github.io/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=ngacareer/ngacareer.github.io" />
</a>

<i>Made with [contributors-img](https://contributors-img.web.app).</i>

## Online Edit
[![Edit with Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/ngacareer/ngacareer.github.io)

## Checkout
The below steps are for checking out this codebase.
```
git clone https://github.com/ngacareer/ngacareer.github.io.git techprimers-repo
cd techprimers-repo
git submodule init
git submodule update
```

## Add your name
Add your name with a new markdown file under `/content/contributors/` folder along with content similar to `triuhv.md` file.

## Install Hugo
You need [hugo](https://gohugo.io/) to create the Static HTML files based on the markdown files(*.md) which we have created.
Steps for installing hugo can be followed from [here](https://gohugo.io/getting-started/installing/)

## Run the site locally
You can run the site locally and see how the pages are reflected before committing/pushing the code.
```
cd techprimers-repo
hugo serve -D
```
This command will help in Live reloading of website once we update the Markdown files.
The site will be available at [http://localhost:1313](http://localhost:1313)

## Creating final Static files
Run the `hugo` command to create static files under `public/` folder.
```
cd techprimers-repo
hugo
```
Commit the `public` folder along with your markdown file and raise a pull request. -> This process is now automated using [Travis CI](https://travis-ci.com/ngacareer/ngacareer.github.io).

Feel free to just add the `.md` file alone.

## Motivation 
Contribution brings happiness to world!

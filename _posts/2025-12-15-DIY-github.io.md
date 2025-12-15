---
layout: post
title:  wanna DIY *.github.io page?
date:   2025-12-16 00:01:01 +0530
categories: jekyll
---
## sign-up

- <https://github.com/>

## installation

```console
winget install --id Git.Git -e --source winget
winget install RubyInstallerTeam.RubyWithDevKit.{MAJOR}.{MINOR}
gem install jekyll bundler
git init {REPOSITORY-NAME}
cd {REPOSITORY-NAME}
jekyll new --force --skip-bundle .
bundle install
bundle exec jekyll serve
```

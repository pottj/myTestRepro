# My test repository

This is my test repository (sorry for the typo in the name). Here I can test and practise. 

Helpful documentation: 

- [Link to basic md syntax](./docs/index.html).
- [Link to some dummy](./docs/another_test_page.html)

## Test 1: Permanent remove file (26.10.2021)

For my first test, I needed Carls help. I wanted to remove some files, and it did not work initially. He managed to remove the target files ("Musterloesung"). I tried later with another test file ("File3.R"), and it worked, too. No idea what I did differently. 

A line I wrote on my computer in the office. 

## Test 2: create a page for this repository

- create docs subdirectory and an index.md file with simple markdown structure
- create _config.yml next to the repository README.md (highest level!), will need to look something like

```yml
title: Minimal theme
logo: path/to/figure.png
description: Minimal is a theme for GitHub Pages.
theme: jekyll-theme-minimal
```

- go to settings/pages and select github actions - deploy jekyll
- **important**: the readme will always be the start page, but I can use links to get to the other docs!

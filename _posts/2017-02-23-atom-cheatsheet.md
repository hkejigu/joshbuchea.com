---
layout: post
title: Atom Cheatsheet
---

- Edit
  - Move Line Up: `CTRL + CMD + Up`
  - Move Line Down: `CTRL + CMD + Down`
  - Duplicate Lines: `Shift + CMD + D`
- Find
  - Find File: `CMD + P`
  - Select Next: Select text, then `CMD + D`
- Select
  - Split into Lines: `Shift + CMD + L`

## Package Manager

I use the Stars functionality to keep a list of the packages I use:

- Star all installed packages (you will be prompted for an API token from https://atom.io/account): `apm star --installed`
- List starred packages: `apm stars` or `apm starred`
- Install all starred packages: `apm stars --install` or `apm starred --install`

## Snippets

- ALL Selector: `*`
- HTML Selector: `.text.html.basic` (not `.source.html`)
- PHP Selector: `.text.html.php` (not `.source.php`)
- CSS Selector: `.source.css`
- JS Selector: `.source.js`
- Markdown Selector: `.text.md`
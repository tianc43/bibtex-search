# bibsearch [![DroneCI](https://ci.abakus.no/api/badges/ekmartin/bibsearch/status.svg?branch=master)](https://ci.abakus.no/ekmartin/bibsearch)

> Command-line interface for retrieving BibTeX references

![bibsearch](https://i.imgur.com/ARhwzbQ.gif)

Currently uses [ACM's Digital Library](https://dl.acm.org/),
[Google Scholar](https://scholar.google.com/) and
[IEEE Xplore](http://http://ieeexplore.ieee.org/) to find papers, but might
support other sources in the future.

## Installation

bibsearch needs at least version 7.6 of Node.js installed.

```bash
$ npm install --global bibsearch
```

## Usage

```bash
$ bibsearch <query>

Options:
  --source, -s Where to find papers from (default: acm) - valid options: [acm, ieee, google]

Examples:
  $ bibsearch bayou
  $ bibsearch --source google zaharia spark
```

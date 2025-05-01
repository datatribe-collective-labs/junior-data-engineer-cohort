# Read Me:

## How to run website locally:

To run the this website locally, you need to install [Hugo](https://gohugo.io/installation/), and [Go](https://go.dev/doc/install) on your system.

> [!NOTE]
> Go will be installed automatically with Hugo as a requirement.

Clone the repository on your system:

```bash
git clone git@github.com:datatribe-collective/junior-data-engineer-cohort.git
```

To run the server run this bash command:

```bash
hugo server -D
```

Navigate to `localhost:1313/` and you should see the website Hero page.

## Content structure

The contents of the website are stored in the `content/doc/` path. Each folder requires a `_index.md` file with the proper settings to be recognized by Hugo. The template for the setting is the YAML metadata like this:

```yaml
---
weight: 300
title: ""
description: ""
icon: ""
date: ""
lastmod: ""
draft: false
---
```

The template uses [Google icons](https://fonts.google.com/icons).

To find out more about the capabilities of the Lutos Docs template you can visit their [Github ExmpleSite](https://github.com/colinwilson/lotusdocs/tree/release/exampleSite). You can also chekcout [their website](https://lotusdocs.dev/).


---
title: 'SchemaBlocks Repositories'
date: 2019-03-06
layout: default
author: "@mbaudis"
excerpt_separator: <!--more-->
www_link: # a simple web address related to the post, e.g. https://www.ga4gh.org
www_links_formatted:  # one or multiple complete links
#  - '<a href="https://www.biorxiv.org" target="_blank">[biorXiv]</a>'
pdf_file_name: # the name of a PDF (no path) somewhere in "assets", which will be auto-linked
permalink: '/about/repositories.html'
category: # please adjust
  - about
  - howto
tags: # please adjust; see tags -n _config.yml (or extend them there, too)
  - FAQ
  - howto
  - issues
---

## {{ page.title }}

The SchemaBlocks Github organisation contains several specifically scoped 
repositories. Please use the relevant _Github Issues_ to and/or GH pull requests comment and contribute there.

<!--more-->

#### [schemablocks.github.io](https://github.com/ga4gh-schemablocks/ga4gh-schemablocks.github.io)

* website repository
* contains
    - documentation pages (formats, general)
    - representation of schemas ("blocks"), rendered from the code repositories
* [Github issues](https://github.com/ga4gh-schemablocks/ga4gh-schemablocks.github.io/issues) here should address general SchemaBlocks topics and governance, as well as formats documentation

#### [blocks](https://github.com/ga4gh-schemablocks/blocks)

* schema repository
* contains the [source code](https://github.com/ga4gh-schemablocks/blocks/tree/master/src/yaml) as well as rendered representations and example data
* main repository to create code specific pull requests and issues

#### TODO: "implementations"

* example implementations repository
* expected to provide representations and examples of SchemaBlocks use in different projects

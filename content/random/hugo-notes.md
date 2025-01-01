---
title: "Hugo notes"
# weight: 1
# bookFlatSection: false
# bookToc: true
# bookHidden: false
# bookCollapseSection: false
# bookComments: false
# bookSearchExclude: false
---

# Hugo notes

Since setting up these public notes I've been trying to learn hugo. These are the notes I make during.

## Folder structure
* `archetypes` - templates for content files
* `content` - contains all content files i.e. markdown files. The folder structure matters here.
* `data` - stores structues content like JSON, TOML,YAML, CSV
    * These are made available as global variables
* `layouts` - Overrides parts of a theme. This folder contains all customization to themes.
* `themes` - Contains all resources to provide the presentation for the content. Uses Go template language to write themes. 
* `static` - files that need to be hosted, does not fit in any category
    * like fonts, pdf files etc.
* `assets` - unprocessed images, JS/css files
* `resources` - for caching processed assets
* `config` - settings and metadata. Initially is a single file
* `public` - output folder (this is what we host)
* `vendor` & `go.sum` for hugo modules and third party dependencies
* `api` - custom first party apis



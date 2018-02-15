# Personal Blog 

Welcome to visit at: `dulyup.github.io` <br>
Ref https://help.github.com/categories/github-pages-basics/

Overview
---
Write Jekyll-compliant site source code locally, upload it to github, build and host the entire site on Github.

Github Pages
---
GitHub Pages are public web pages for users, organizations, and repositories, that are freely hosted on GitHub’s github.io domain or on a custom domain name of your choice. GitHub Pages are powered by Jekyll behind the scenes, so they’re a great way to host your Jekyll-powered website for free.<br>
Users are allowed to upload webpages written by themselves. The interesting thing is that the upload will happen after the reprocessing of Jekyll programs. 

Jekyll
---
As a Static Website Generator, Jekyll will generate static files based on the web page source. It provides templates, variables, plug-ins and other functions, so in fact can be used to write the entire site. 
Markdown (or Textile), Liquid, HTML & CSS go in. No more databases, comment moderation, or pesky updates to install—just your content.
* Liquid language Ref: https://github.com/shopify/liquid/wiki/liquid-for-designers
* Forum: https://talk.jekyllrb.com

Stucture
---
>_config.yml: Setting files of jekyll

>index.html

>_layouts: Used to store the template file

>>  default.html: Default template 

>posts: Store articles

>>  yyyy-mm--dd-title.html

Details
---
`YAML` Front Matter `---` to mark start and end. No space in front and in the middle of each line.

`gh-pages` is optional, `master` branch also works.If choose to use branch `gh-pages`, make sure there's no parent branch: `$ git checkout --orphan gh-pages`

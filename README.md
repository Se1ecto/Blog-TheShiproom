# Project Name

Blog project for The Shiproom

## Running the Project Locally


Checkout the project and update the submodules to gather the themes:
`git submodule update --init --recursive`

Install Hugo Extended Version [0.149.0+] (Installation guide: [Hugo installation](https://gohugo.io/getting-started/installing/))

To start the site locally, run:
`hugo server`

This will start the Hugo server on http://localhost:1313 with live reload.

## Creating a New Blog Post

To create a new blog post, run:
`hugo new posts/my-new-post.md`

## Building the Site

To build your site with production-ready assets:
`hugo --minify`

## Themes used
https://github.com/adityatelange/hugo-PaperMod/wiki/Installation
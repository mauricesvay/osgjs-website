# OSG.JS Website

# Installation

The website requires Node.js.

* clone the repository
* Install Wintersmith and its Nunjucks plugin : `npm install -g wintersmith wintersmith-nunjucks`

# Editing

Content is in `src/contents`. Each section has its own Markdown file.
The Markdown files can have a header block. The header block starts with `---` and ends with `---`.
The header block is parsed as YAML.

# Preview

To preview the website, simply use:

    ./preview.sh

This will launch a web server on port 8080. Just point your browser to htt://localhost:8080/.

# Build the website

To generate the static HTML files, use:

	./build.sh

Files are generated in the root folder.
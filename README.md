# python-savepage

## Overview

A python script to download an HTML page and any links to images, CSS and javascript.

Features:
* Download images in the HTML page as well as in linked CSS files or embedded CSS.
* Files are stored locally with unique filenames and all references in any HTML and CSS
  are modified.

Limitation:
* Will not download links created by dynamic JavaScript (e.g any JS that calls 
  document.CreateElement("img") will be missed by python-savepage).

## Usage

`savepage.py <url> <outpath>`


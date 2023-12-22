# Semper Prorsum

From students for students.

A website to build plain text notes into a website that can be accessed by students for reference.

This original source was written in the text editor Obsidian, but other editors can easily be used.

## Branches

Git is a system for managing different versions of files on your computer. These files can be kept in "branches," (like of a tree) and edited while being stored in the same Git system. The details for the way this project is structured is below.

 - `source`: Where the plain text notes are stored! These can be compiled on a local computer using the files and settings located in `compiler` and uploaded to the `website` branch, which is then hosted as a website on github pages. You can fork this repository and run your own version of the website.

 - `compiler`: The branch that stores the compiler side of things. you can input the folders to this branch and it will be turned into files that can be used by a website. GitHub Pages is a way to take your local files and host them online that you can share with other people.

  - `website`: The branch that the compiled files from the last two branches resides. This is what GitHub Pages (or your own server) can use and host so that other people can look at it.

This is available under the open source MIT License, so feel free to fork or use the files to make your own website. The can put your own plaintext markdown files into the compiler and output your own website.

## Technical Details

The stack that SP is built on:

 - Abell (Vite): Statically generated for GitHub hosting, convenience, and ease of use. Abell is built on top of Vite, including prop and plugin support.
 - Markdown: Fantastic plain text formatting. Human readable with massive community support. Files can be written by people with very little programming experience. Markdown can also be compiled to HTML and supports the other features here.
 - LaTeX (Mathjax): Math can be tricky to read especially in a typed text format. While LaTeX can be quite tricky and complicated to work with, the result is much more easy to read. LaTeX is the mathematical notation that can be used, Mathjax is the compiler that allows it to be read on the browser.
 - GitHub: GitHub Pages is great because it allows you to host a statically generated site for free. Using the files generated, we can host a website that is readily accessible to others.

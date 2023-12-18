For those curious about this website, for whatever reason.

If you want to skip the boring stuff and know directly how it works, go to the [Technical Details](#Technical-Details).

All of the code for the website is open source! This includes the source note files. Feel free to contribute and help other students on [GitHub](github.com/plexlad/insidetrack).

## Idea (this part is quite boring)

This all started with a text editor known as Obsidian. Obsidian is fantastic because it stores plain text by default. This means that you own all of your data and you can do things with it and customize it to however you prefer it.

Obsidian uses a file format called Markdown by default. Markdown is great because it gives you a file that you can still read on it's own, but there are different ways that it can be shown by software. Anything from big text headers to emphasis with font italics and boldness. Obsidian uses markdown and displays it in the way that you type it.

Markdown happens to also have a large community of programmers that use markdown for a lot of things. This means that you have a lot of features for apps that support markdown. One of these are what you call "site generators," which can actually take your markdown files and create a website using those. I was wondering what would happen if I created a website using my notes (and potentially other people's) from Obsidian.

At this point, my work was cut out for me. 

## Why did I choose what I did?

First off, finding a way to still display complex ideas or functions (math in particular) using Obsidian. Luckily, Obsidian already supports a format called LaTeX, which is used to write math in a text file, that can later be used by a formatter to properly display the "math."

If just went from there! 

## Technical Details

If you just want to skip to this part.

 - Abell (Vite): Abell is a static site generation tool that is used to write inline Javascript code with templates to create a statically generated site. Built on top of Vite, which allows for more features and support.
 - Markdown: A text format that is plain text, human readable, and super extensible with community support. This is just all around my personal favorite. It's easy and works with the other features listed here.
 - LaTeX (Mathjax): A type of format meant to write mathematical notation using text files. Mathjax is a tool that allows it to be ported and used on websites. This makes understanding text based math notes WAY easier. With Markdown's and Mathjax's inline support, it also just made sense.
 - GitHub: GitHub allows you to launch a free statically hosted site with custom DNS support and site protection, so it was the choice I wanted to go with without having to work on extra features. I'm glad that I went with this because the backend is truly hands off and allows me to focus on school.

## Explanation

There is support for fancy math notation (like this: $a=\pi r^2$) on this website! This means that there is much less room for confusion using a notation that does not make any sense for math notes. That math notation is originally written in LaTeX, a format that lets you write complicated math and put it through a renderer, which can display it in different ways.

All of the original notes are written in Markdown. Markdown is extremely easy to work with and has extensive community support. I use the editor Obsidian to write my Markdown. At this point, I just have to run the markdown files through a compiler to make it web friendly.

Abell was my choice for a site generation tool. I honestly just wanted something that could run javascript that was compatible with mathjax. Abell has built in inline javascript, which made my life way easier. Abell is also build on the web framework Vite, which allowed me to use the props and plugin support that Vite provides. Overall, really smooth sailing for static site generation.

GitHub was my place to host of choice because of its accessibility and price! This is also mainly why I went with a static site.
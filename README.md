# Marp Madness
This is a repo to demonstrate the use of marp for slide development


# Overview:

MARP is a toolkit for generating slides from markdown text

# Why Marp:

If we go with Marp or something like it we can manage our courseware as code

# Undecided topics

* Would we include the course code with the slide deck content or would they be separate repos. Probably separate.

# Benefits:

* Ease of versioning
* Ease of contribution
* Can be converted to speach using some tool Mark M mentioned
* Built in Issue reporting and tracking

# Cons

* We each have access to this, feel free to edit and add any negatives that you think or relevant, or of course you can create an issue

# How to use

* Easiest way to edit and verify seems to be to use VSCode along with some plugins to render the slides side by side as you make changes

Slide delimiter is ```---```

Header is ```#```

Level 2 header is ```##```

and so on

Bulletid list is ```*```

New line is two empty lines between lines. 


# Tools I use

I went here and installed the VScode plugin
https://marp.app/#get-started

And the CLI

# How I built the pdf,

I ran this

```marp sample_course.md --pdf --allow-local-files```

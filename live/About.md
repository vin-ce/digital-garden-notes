---
date: 2020-11-10
---

This is my [[D - Digital Garden|digital garden]] that's hooked up to my own note-taking system with [Obsidian](https://obsidian.md/). My computation + design work [lives here](http://vincentli.space/).

While exploring them, there's a few important things to note:

  - I'm always open to discussion! If you want to chat, I'm
	  - [on the bird app (I don't tweet anything though)](https://twitter.com/vincent_yc_li), and you can also find me on 
	  - [arena](https://www.are.na/vincent-li). Email is also great - do so at 
	  - yc (dot) li (dot) vincent (at) gmail (dot) com. 

  - Linked words (such as '[[D - Goal|goals]]') refer to a specific framing of the idea (for example 'goals' refer to a particular model of how they shape everything we interpret, feel, think, do, as well as our [[Teleology MOC|our absolute control and ability]] to shape them).

- In many notes I might make reference to one concept multiple times, but I generally only link it in the first mention.

- In terms of navigation, there's three things:
	1. The bottom of notes have 'Linked References'. They notes that are linked to the current note you're on. 
	2. I sometimes link to a particular section of a note - this does not show up in the hover preview, and so will not show you the relevant snippet.
	3. I selectively upload notes. If you're curious about something that's private, please feel free to message me! I'll see if it's ready to share.

Below exists more detailed stuff.

## Note Types
This describes the note types, listed in a roughly hierarchical manner.

### MOC
Map of Concepts

Two types:
1. 'Book titles' type. Linking together multiple concepts + topics + evergreens. Holistic thought, 'publishable' as article.
2. Topic type. A direct field such as [[0201 Stoicism MOC| stoicism]].

### Evergreens
The notion of Evergreen came from [[Andy Matuschak]]. Have a look [here](https://notes.andymatuschak.org/Evergreen_notes). [[Maggie Appleton]] also made [a great visualization](https://maggieappleton.com/evergreens) of it.

### Type Prefixes
Inspired by [Appleton's page prefixes](https://maggieappleton.com/roam-garden), I've created my own, which you might see crop up from time to time. 

- A - Articles
- B - Books
- C - Courses
- D - Definitions
	- Definitions/ Concepts that aren't quite MOCs
- E - Evergreens



## Technical
This is built on [Gatsby](https://www.gatsbyjs.com/), and is my first project using it. I've thoroughly enjoyed it so far!

I keep these 'published' notes in a folder that nested inside my Obsidian vault. That's pushed to a public git which is then pulled as pages, parsed through various plugins and turned into pages. 

Folder in Obsidian, public git, pulled from there as pages, parsed through custom plugin that turns double bracket links into proper ones. 

For specific details on which plugins I've used, I've linked all of them in this [OneTab page](https://www.one-tab.com/page/gNjdc2tZSZSvyW6AlSP5jQ). 

With the [gatsby-transformer-markdown-reference](https://github.com/mathieudutour/gatsby-digital-garden/tree/master/packages/gatsby-transformer-markdown-references) plugin by Dutour (who's work I also based my own double brackets into links custom plugin off of), there are a few additional tweaks made to get the inbound/ outbound links properly working with Obsidian.

I also created a custom footnote parser that turns it into syntax that [Tufte.css](https://edwardtufte.github.io/tufte-css/) uses.
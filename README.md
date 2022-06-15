<div align="center">

<!-- title -->

<!--lint ignore no-dead-urls-->
# Awesome Dendron

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](https://github.com/dendronhq/awesome-dendron/blob/main/LICENSE)
[![lint](https://github.com/dendronhq/awesome-dendron/actions/workflows/lint.yaml/badge.svg)](https://github.com/dendronhq/awesome-dendron/actions/workflows/lint.yaml)

<!-- subtitle -->

The big list of Dendron docs, talks, tools, examples, articles, extensions, vaults, showcases, and more that the internet has to offer.  

<!-- image -->

<a href="" target="_blank" rel="noopener noreferrer">
  <img src="https://org-dendron-public-assets.s3.amazonaws.com/images/dendron-banner.png" />
</a>

<!-- description -->

[![dendronhq on Twitter](https://img.shields.io/twitter/follow/dendronhq?style=social)](https://link.dendron.so/twitter)
[![Dendron on YouTube](https://img.shields.io/youtube/channel/subscribers/UC8GQLj4KZhN8WcJPiKXtcRQ?style=social)](https://link.dendron.so/youtube)
[![Discord](https://img.shields.io/discord/717965437182410783?color=blueviolet&label=Discord&style=flat-square)](https://link.dendron.so/discord)
![VS Code Installs of Dendron](https://img.shields.io/visual-studio-marketplace/i/dendron.dendron?label=VS%20Code%20Installs%20of%20Dendron&color=blue&style=flat-square)

[Dendron](https://www.dendron.so) is an **open-source, local-first, markdown-based, note-taking tool**. It's a personal knowledge management solution (PKM) built specifically for developers and integrates natively with IDEs like [VS Code](https://code.visualstudio.com/) and [VSCodium](https://vscodium.com/).


</div>


<!-- toc -->

## Contents

- [Dendron Official Public Vaults](#dendron-official-public-vaults)
- [Community Public Vaults](#community-public-vaults)
- [Dendron Official VS Code / VSCodium Extensions](#dendron-official-vs-code--vscodium-extensions)
  - [Archived / Not Recommended](#archived--not-recommended)
- [Community VS Code / VSCodium Extensions](#community-vs-code--vscodium-extensions)
  - [Markdown Enhancers](#markdown-enhancers)
  - [Spellcheck, Linters, and Style Guides](#spellcheck-linters-and-style-guides)
  - [Git](#git)
  - [Vim](#vim)
  - [Coding](#coding)
  - [Other](#other)
- [Dendron Enhancers](#dendron-enhancers)
  - [Migration tools](#migration-tools)
- [Browser Extensions](#browser-extensions)
  - [Web Clippers](#web-clippers)
- [Other awesome lists of interest](#other-awesome-lists-of-interest)
- [Read](#read)
- [Visit and follow](#visit-and-follow)
  - [Dendron Twitter Lists](#dendron-twitter-lists)
  - [Dendron Showcase](#dendron-showcase)

<!-- START content -->

## Dendron Official Public Vaults

> Official public vaults by Dendron. Feel free to use and contribute to them!

- [Dendron Documentation](https://wiki.dendron.so/) - Official user documentation for Dendron ([Source](https://github.com/dendronhq/dendron-site)).
- [Dendron Developer Documentation](https://docs.dendron.so/) - Official developer, code-contributor documentation for Dendron ([Source](https://github.com/dendronhq/dendron-docs)).
- [The Open PKM Catalogue](https://pkm.dendron.so/) - This site is meant to be a reference of all things PKM (Personal knowledge management) ([Source](https://github.com/dendronhq/catalogue-open-pkm)).
- [The Open AWS Catalogue](https://aws.dendron.so/) - This site is meant to be a reference of all things AWS. It is compiled from the [highest quality open sources of information](https://aws.dendron.so/notes/dd5fcf14-9678-4f38-acec-4b8965c8c568.html) available about AWS ([Source](https://github.com/dendronhq/seeds.aws)).
- [TLDR](https://tldr.dendron.so/) - A Dendron vault of the [tldr-pages project](https://tldr.sh/): a collection of community-maintained help pages for command-line tools, that aims to be a simpler, more approachable complement to traditional man pages ([Upstream Source](https://github.com/tldr-pages/tldr) | [Dendron Vault Source](https://github.com/kevinslin/seed-tldr)).
- [Dendron Templates](https://github.com/dendronhq/templates/) - Note templates for Dendron. 
- [Dendron Schema Library](https://github.com/dendronhq/schema-library) - This workspace contains commonly used schemas for Dendron.

## Community Public Vaults

> Public vaults from the Dendron community. Feel free to use and contribute to them!

- [Bassman/dendron-schemas](https://github.com/Bassmann/Dendron-schemas) - Collection of Dendron schema and template files.
- [IntegerMan/LearningLog](https://github.com/IntegerMan/LearningLog) - A collection of highlights of things [Matt Eland](https://matteland.dev/) learned from reading, conferences, and courses as well as lists of resources to investigate.

## Dendron Official VS Code / VSCodium Extensions

> Official extensions by Dendron.

- [Dendron](https://link.dendron.so/vscode) - The official Dendron extension that turns your editor into a personal knowledge management (PKM) tool.
- [Dendron Nightly/Preview](https://marketplace.visualstudio.com/items?itemName=dendron.dendron) - Nightly/preview version of Dendron. Includes the very latest updates, but can introduce instability.
- [Dendron Paste Image](https://marketplace.visualstudio.com/items?itemName=dendron.dendron-paste-image) - Paste images directly into your notes from the clipboard using this fork of [Paste Image](https://marketplace.visualstudio.com/items?itemName=mushan.vscode-paste-image) (supports Dendron-specific features).
- [Dendron Markdown Shortcuts](https://marketplace.visualstudio.com/items?itemName=dendron.dendron-markdown-shortcuts) - Shortcuts for Markdown editing using this fork of [Markdown Shortcuts](https://marketplace.visualstudio.com/items?itemName=mdickin.markdown-shortcuts) (supports Dendron-specific features).
- [Dendron Snippet Maker](https://marketplace.visualstudio.com/items?itemName=dendron.dendron-snippet-maker) - Easily create markdown snippets using this fork of [Easy Snippet Maker](https://github.com/tariky/easy-snippet-maker) (supports Dendron-specific features).

### Archived / Not Recommended

> These official extensions are no longer recommended, or may cause unintended and unexpected behavior, when using Dendron.

- [Dendron Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=dendron.dendron-markdown-preview-enhanced) - Dendron now uses `Dendron: Show Preview`, which comes built-in with Dendron.
- [Dendron Markdown Links](https://marketplace.visualstudio.com/items?itemName=dendron.dendron-markdown-links) - Dendron Markdown Links are now built-in with Dendron.

## Community VS Code / VSCodium Extensions

> Community extensions from the marketplace can potentially have conflicts (settings, shortcuts, etc.) with the official Dendron extensions, leading to unexpected behavior.

### Markdown Enhancers

> Custom shortcuts, renderings, and more for Markdown notes in your editor.

- [Markdown Writer Theme](https://marketplace.visualstudio.com/items?itemName=mgmeyers.markdown-writer-theme) - VS Code theme emphasizing markdown over code.
- [Markdown All-In-One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) - All you need for Markdown (keyboard shortcuts, table of contents, and more).
  - May cause instability or general problems with using VS Code snippets
  - Shortcuts that clash, and may need to be reassigned
    - Toggle heading (downlevel): `Ctrl + Shift + [` || `Dendron: Go Previous Sibling` (`Ctrl + Shift + [`)
    - Toggle heading (uplevel): `Ctrl + Shift + ]` || `Dendron: Go Next Sibling` (`Ctrl + Shift + ]`)
- [Todo+](https://marketplace.visualstudio.com/items?itemName=fabiospampinato.vscode-todo-plus) - Manage todo lists with ease. Powerful, easy to use and customizable.
- [Projects+ Todo+](https://marketplace.visualstudio.com/items?itemName=fabiospampinato.vscode-projects-plus-todo-plus) - Bird's-eye view over your projects, view all your todo files aggregated into one.
- [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree) - Show TODO, FIXME, etc. comment tags in a custom tree view.
- [Excel to Markdown table](https://marketplace.visualstudio.com/items?itemName=csholmq.excel-to-markdown-table) - Converts Excel and Google Docs spreadsheet data to Markdown table formats.
- [Advanced Table Functionality](https://marketplace.visualstudio.com/items?itemName=RomanPeshkov.vscode-text-tables) - Work with text tables without the pain.
- [Markdown Table](https://marketplace.visualstudio.com/items?itemName=TakumiI.markdowntable) - A minimal extension for markdown tables. Add features to edit markdown tables.
- [vscode-reveal](https://marketplace.visualstudio.com/items?itemName=evilz.vscode-reveal) - This extension lets you display a [reveal.js](https://revealjs.com/) presentation directly from an opened markdown document.

### Spellcheck, Linters, and Style Guides

> Enhance your note-taking experience to create higher quality notes and documentation.

- [Spell Right](https://marketplace.visualstudio.com/items?itemName=ban.spellright) - Multilingual, Offline and Lightweight Spellchecker.
  - Will flag `id:` values in YAML frontmatter as misspellings. Fix: `"spellright.ignoreRegExps": ["/id: .*/ig"],`
- [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint) - Markdown/CommonMark linting and style checking for Visual Studio Code.
- [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) - A basic spell checker that works well with camelCase code. The goal of this spell checker is to help catch common spelling errors while keeping the number of false positives low.
- [Write Good Linter](https://marketplace.visualstudio.com/items?itemName=travisthetechie.write-good-linter) - Applies the Write Good Linter to your Markdown, so you can write more good.
- [Vale](https://marketplace.visualstudio.com/items?itemName=errata-ai.vale-server) - The Vale extension for VS Code provides customizable spelling, style, and grammar checking for a variety of markup formats (Markdown, AsciiDoc, reStructuredText, HTML, and DITA).
- [YAML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml) - Validation for YAML files, such as `dendron.yml`.

### Git

> Extensions related to `git` workflows and navigation.

- [Git Automator](https://marketplace.visualstudio.com/items?itemName=ivangabriele.vscode-git-add-and-commit) - One command to commit and push all changes.
- [GitDoc](https://marketplace.visualstudio.com/items?itemName=vsls-contrib.gitdoc) - Automatically commit/push/pull changes on save, so you can edit a Git repo like a multi-file, versioned document.
- [Gitlens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) - Repository/File/Line history and annotations of all your files.
- [GitGraph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph) - View a Git Graph of your repository, and easily perform Git actions from the graph. Configurable to look the way you want.
- [Path AutoComplete](https://github.com/ionutvmi/path-autocomplete) - Path autocomplete for Visual Studio Code.

### Vim

> For [Vim](https://www.vim.org/) and [NeoVim](https://neovim.io/) lovers.

- [VSCode Vim](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim) - VSCodeVim is a Vim emulator with Vim keybindings.
- [VSCode NeoVim](https://marketplace.visualstudio.com/items?itemName=asvetliakov.vscode-neovim) - Neovim is a fork of VIM to allow greater extensibility and integration. This extension uses a full embedded Neovim instance, no more half-complete VIM emulation! VSCode's native functionality is used for insert mode and editor commands, making the best use of both editors.
- [Learn Vim](https://marketplace.visualstudio.com/items?itemName=vintharas.learn-vim) - Learn Vim right within VSCode. Use this extension to learn and practice your Vim skills and become a more awesome developer.

### Coding

> Make use of scripts and code snippets within your workspaces.

- [Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner) - Run code snippets or code files. Multiple languages supported.
- [Auto Run Command](https://marketplace.visualstudio.com/items?itemName=gabrielgrinberg.auto-run-command) - An extension that automatically runs commands after VS Code startup (e.g. `dendron.sync`).

### Other

> The land of of miscellaneous, misfit toys.

- [Macros](https://marketplace.visualstudio.com/items?itemName=geddski.macros) - Automate repetitive actions with custom macros. 
- [Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks) - Bookmark lines within files, and be able to jump directly to them.
- [Vertical Limit](https://marketplace.visualstudio.com/items?itemName=generik.vertical-limit) - Work with multiple cursors and blocks of text.
- [CodeUI](https://marketplace.visualstudio.com/items?itemName=ryanraposo.codeui) - Easier customization of every part of the VSCode UI.
- [Open in Typora](https://marketplace.visualstudio.com/items?itemName=cyberbiont.vscode-open-in-typora) - Open note in Typora.
- [Profile Switcher](https://marketplace.visualstudio.com/items?itemName=aaronpowell.vscode-profile-switcher) - Create different sets of extension profiles.
- [Project Manager](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager) - Easier navigation UX between projects, directories, and workspaces.
- [Open in External App](https://marketplace.visualstudio.com/items?itemName=YuTengjing.open-in-external-app) - When you want to edit your files in Typora, iAWriter or some other tool: helps open files in a different app.
- [Read Time](https://marketplace.visualstudio.com/items?itemName=johnpapa.read-time) - Perfect for writers who want an estimate how for long it may take to read your markdown.
- [Recall](https://marketplace.visualstudio.com/items?itemName=frenya.vscode-recall) - Recall is an extension of Microsoft's Visual Studio Code to help you remember stuff using [spaced repetition](https://en.wikipedia.org/wiki/Spaced_repetition).

## Dendron Enhancers

> Scripts, tools, and repos dedicated to leveling up your Dendron powers.

- [Export and Publish Draw.io Diagrams](https://github.com/LukeCarrier/dendron-publish-drawio) - Use this tool to embed [draw.io / diagrams.net](https://www.diagrams.net/) diagrams in your published Dendron notes and documentation.
- [`dendron-pandoc`](https://github.com/mivanit/dendron-pandoc) - Run specialized [pandoc](https://pandoc.org/) filters for making Dendron links work properly, a script for adding bibliography information (or other data) to all markdown files in a vault, and more.
- [`dendron-citations`](https://github.com/mivanit/dendron-citations) - A tool for converting BibTeX citations to notes, to use them in Dendron.
- [`gibcite`](https://github.com/Maarrk/gibcite) - A small command line tool for getting details of a paper from local [Zotero](https://www.zotero.org/) database (regardless if Zotero is running in the background).

### Migration tools

> Scripts, tools, and repos dedicated to migrating content from other platforms.

- [`joplin2dendron`](https://github.com/chmac/joplin2dendron) - Helper script to copy the correct dates from **Joplin** files into Dendron when migrating.
  1. In Joplin: `File` -> `Export all` -> `MD - Markdown + Front Matter`.
  2. In Dendron: Use the [Markdown Import Pod](https://wiki.dendron.so/notes/f23a6290-2dec-45dc-b616-c218ee53db6b/) to import your notes.
  3. Use `joplin2dendron` to update the Dendron frontmatter timestamps to sync with Joplin source frontmatter.
- [Yarle](https://github.com/akosbalasko/yarle) - Yarle is the ultimate converter of **Evernote** notes to Markdown.
- [OneNote / Office 2016 Markdown Exporter](https://github.com/alxnbl/onenote-md-exporter) - OneNote Md Exporter is a console application running on Windows that exports your **OneNote 2016** notebooks in different markdown formats.
- [OneNote / Office 365 HTML Exporter](https://github.com/sspeiser/onenote-export) - This project exports your **OneNote notes from Microsoft Office 365 (O365)** to a zip file containing HTML files or a Evernote ENEX export file.
- [Google Keep Converter](https://github.com/vHanda/google-keep-exporter) - Convert your **Google Keep** notes into a standard markdown + YAML header format.

## Browser Extensions

> Extensions and add-ons for your favorite web browsers that make note taking, sharing, organizing, and collecting knowledge easier in Dendron workflows.

### Web Clippers

> Tools that help add your online content to your notes.

- [Roam-highlighter](https://chrome.google.com/webstore/detail/roam-highlighter/mcoimieglmhdjdoplhpcmifgplkbfibp) - This extension offers an easy way to highlight text on a web page and import it to note-taking apps like Dendron, Roam Research, Obsidian, Logseq or Notion in the format that best suits your workflow. Open Source! Works on: `Chrome/Chromium` / `Firefox`.
- [Roam Highlighter (alternative to other `Roam-highlighter`)](https://chrome.google.com/webstore/detail/roam-highlighter/hponfflfgcjikmehlcdcnpapicnljkkc) - This extension offers an easy way to highlight text on a web page and import it to note-taking apps like Dendron, Roam Research, Obsidian, Logseq or Notion in the format that best suits your workflow. This one is NOT open source. Works on: `Chrome/Chromium`.
- [MarkDownload - Markdown Web Clipper](https://github.com/deathau/markdownload) - This extension works like a web clipper, but it downloads articles in markdown format. Works on: `Chrome/Chromium` / `Firefox` / `Edge` / `Safari`.
- [Web Clipper](https://chrome.google.com/webstore/detail/web-clipper/mhfbofiokmppgdliakminbgdgcmbhbac) - Another markdown-format web clipper. Universal open source web clipper for Notion, OneNote, Joplin, Yuque,Bear, GitHub and more notes.
- [Convert a Website Table to Markdown](https://tabletomarkdown.com/convert-website-table-to-markdown/) - A website that helps you convert HTML tables from websites into Markdown formatted pipe tables.

## Other awesome lists of interest

> Awesome lists and other collections of topics related to the Dendron stack, or otherwise of interest to dendronites. These may also be candidates for pulling into a future `awesome-list` Dendron vault.

- [The Book of Secret Knowledge](https://github.com/trimstray/the-book-of-secret-knowledge) - A collection of inspiring lists, manuals, cheatsheets, blogs, hacks, one-liners, cli/web tools, and more.
- [Awesome git](https://github.com/dictcp/awesome-git) - A curated list of amazingly awesome Git tools, resources and shiny things.
- [Awesome Shell](https://github.com/alebcay/awesome-shell) - A curated list of awesome command-line frameworks, toolkits, guides and gizmos.
  - [Modern Unix](https://github.com/ibraheemdev/modern-unix) - A collection of modern/faster/saner alternatives to common unix commands. 
- [Awesome VS Code](https://github.com/viatsko/awesome-vscode) - A curated list of delightful Visual Studio Code packages and resources.
- [GitHub Cheat Sheet](https://github.com/tiimgreen/github-cheat-sheet) - A collection of cool hidden and not so hidden features of Git and GitHub.
- [Awesome GitHub Actions](https://github.com/sdras/awesome-actions) - A curated list of awesome things related to GitHub Actions.
- [Awesome TypeScript](https://github.com/dzharii/awesome-typescript) - A collection of awesome TypeScript resources for client-side and server-side development. Write your awesome JavaScript in TypeScript.
- [Awesome Node.js](https://github.com/sindresorhus/awesome-nodejs) - Delightful Node.js packages and resources. 
- [Awesome Electron](https://github.com/sindresorhus/awesome-electron) - Useful resources for creating apps with Electron.
- [Structured Text Tools](https://github.com/dbohdan/structured-text-tools) - The following is a list of text-based file formats and command line tools for manipulating each.
- [Second Brain](https://github.com/KasperZutterman/Second-Brain) - A curated list of awesome Public Zettelkastens / Second Brains / Digital Gardens.
- [Digital Gardeners](https://github.com/MaggieAppleton/digital-gardeners) - This collection of apps, tools and articles is here to help you learn more about digital gardening.

## Read
> Tutorials and writeups of Dendron on the webs

- [It's Not You - It's Your Knowledge Base](https://www.kevinslin.com/notes/e1455752-b052-4212-ac6e-cc054659f2bb) - Original Dendron Manifesto.
- [A Hierarchy First Approach to Note Taking](https://www.kevinslin.com/notes/3dd58f62-fee5-4f93-b9f1-b0f0f59a9b64) - Using hierarchy to manage information overload.
- [The Five Minute Journal with Dendron and Visual Studio Code](https://blog.dendron.so/notes/P1DL2uXHpKUCa7hLiFbFA) - Add some structure to your days using five minute journals (5MJ) schemas, and VSCode.
- [Weekly Reviews in Dendron](https://dev.to/mshiltonj/my-personal-weekly-reviews-in-dendron-3929) - Use dendron for weekly reviews with this schema and template.

## Visit and follow

> People, accounts, and lists to follow online when it comes to apps, tools for thought, personal knowledge management, and other backgrounds of interest.

### Dendron Twitter Lists

> Twitter Lists created, and managed by, Dendron.

- [Mobile Markdown Notes](https://twitter.com/i/lists/1452712294438289422?s=20&t=9JKcKO8S3BY2-DdNZYeQUQ) - Apps mentioned in the Dendron blog article, [Best Mobile Note-Taking Apps for Markdown](https://blog.dendron.so/notes/fDCVPEo3guCFWPdxokXHU/), and other related accounts.
- [PKM / Tools for Thought](https://twitter.com/i/lists/1484255825413619712?s=20&t=9JKcKO8S3BY2-DdNZYeQUQ) - Accounts tweeting about second brains, tools for thought, personal knowledge management (PKM), etc.

### Dendron Showcase

> Websites published with Dendron. These users get the **Planter** [Discord role badges](https://wiki.dendron.so/notes/7c00d606-7b75-4d28-b563-d75f33f8e0d7/), and also have their Discord handles listed.

- [Kevin Lin's Garden](https://www.kevinslin.com/) - Founder of Dendron (`@kevins8#0590`).
- [Mark Hyunik Choi's Cerebrarium](https://cerebrarium.garden/) - Software Engineer at Dendron (`@hikchoi#8934`).
- [Derek Ardolf's Garden (icanteven)](https://icanteven.io/) - Technology Evangelist at Dendron (`@icanteven#0264`).
- [Luke Carrier's Garden](https://luke.carrier.im/) - Software Engineer turned Site Reliability Engineer ( `@lukecarrier#2081`).
- [Ian Jones' Garden](https://garden.ianjones.us/) - Fullstack developer focused on React.JS and Ruby on Rails (`@ianjones#3696`).
- [Kevin Cunningham's Garden](https://garden.kevincunningham.co.uk/) - Developer, educator, instructor, and speaker (`@dolearning (Kevin)#3551`).
- [Cameron Yik's Garden (serendipidata)](https://notes.serendipidata.com/) - Software engineer and dot-collector / dot-connector (`@cameron#9185`).
- [Adam Gluck's Garden (glucknotes)](https://glucknotes.com/) - Computer Science Student interested in cutting edge tools/libraries for software development, data science, and knowledge management (`@glucinater21#0869`).

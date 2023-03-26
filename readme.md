<div align="center">

<!-- title -->

<!--lint ignore no-dead-urls-->

# Awesome org-roam [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<!-- description -->

> Org-roam is a plain-text knowledge management system. It brings some of [Roam's](https://www.roamresearch.com/) more powerful features into the [Org-mode](https://orgmode.org/) ecosystem.

</div>

<!-- TOC -->

## Contents

- [Tools](#tools)
- [Resources](#resources)

<!-- CONTENT -->

## Tools

- [PKMigrator](https://github.com/AnweshGangula/PKMigrator) - Roam Research markdown export to Org Roam files.
- [dendroam](https://github.com/vicrdguez/dendroam) - Attempt of bringing to bring to emacs some [Dendron](https://github.com/dendronhq/dendron) features hand in hand with [Org Roam](https://github.com/org-roam/org-roam).
- [md-roam](https://github.com/nobiot/md-roam) - Use Org-roam with markdown files by adding Md-roam as a plug-in. Mix org and markdown files in a single Org-roam database.
- [org-roam-capture-extension](https://github.com/xiliuya/org-roam-capture-extension) - A Chrome and Firefox extension facilitating org-capture in emacs.
- [org-roam-ql](https://github.com/ahmed-shariff/org-roam-ql) - An org-ql interface for org-roam.
- [citar-org-roam](https://github.com/emacs-citar/citar-org-roam) - An emacs package to provide tighter Citar and Org-Roam integration.
- [org-similarity](https://github.com/brunoarine/org-similarity) - A package to help Emacs org-mode users discover similar or related files. Under the hood, it uses Python and scikit-learn for text feature extraction, and nltk for text pre-processing.
- [org-roam-search](https://github.com/natask/org-roam-search) - Org-ql like search for org-roam. depends on the following packages not yet on melpa. 
- [consult-org-roam](https://github.com/jgru/consult-org-roam) - A collection of functions to operate org-roam with the help of consult and its live preview feature. You can use it to search, filter and find notes, preview backlinks as well as forward links, and sift through currently open org-roam buffers.
- [Zetteldesk.el](https://github.com/Vidianos-Giannitsis/zetteldesk.el) - Zetteldesk.el is an emacs library built on top of org-roam with the purpose of easier revision on various subjects and a better outliner tool for emacs.
- [org-roam-bibtex](https://github.com/org-roam/org-roam-bibtex) - Org Roam integration with bibliography management software.
- [nursery](https://github.com/chrisbarrett/nursery) - "This is a repository for Emacs Lisp packages that I think could be useful for friends and coworkers. It’s an experimental, low-pressure space for me just to hack on Lisp with the garage door open."
    -  [org-roam-review](https://github.com/chrisbarrett/nursery/blob/main/lisp/org-roam-review.el) _(incubating)_ - Implements a system for managing [Evergreen Notes](https://maggieappleton.com/evergreens) on top of org-roam. Provides a spaced-repetition system that prompts you to review notes or revisit stubs and help them grow to maturity.
    -  [org-roam-dblocks](https://github.com/chrisbarrett/nursery/blob/main/lisp/org-roam-dblocks.el) _(incubating)_ - Add org dynamic blocks that implement “canned searches” for org-roam. You can search for notes or list backlinks, then do additional filtering based on title or tags.
    -  [org-roam-search](https://github.com/chrisbarrett/nursery/blob/main/lisp/org-roam-search.el) _(incubating)_ - Search your org-roam files for a string and display a buffer of results. Results are shown with collapsible previews, like in the org-roam buffer.
    -  [org-roam-links](https://github.com/chrisbarrett/nursery/blob/main/lisp/org-roam-links.el) _(incubating)_ - Display a tree of backlinks _and_ forward links up to a configurable depth. Useful for looking for unexpected connections without busting open a full-fledged graph UI. Contrasts with the normal org-roam buffer, which only shows backlinks.
    -  [org-roam-consult](https://github.com/chrisbarrett/nursery/blob/main/lisp/org-roam-consult.el) _(incubating)_ - A version of `consult-ripgrep` that shows node titles instead of filenames so you don’t have to guess anymore.
    -  [org-roam-slipbox](https://github.com/chrisbarrett/nursery/blob/main/lisp/org-roam-slipbox.el) (_incubating_) Automatically tag nodes according to the name of the directory they’re in, and easily refile between these directories.
    -  [org-roam-gc](https://github.com/chrisbarrett/nursery/blob/main/lisp/org-roam-gc.el) _(spike)_ - Automatically delete empty dailies files so they don’t build up forever.
    -  [org-roam-rewrite](https://github.com/chrisbarrett/nursery/blob/main/lisp/org-roam-rewrite.el) _(spike)_ - Commands for renaming nodes, rewriting links and deleting nodes with redirection so you can refactor notes without leaving broken links.
    -  [timekeep](https://github.com/chrisbarrett/nursery/blob/main/lisp/timekeep.el) _(spike)_ - Provides a structured way to use org-roam for representing multiple clients/employers. It provides a simple clocking interface built on org-clock and provides integrations with org-capture.
    -  [org-roam-refill-previews](https://github.com/chrisbarrett/nursery/blob/main/lisp/org-roam-refill-previews.el) _(spike)_ - Refill previews in the backlinks buffer so they fit the window.
    -  [org-roam-lazy-previews](https://github.com/chrisbarrett/nursery/blob/main/lisp/org-roam-lazy-previews.el) _(spike)_ - Compute previews lazily for much better performance in buffers with many backlinks or reflinks.
    -  [org-format](https://github.com/chrisbarrett/nursery/blob/main/lisp/org-format.el) (_spike_) - Formatter for org-mode files to ensure consistency.
- [org-roam-timestamps](https://github.com/tefkah/org-roam-timestamps) - Add modified and creation timestamps to the org-roam property drawer.

## Resources

- [Getting Started with Org Roam - Build a Second Brain in Emacs](https://www.youtube.com/watch?v=AyhPmypHDEw) - [David Wilson](https://github.com/daviwil) of [System Crafters](https://www.youtube.com/c/SystemCrafters) has produced an introductory video that covers the basic commands.
- [Taking Notes with Emacs Org Mode and Org-Roam](https://lucidmanager.org/productivity/taking-notes-with-emacs-org-mode-and-org-roam/).
- [Taking org-roam everywhere with logseq](https://coredumped.dev/2021/05/26/taking-org-roam-everywhere-with-logseq/) - A way (with elisp script) to make Org-roam work with Logseq for mobile app experience.
- [Dominik Honnef's Org-roam based workflow for taking notes and writing articles](https://honnef.co/articles/my-org-roam-workflows-for-taking-notes-and-writing-articles/) - A very thorough and complex system that captures notes, articles that he reads on the web, articles for his blog, and miscellaneous notes as they occur to him. The system automatically maintains a bibliography and can massage a note intended for his blog to make it compatible with Hugo, which he uses to publish his blog.
- [Using Org-roam as a CRM](https://www.youtube.com/watch?v=DteN5uBV5ts) - A makeshift personal CRM setup in Org-roam.
- [(EmacsConf 2020) Org-roam: Presentation, Demonstration, and What’s on the Horizon](https://emacsconf.org/2020/schedule/16).
- [(EmacsConf 2020) Org-mode and Org-Roam for Scholars and Researchers](https://emacsconf.org/2020/schedule/17).
- [(EmacsConf 2020) Org-roam: Technical Presentation](https://emacsconf.org/2020/schedule/18).
- [Zettelkasten, Emacs, and Creative Thinking](https://www.alexkehayias.com/essays/zettelkasten-setup/) - A walkthrough of note taking practice using Emacs, org-roam, hugo, Working Copy, and GitHub Actions.
- [(EmacsConf 2022) Writing and organizing literature notes for scientific writing](https://emacsconf.org/2022/talks/science/) - Using Emacs and org-mode for managing bibliography with ivy-bibtex, writing literature notes using org-noter and organizing them in a Zettelkasten system built with org-roam using zetteldesk.

<!-- END CONTENT -->

## Contributing

[Contributions of any kind welcome, just follow the guidelines](contributing.md)!


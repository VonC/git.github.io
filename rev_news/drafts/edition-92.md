---
title: Git Rev News Edition 92 (October 26th, 2022)
layout: default
date: 2022-10-26 12:06:51 +0100
author: chriscool
categories: [news]
navbar: false
---

## Git Rev News: Edition 92 (October 26th, 2022)

Welcome to the 92nd edition of [Git Rev News](https://git.github.io/rev_news/rev_news/),
a digest of all things Git. For our goals, the archives, the way we work, and how to contribute or to
subscribe, see [the Git Rev News page](https://git.github.io/rev_news/rev_news/) on [git.github.io](http://git.github.io).

This edition covers what happened during the month of October 2022.

## Discussions

<!---
### General
-->

<!---
### Reviews
-->

<!---
### Support
-->

<!---
## Developer Spotlight:
-->

## Releases

+ Tower for Windows [4.0](https://www.git-tower.com/release-notes/windows?show_tab=release-notes) ([blog post](https://www.git-tower.com/blog/tower-windows-4/))


## Other News

__Events__

+ The recorded talks of GitMerge 2022 [are now live](https://www.youtube.com/playlist?list=PL0lo9MOBetEGEAs1D28ExRQONnX-uZ3Wf).
+ The summary of GitMerge 2022 can be found in the
  [Git Merge 2022 – that’s a wrap!](https://github.blog/2022-10-21-git-merge-2022-mission-report/)
  blog post by Lee Reilly on the GitHub Blog.


__Various__

+ [Git security vulnerabilities announced](https://github.blog/2022-10-18-git-security-vulnerabilities-announced/)
  (CVE-2022-39253, and CVE-2022-39260) that affect Git's [`--local` clone optimization](https://git-scm.com/docs/git-clone#Documentation/git-clone.txt---local)
  (important when cloning with `--recurse-submodules` from untrusted repositories)
  and [`git shell`'s interactive command mode](https://git-scm.com/docs/git-shell#_interactive_useA).
  Fixed in Git 2.38.1.
+ [Highlights from Git 2.38](https://github.blog/2022-10-03-highlights-from-git-2-38/)
  by Taylor Blau on GitHub Blog.<br>
  See also [Git 2.38 Adds Microsoft's "Scalar" Repository Management Tool](https://www.phoronix.com/news/Git-2.38-Released)
  by Michael Larabel on Phoronix.
+ [Cybernews research team discovered millions of `.git` folders exposed to public](https://cybernews.com/security/millions-git-folders-exposed/).
+ A [Code Review Handbook](https://www.sledgeworx.io/code-review-handbook/) published by Sledgeworx Software.


__Light reading__

+ [Setting Up GPG on Windows (The Easy Way)](https://www.git-tower.com/blog/setting-up-gpg-windows/) by Bruno Brito on Tower’s blog.
+ [Our Favorite Tower Features](https://blog.kaleidoscope.app/2022/10/18/our-l33t-tower-features/) by Florian Albrecht on Kaleidoscope's blog.
+ [The Story of Scalar](https://github.blog/2022-10-13-the-story-of-scalar/)
  by Derrick Stolee and Victoria Dye on GitHub Blog.
+ Literally the smallest changeset possible created:
  [Fix: remove a ZERO WIDTH NO-BREAK SPACE in front of an inline literal](https://github.com/spyder-ide/spyder-docs/pull/332).
+ [VS Code "Timeline" feature — Your local version control system](https://www.amitmerchant.com/vs-code-timeline-your-local-version-control-system/)
  by Amit Merchant.
+ [Turn around your Git mistakes in 17 ways](https://dev.to/smitterhane/turn-around-your-git-mistakes-in-17-ways-2mn1)
  by Smitter hane on DEV\.to.
+ [GitHub's Missing Merge Option](https://tylercipriani.com/blog/2022/09/30/githubs-missing-merge-option/)
  by Tyler Cipriani, and the conflict between
  team “git log should be clean” vs. team “git log should have an accurate history.”

<!---
__Easy watching__
-->

__Git tools and sites__

+ [`focus`](https://github.com/twitter/focus) is a tool to manage
  [Git sparse checkouts](https://github.blog/2020-01-17-bring-your-monorepo-down-to-size-with-sparse-checkout/)
  derived from the [Bazel](https://bazel.build/) build graph.
+ Goblet is a Git proxy server that caches repositories for read access,
  which is intended to be used as a library.
  Created at Google as 20% project (with glue code for googlesource.com)
  as [google/goblet](https://github.com/google/goblet),
  and also used in a modified form at Canva
  as [canva-public/goblet](https://github.com/canva-public/goblet).
+ A different [Goblet](https://pythonhosted.org/goblet/)
  _was_ time ago a web frontend for Git repositories in Python,
  using libgit2 and Flask; [seveas/goblet](https://github.com/seveas/goblet)
  repository was archived by the owner.
+ [`nb`](https://xwmx.github.io/nb/) is a command line and local web
  note-taking, bookmarking, archiving, and knowledge base application
  with Git-backed versioning and syncing.
+ [Git Reference](http://git.github.io/git-reference/) site is meant to be a
  quick reference for learning and remembering the most important and commonly
  used Git commands, but it can also be used as a tutorial. Every page will also
  link to more in-depth Git documentation.
+ [email + git = <3: Learn to use email with git!](https://git-send-email.io/)
  is a guide to contributing to email-driven projects like the Linux kernel, PostgreSQL, or Git.
  Covers various operating systems and distributions.


## Credits

This edition of Git Rev News was curated by
Christian Couder &lt;<christian.couder@gmail.com>&gt;,
Jakub Narębski &lt;<jnareb@gmail.com>&gt;,
Markus Jansen &lt;<mja@jansen-preisler.de>&gt; and
Kaartic Sivaraam &lt;<kaartic.sivaraam@gmail.com>&gt;
with help from Johannes Schindelin.
---
layout: default
title: Developers
published: true
---

<p class="text-center">
   <a class="btn" href="https://github.com/cwi-swat/rascal"><i class="icon-github"></i> Source code </a>
   <a class="btn" href="https://github.com/cwi-swat/rascal/issues/"><i class="icon-tasks"></i> Report issues</a>
   <a class="btn" href="https://github.com/cwi-swat/rascal/wiki/Rascal-Developers-Setup---Step-by-Step"><i class="icon-info-sign"></i> Develop instructions</a>
</p>

This page is intended for developers contributing to the source code of the Rascal  implementation  itself, rather than programmers that use Rascal.

## Library contributions

We solicit for Rascal library contributions. Examples are bindings
for version repository systems and bug databases, or front-ends for programming
   languages and domain specific languages. Please [contact us](mailto:Jurgen.Vinju@cwi.nl) if you are
   interested. 

## Enhancements, bugs and patches

We welcome feedback. Please use [GitHub issues](https://github.com/cwi-swat/rascal/issues) 
to submit your contributions such as pull requests, bug reports and suggestions for enhancement. Thanks! 

## Source access

Rascal is completely hosted on GitHub, [under the cwi-swat repositories](https://github.com/organizations/cwi-swat).
See our [developer setup](https://github.com/cwi-swat/rascal/wiki/Rascal-Developers-Setup---Step-by-Step)
instructions on which projects to checkout and dependencies to install.

## Continuous integration

* Please find our [Jenkins](http://jenkins-ci.org) installation running at <http://build.rascal-mpl.org>.
* The continuous update site is deployed at `http://update.rascal-mpl.org/unstable`. Every time a contribution is pushed to GitHub, and all tests succeed, the unstable update site is build and deployed fully automatically.
* We also publish a unstable version of the [command line REPL](http://update.rascal-mpl.org/console/rascal-shell-unstable.jar)
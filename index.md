# Welcome to SUSE for java devs!

## Philosophy

The \*SUSE way is to avoid vendor lock-in, and leverage freely available standards where possible.

This project is following the same guidelines, and you will basically see how to migrate from your proprietary systems, towards freely available solutions based on the latest standards.

The git repo will contain tools to build your own environments on SUSE based distros.

## Disclaimer

SUSE SLES product supports tomcat. If you only need tomcat, you might not need to check further, and just use SLES.
SUSE CAP (CloudFoundry+Kubernetes) product has an official java buildpack too.

This repository takes a different approach: "What can we build together, as a community (and therefore not supported by SUSE), to have a different kind of working JAVA environments on \*SUSE based distros?".

This repository should also resolve the pain points of migrating from proprietary systems towards open, freely available ones.

## Repository contents

* Docs and learning experiences
* Migration tooling from * towards tomEE (tomcat + JakartaEE)
* How to build your own packages/containers with intermediary solutions, which might be helping on the migration (Wildfly).
* How to use tomcat/tomEE/Spring on SUSE based distros and products

# SUSE for JBoss users

# SUSE for Weblogic users

# SUSE for Websphere users

# SUSE for Glassfish users

# SUSE for TomEE users

# SUSE for Spring users

### How to contribute to this project

You can contribute to documentation, or to code (packaging, migration tooling, ...).
The code for the migration tooling is in master branch, while the documentation is in the gh-pages branch.

### How to contribute to this documentation

You can fork this repo, and use the [editor on GitHub](https://github.com/evrardjp/suse-for-java-devs/edit/gh-pages/index.md) to maintain and preview the content.

Alternatively, you can build you own environment with Jekyll: GitHub Pages runs [Jekyll](https://jekyllrb.com/) to rebuild the pages of this site, from the content of the Markdown files.

# Git Contributing Guide

This repository contains the Git, GitHub, and GitLab documentation in AsciiDoc format.

AsciiDoc is a plain text documentation syntax, also known as a mark-up language, for text files. AsciiDoc is rendered as HTML automatically by web browsers, so the files can be viewed as formatted text via the GitLab
repository URL.

## Development

For active maintenance/development of the HACBS documentation, developers
should create a [fork](https://github.com/Trivedi-Gaurav/git-content#creating-a-fork) of the Git repository. Updates are performed in the forked repository and, when changes are ready for review, submitted as pull request to the upstream reposiory. Contributers are encouraged to create task specific branches in their forked repositories, but pull request should always target the default branch of the
[Git repository](https://github.com/Trivedi-Gaurav/git-content).

### Rendering Individual Pages

To render individual AsciiDoc pages for review, use the `asciidoctor` software to generate HTML files.
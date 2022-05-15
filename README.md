# Git for technical writers

This repository is the source code of the Git for technical writers blog. I've used Antora framework to display the content for this blog.

## To generate output

<ol>
  <li>Clone this repo.</li>
  <li>Set up Antora on your [system](https://docs.antora.org/antora/latest/install-and-run-quickstart).</li>
  <li>Run the following command on your terminal: `npx antora --fetch antora-playbook.yml`. </li>
</ol>

> To publish your documentation by using GitLab pages you need to setup a CI pipeline.

> To publish your documentation by using GitHub pages you need to upload the output (the build folder) in a [blank repository](https://github.com/Trivedi-Gaurav/git.io).

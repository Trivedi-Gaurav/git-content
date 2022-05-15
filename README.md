# HACBS documentation

Hybrid Application Console Build Services (HACBS) is an effort to automate
build and delivery of Red Hat products. With HACBS, you have access to single, simple workflow for developing, testing, and releasing containerized applications while ensuring compliance with enterprise security standards.

## HACBS documentation links

* [Getting-Started Guide](https://red-hat-hybrid-application-cloud-build-services-documentation.pages.redhat.com/hacbs-documentation/users/getting_started.html)
* [User Documentation](https://red-hat-hybrid-application-cloud-build-services-documentation.pages.redhat.com/hacbs-documentation/users/index.html/120v38DZY6iuHlnyJJ2_k78vwhNiA38LqIZIzTT9j8aM)
* [Developer Documentation](https://red-hat-hybrid-application-cloud-build-services-documentation.pages.redhat.com/hacbs-documentation/developers/index.html)
* [Schema Documentation](https://red-hat-hybrid-application-cloud-build-services-documentation.pages.redhat.com/hacbs-documentation/schema/index.html)
* [Architecture Overview](https://red-hat-hybrid-application-cloud-build-services-documentation.pages.redhat.com/hacbs-documentation/architecture/index.html)

## External Links

* [Hybrid Application Console (Confluence)](https://docs.engineering.redhat.com/pages/viewpage.action?pageId=256849149)
* [HACBS Project Status Dashboard](https://docs.google.com/document/d/1wzJu-wOYez5p875kl0QkgQ6b2i9x_T9983YdxTxBd-I/edit?usp=sharing)

## HACBS Contact Information

* [HACBS Documentation Home Page](https://red-hat-hybrid-application-cloud-build-services-documentation.pages.redhat.com/hacbs-documentation/)
* [HACBS Documentation GitLab Repository](https://gitlab.cee.redhat.com/red-hat-hybrid-application-cloud-build-services-documentation/hacbs-documentation)
* [Email: HACBS Development Team](mailto:hacbs@googlegroups.com)
* [Google chat: HACBS Users](https://groups.google.com/g/hacbs)

## Notes

This README file follows the content and syntax conventions defined in the
Systems Design and Engineering Continuous Integration Git Repository README
File Guide (The Source):
- https://source.redhat.com/groups/public/systems-design-and-engineering/continuousintegration/continuous_integration_wiki/xci_git_repository_readme_file


## References for documentation team

* We used AsciiDoc to document HACBS (https://docs.asciidoctor.org/asciidoc/latest/#about-asciidoc).
* We created this website using Antora (https://docs.antora.org/antora/latest/). We use Antora because it provides a search capability that we can customize.
* We manage documentation in GitLab. They are in a repository (<https://gitlab.cee.redhat.com/red-hat-hybrid-application-cloud-build-services-documentation/hacbs-documentation>). We use GitLab to manage publication - continuous integration settings in the repository automatically generate the web site when changes are merged and GitLab Pages is used to publish the website here <https://red-hat-hybrid-application-cloud-build-services-documentation.pages.redhat.com/hacbs-documentation/>.

### To generate output

* On your system: After setup (to set up follow reference information) run the following command on your terminal: `npx antora --fetch antora-playbook.yml`

* Merge you changes and refresh the HACBS documentation link, which is, <https://red-hat-hybrid-application-cloud-build-services-documentation.pages.redhat.com/hacbs-documentation/>

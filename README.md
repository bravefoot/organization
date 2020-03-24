# Helpful Engineers GitHub Organization

## Structure
* organization: top-level issue tracking, wiki, and organization management.
* proposals/[resources](https://github.com/helpfulengineering/resources), project proposals in its early stages.
* project-\*: individual project repositories. 

## Contributing

**If you want to add a repository, please open an issue or reach out us on the Slack [#skill-software-devops](https://helpfulengineering.slack.com/archives/CV54M16QH) channel.**

## Kinds of repository

### Organization specific
* Creation policy: we should embrace the Unix philosophy of «do one thing and do it well» to segment the organization needs into concisely scoped repositories.

* Naming: these repositories should be named in a consistent way (kebab-case) and, ideally, share a common prefix like (organization).

* Access privileges: this has to be discussed, please refer to the «owner and member policy» section below.

* Quirks: the most important repositories can be pinned so they are easy to find.

* Teams: People can be added to teams they work on, and be added to skills. This way, specific skill sets can be tagged in issues and pull requests across projects and across the organization.

### Project specific
* Creation policy: there should be a maximum of one repository by project (a soft limit to keep things sane), and a minimum of zero, as we shouldn’t be creating repositories for projects that don’t need one or are using other tools and don’t want to migrate.

* Naming: repository names should match the Slack channels they are affiliated with where possible (i.e. Slack channel #project-awesome-thing would yield project-awesome-thing). 

* Access privileges: each project will designate a few users, covering different time zones whenever possible, that will have triage-level access to the project repository.

## Classifying repositories

### Recommended tags

1. Contents: `hardware` `software` `documentation` `graphics` `data`
2. Type: `project` `organization` `tool`
3. Name: `big-thing` for a repository named *project-big-thing*.

*Note: adding also the `covid-19` tag visibilizes the repositories on the global GitHub scope and, hopefully, will bring more skilled collaborators to Helpful Engineering.*
  
## Guide for licensing a new project

>Hi Everyone, _Please follow this guide if you do not already have an open source license on your work. If you have one, please leave the one you have in place._
>
>**Licensing Guide**  
>
>Thank you for your patience whilst we prepared a guide for open source licensing. The scale and severity of this global pandemic is a test our ability as a species to come together and support one another. As a result, we have a strong open source mantra here at Helpful Engineering.  
>
>In order to help everyone license their work properly, make it clear that it can be reused, and offer everyone a bit more protection, we have released this recommended licensing guide.Considering the huge uncertainties in how society will respond to the COVID-19 pandemic, we have decided to use permissive licenses where at all possible. This is founded on a desire to collaborate with established manufacturers and technology companies in order to create the best responses we can.We have kindly used [Safecast's licensing structure for inspiration](https://slack-redir.net/link?url=https%3A%2F%2Fsafecast.org%2Fabout%2Flicenses%2F&v=3) and content. We also believe that there is a chance large manufacturing or technology companies may wish to pick up our designs in this moment of crises. On this basis, we are recommending permissive licenses for you to use.
>
>**Hardware Projects**  
>
>Everything needed or used to design, make, test or prepare the Medical Hardware or other Contributions  to be made or distributed whether hardware designs, software, schematics or anything else is licensed under the [CERN 2.0 Permissive licence](https://slack-redir.net/link?url=https%3A%2F%2Fohwr.org%2Fproject%2Fcernohl%2Fwikis%2FDocuments%2FCERN-OHL-version-2&v=3) (CERN-OHL-P). That includes both firmware and any software that normally comes with the  hardware or other item as well as software used to test it. We recommend placing a TXT file in the root of the repository, by the repository owner, with this license in it.
>
> **Software Projects**  
>
> Software that is not necessary for the functioning of the hardware but may be loaded onto it, or be used by another device to communicate with it is licensed under the permissive [Blue Oak License 1.0.0](https://slack-redir.net/link?url=https%3A%2F%2Fblueoakcouncil.org%2Flicense%2F1.0.0&v=3) unless another open source license is used. We recommend placing a TXT file in the root of the repository, by the repository owner, with this license in it.
>
> **Guides, instructional videos, and other materials**  
>
> Accompanying materials such as instruction manuals, videos and other copyrightable works that are useful for but not necessary to design, make, test or prepare the Medical Hardware for distribution should be published under a [Creative Commons Attribution 4.0](https://slack-redir.net/link?url=https%3A%2F%2Fcreativecommons.org%2Flicenses%2Fby%2F4.0%2F&v=3) License. A reference to this license should be included at the bottom of vital documents, and we recommend the following:  
>
> > _All copyrightable materials  other than software, and everything needed to design, make, test and prepare the hardware for distribution, such as instructional videos and manuals, are published under a_ [Creative Commons Attribution 4.0](https://slack-redir.net/link?url=https%3A%2F%2Fcreativecommons.org%2Flicenses%2Fby%2F4.0%2F&v=3) _License._
>
> As a follow up, we will be asking all contributors to acknowledge that their designs are open source.

**Source: [https://helpfulengineering.slack.com/archives/C010GJ68R1N/p1584974903050100](https://helpfulengineering.slack.com/archives/C010GJ68R1N/p1584974903050100)**

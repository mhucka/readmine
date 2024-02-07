# READMINE: Suggested template for software READMEs

This is an example README file demonstrating a suggested structure for README files of software projects on GitHub.  You can copy this file into your project repository and edit the text as needed.

[![License](https://img.shields.io/badge/License-CC0-lightgray.svg?style=flat-square)](https://creativecommons.org/publicdomain/zero/1.0/)
[![Latest release](https://img.shields.io/github/v/release/mhucka/readmine.svg?style=flat-square&color=b44e88&label=Latest%20release)](https://github.com/mhucka/readmine/releases)
[![DOI](http://img.shields.io/badge/DOI-10.22002%20%2f%20D1.20173-blue.svg?style=flat-square)](https://data.caltech.edu/records/20173)
[![Mentioned in Awesome Awesome README](https://awesome.re/mentioned-badge-flat.svg)](https://github.com/matiassingers/awesome-readme)


## Table of contents

* [Introduction](#introduction)
* [Installation](#installation)
* [Quick start](#quick-start)
* [Usage](#usage)
* [Known issues and limitations](#known-issues-and-limitations)
* [Getting help](#getting-help)
* [Contributing](#contributing)
* [License](#license)
* [Acknowledgments](#acknowledgments)


## Introduction

This repository contains a README file in Markdown format. The file is meant to provide a self-documenting template for README files, as well an illustration of what the file can be expected to look like. The structure of this file is based on examining many examples and recommendations for README files, as well as this author's own experiences of creating many open-source projects and repositories over three decades.

For a real software project, the [Introduction](#introduction) section – which you are presently reading – should summarize in general terms what the software does, the need(s) it addresses, the programming language(s) it's written in, and optionally, links to other resources that can help orient readers. Ideally, this section should be short and use plain language. Keep in mind that not all readers will be familiar with the topic area.


## Installation

Begin this section by mentioning prerequisites that users may need to obtain before they can use your software. Examples include required hardware, operating systems, and software frameworks.

Next, provide step-by-step instructions for installing your software, preferably with examples of commands that can be copy-pasted by readers into their computing environments. If your software can be installed using common installers or package managers (e.g., `pip`, `npm`, `brew`, `apt`, etc.), illustrate how it can be done using [code blocks](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-and-highlighting-code-blocks) in the Markdown file so that it's clear to readers. For example,

```sh
pip install yoursoftware
```

For installation methods that don't involve command lines, try to provide screenshots along with written instructions to help readers figure out what they need to do.

Subsections may be appropriate within this [Installation](#installation) section for different operating systems or particularly complicated installations. Keep in mind, though, that the more complicated the installation process is, the more likely that users will encounter difficulties and give up.


## Quick start

Nobody wants to read long explanations about how to use your software before they can try it, especially while they are still trying to decide _whether_ to try it at all. A [Quick start](#quick-start) section right after the installation instructions helps readers figure out what's involved.

Explain the minimal configuration (if any) required to start using the software, then provide the simplest example or command that demonstrates actual functionality implemented by your software. If your software is command-line oriented, provide examples (again using [code blocks](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-and-highlighting-code-blocks) in the Markdown file).

```sh
yoursoftware argument1 argument2
```

If your software is not command-line oriented, try to provide screenshots – preferably annotated with arrows or other guidance – to show readers how to use the software.

If possible, avoid animated GIFs or video tutorials, for the following reasons: users who turn off animations in their browsers may not even see them, videos hosted on other platforms may disappear over time, videos take more time to keep updated as your software changes, and (at least in this author's experience) a sizeable number of people dislike video tutorials and won't play them anyway.


## Usage

This section explains the principles for using this README file. If this repository were for actual _software_, this [Usage](#usage) section would explain more about how to run the software, what kind of output or behavior to expect, and so on. It would cover basic operations as well as more advanced uses.

Some of the information in this section will repeat what you wrote in the [Quick start](#quick-start) section. This repetition is unavoidable, but also, not entirely undesirable: the more detailed explanation in the [Usage](#section) can help clarify ambiguities that might exist in the more concise [Quick start](#quick-start) section, as well as provide more context.

If your software is complex and has many features, it is better to make a dedicated website for your documentation (e.g., in GitHub Pages, Read the Docs, or similar) rather than to cram everything into a single linear README file. In that case, the [Usage](#section) section can be shortened to just a sentence pointing people to your documentation site.


### Basic operation

A suggested approach for using this example README file is as follows:

1. Copy the [README source file](https://raw.githubusercontent.com/mhucka/readmine/main/README.md) to your repository
2. Delete all body text, but keep the section headings (i.e., the lines that start with `#`)
3. Replace the title heading (on the first line of the file) with the name of your software
4. Commit the resulting skeleton file to your version control system
5. Write your real README content

The first paragraph in the README file (under the title at the very top) should summarize your software in a concise fashion, preferably using no more than one or two sentences. The circled text in the figure below gives an example.

<p align="center">
<img alt="Screenshot showing the top portion of this file on the web." width="80%" src=".graphics/screenshot-top-paragraph.png"><br>
<em>Figure: Screenshot showing the top portion of this file as it would appear on the web.</em>
</p>

The space under the first paragraph and _before_ the [Table of Contents](#table-of-contents) is a good location for optional [badges](https://github.com/badges/shields), which are small visual tokens commonly used on GitHub repositories to communicate project status, dependencies, versions, DOIs, and other information. (Two example badges are shown in the figure above.) The particular badges and colors you use depend on your project and personal tastes.


### More options

Some projects need to communicate additional information to users and can benefit from additional sections in the README file. It's difficult to give specific instructions here – a lot depends on your software, your intended audience, etc. Use your judgment and ask for feedback from users or colleagues to help figure out what else is worth explaining.


## Known issues and limitations

In this section, summarize any notable issues and/or limitations of your software. If none are known yet, this section can be omitted (and don't forget to remove the corresponding entry in the [Table of Contents](#table-of-contents) too); alternatively, you can leave this section in and write something along the lines of "none are known at this time".


## Getting help

Inform readers of how they can contact you, or at least how they can report problems they may encounter. This could take the form of a request to use the issue tracker on your repository. Some projects have associated chat or mailing lists, and this section is a good place to mention those.


## Contributing

This section is optional. If your project accepts open-source contributions, this is where you can welcome contributions and explain to readers how they can go about it. Mention reading the [`CONTRIBUTING.md`](CONTRIBUTING.md) file in your repository, if you have one.


## License

This section should state any copyright asserted on the project materials as well as the terms of use of the software, files and other materials found in the project repository.

_This_ README file is itself distributed under the terms of the [Creative Commons 1.0 Universal license (CC0)](https://creativecommons.org/publicdomain/zero/1.0/). The license applies to this file and other files in the [GitHub repository](http://github.com/mhucka/readmine) hosting this file. This does _not_ mean that you, as a user of this README file in your software project, must also use CC0 license!  You may use whatever license for your work you prefer, or whatever you are required to use by your employer or sponsor.


## Acknowledgments

This final section is where you should acknowledge funding and/or institutional support, prior work that influenced or inspired your project, resources that you used (such as other people's software), important contributions from other people, and anything else that deserves mention. After all, nothing is truly done in isolation; everything is built on top of something, and we all owe debts to other projects and people who helped us, supported us, and influenced us.

For example, in the process of developing this file, I used not only my own ideas: I read many (sometimes contradictory) recommendations for README files, examined real READMEs in actual use, and tried to distill the best ideas into the result you see here. Sources included the following:

* http://tom.preston-werner.com/2010/08/23/readme-driven-development.html
* https://changelog.com/posts/top-ten-reasons-why-i-wont-use-your-open-source-project
* https://dev.to/merlos/how-to-write-a-good-readme-bog
* https://thoughtbot.com/blog/how-to-write-a-great-readme
* https://dev.to/documatic/how-to-write-an-awesome-readme-cfl
* http://jonathanpeelle.net/making-a-readme-file
* https://github.com/noffle/art-of-readme
* https://github.com/noffle/common-readme
* https://github.com/RichardLitt/standard-readme
* https://github.com/jehna/readme-best-practices
* https://gist.github.com/PurpleBooth/109311bb0361f32d87a2
* https://github.com/matiassingers/awesome-readme
* https://github.com/cfpb/open-source-project-template
* https://github.com/davidbgk/open-source-template/
* https://www.makeareadme.com
* https://github.com/lappleapple/feedmereadmes
* https://github.com/badges/shields
* https://readme.so
* https://github.com/orgs/community/discussions/64778
* https://dl.acm.org/doi/10.1145/3611643.3616291

Finally, this README has been optimized for accessibility based on GitHub's Community post "[Tips for Making your GitHub Profile Page Accessible](https://github.com/community)".

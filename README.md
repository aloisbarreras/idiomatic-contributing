# Idiomatic Contributing

Welcome! The fact that you're here means you want to start contributing to open source projects, or you want learn how to be a better contributor. We applaud you for that, and hope you get the most out of this guide. But if you read no further than this section, here are the most important things to take away:

- Idiomatic contributing has more to do with relationships and communication than it does with code
- Conventions are often used in projects to make them easier to maintain. The more popular the project, the more difficult it is to "please everyone". You don't need to like a project's conventions, but it's important to respect them anyway. 

In other words: _Be considerate of a projects conventions, and kind to its humans, and you will go much further in your career as a developer_.

## Table of contents

The following sections are planned. Any contributions or shared wisdom would be appreciated!

- [What to expect from this guide](#what-to-expect-from-this-guide)
- [Contributing 101](#contributing-101)
  * [What is contributing](#what-is-contributing)
  * [Why should I contribute?](#why-should-i-contribute)
  * [Getting familiarized with a project](#getting-familiarized-with-a-project)
- [Effective Contributing](#effective-contributing)
  * [The 4 Details of Highly Effective Bug Reports](#the-4-details-of-highly-effective-bug-reports)
  * [Effective feature requests](#effective-feature-requests)
  * [Contributing code](#contributing-code)
  * [Contributing documentation](#contributing-documentation)
  * [Other ways to contribute](#other-ways-to-contribute)
- [Code of conduct and beyond](#code-of-conduct-and-beyond)
- [About](#about)

<br/>
<br/>
<br/>
![separator](sep.png)
<br/>
<br/>
<br/>

## What to expect from this guide

This guide won't teach you how to use git, or GitHub, or any specific frameworks or tools. There are many other resources available for those things. This guide isn't a replacement for a project's `contributing.md` file either. If you find this guide to be useful, we encourage you to link to it from your project's readme and `contributing.md` files.

If successful, this guide should achieve the following, depending on your level of experience:

- **new to open source**: As the saying goes, "competence breeds confidence". If you've never contributed to an open source project before, this guide will give you the information you need to get started. Confidence will arrive shortly afterwards.
- **experienced**: If you're an experienced contributor, hopefully this guide will help you become a more effective contributor, or at very least give you ideas to use in your own contributing guides. 

<br/>
<br/>
<br/>
![separator](sep.png)
<br/>
<br/>
<br/>

## Contributing 101

### What is contributing? 

There are many ways to contribute to an open source project, including:

- Updating or correcting documentation
- Feature requests
- Submitting bug reports

But you aren't limited to these things. Use your imagination. If you like a project, and you see something that can or should be improved, then you have an opportunity (but not an obligation) to contribute. 

### Why should I contribute?

Regardless of the details, being an effective contributor means that you're adding _adding value_ to a project.

Here are just a few of the advantages of adding value to a project:

- you gain the appreciation and respect of the project's maintainers and community
- you gain valuable experience
- you get noticed by job recruiters
- you become more attrative to potential employers. 

### Getting familiarized with a project

Before you attempt to contribute to a project, take a moment to get familiarized with it. In most cases you can learn all you need to know within a couple of minutes. 

#### Required

The following items are a pre-requisite for contributing to any project. Avoid creating issues or doing pull requests until you've done all of these things:

- **Review the readme**: Oftentimes a project readme has links to documentation, advice on creating issues or bug reports, and so on.
- **Read contributing guidelines**: look for a `contributing.md` file and, if one exists, read it in its entirety before creating issues or doing a pull request. Typically this is in the root of the project, but it might be in `.github/contributing.md` (see [][issue-templates])
- **Search issues**: Before creating bug reports, feature requests, or submitting issues of any kind, you should always search for existing issues (closed or open) that address the same or thing. 

#### Recommended

- **Review unit tests** - one of the best ways to get familiarized with a project is through its unit tests. Of course, this depends on the type of project, complexity, test coverage, and so on. But when applicable, test are often a good source of insight.
- **Get familiarized with the code** - If the codebase is small, and you're familiar with the language, take a moment to review the code to see if you find anything that can be improved. If the codebase is large, you might be able to provide domain expertise or fixes for specific areas.
- **Ask questions** - Depending the project type and size, it might be good to start by searching google to find anwers to your questions. Then, check to see if the project uses [gitter]() or has a [slack]() channel, or something similar. Also visit [stackoverflow]() and do a search to see if others have already asked the same question. As a last resort, create an issue on the project's GitHub repository.

<br/>
<br/>
<br/>
![separator](sep.png)
<br/>
<br/>
<br/>

## Effective contributing

### The 4 Details of Highly Effective Bug Reports

**Rationale**

The easier you make it for a maintainter or members of the community to react, the more likely it is for them to react quickly. 

Like you, maintainers have to make decisions about where to spend their time. Not only within a given project, but oftentimes across multiple projects. If you're experiencing a bug and you want to make a report, bug reports that are clearly described and organized are much more likely to get addressed by the maintainers or member of the community.

Providing these details up front will make everyone happy. If you don't provide these details, maintainers will have to ask you for them, which can be annoying for experienced maintainers who have had to ask for these crucial details many times. 

**The details**

Always include the following essential details in every bug report:

1. [version](#version): what version of X were you using when you experienced the bug?
1. [description](#description): clear description of the bug, and minimum steps to reproduce it.
1. [error messages](#error-messages): paste any error messages into the issue or a [github gist](https://gist.github.com/), and be sure to wrap the error messages in [gfm code blocks][gfm].
1. [code](#code): paste any code necessary for reproducing the bug into the issue or a [github gist](https://gist.github.com/), and be sure to wrap the code in [gfm code blocks][gfm].

Let's review the details in more... detail.

#### 1. version 

Always, always, always provide the version you're using in bug reports. This can't be overstated.

No matter how long you've been contributing to a project, or how familiar you are with the code and core team, every time a bug is reported, the first thing a core team member wants to know is: "What version were you using when you experienced the bug?". Core team members even ask one another for this detail when debugging. The bug you're experience may have alreay been fixed in a patch.

#### 2. description

Decribe the bug with all of the details necessary for others to understand what's happening, including:

- [ ] Expected behavior and actual behavior.
- [ ] Steps to reproduce the problem.

[description]

#### 3. error message

```sh
# paste any error messages here
```

See GitHub's guide to [Creating and highlighting code blocks][gfm] for more details.

#### 4. code

```js
// paste your code into a GFM code block like this. Be sure to use the 
// appropriate language label after the first code "fence"
```

See GitHub's guide to [Creating and highlighting code blocks][gfm] for more details.

[gfm]: https://help.github.com/articles/creating-and-highlighting-code-blocks/

### Effective feature requests

TODO

### Contributing code

TODO

### Contributing documentation

TODO

### Other ways to contribute

TODO

<br/>
<br/>
<br/>
![separator](sep.png)
<br/>
<br/>
<br/>

## Code of conduct and beyond

WIP

- Try to avoid emailing maintainers directly with questions about a project, requests for help, or suggestions for a project. Once you've established a relationship with the maintainers this is probably okay, but it's frowned upon otherwise.
- collaboration leads to faster solutions
- build lasting relationships

<br/>
<br/>
<br/>
![separator](sep.png)
<br/>
<br/>
<br/>

## About

### Contributors

[your name here!]

### Contributing to this project

Please visit the [contributing guide](.github/contributing.md) to learn more about contributing to this project.

### Authors

**Jon Schlinkert**

* [github/jonschlinkert](https://github.com/jonschlinkert)
* [twitter/jonschlinkert](http://twitter.com/jonschlinkert)

**Brian Woodward**

* [github/doowb](https://github.com/doowb)
* [twitter/doowb](http://twitter.com/doowb)

## License

Released under [Creative Commons](LICENSE).
Copyright © 2016, [Jon Schlinkert](https://twitter.com/jonschlinkert).

[issue-templates]: https://github.com/blog/2111-issue-and-pull-request-templates


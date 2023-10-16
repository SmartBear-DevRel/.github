# Contribution Guide

Contributing to an open source project doesn't have to be through code alone. There are various ways in which you can contribute, and at SmartBear DevRel, we're happy to accept all kinds of help. This guide aims to provide information on what kind of contributions you can make, and what steps you should follow.

The [Open Source Guides](https://opensource.guide/) website has a collection of resources for individuals, communities, and companies who want to learn how to run and contribute to an open source project. Contributors and people new to open source alike will find the following guides especially useful:

-   [How to Contribute to Open Source](https://opensource.guide/how-to-contribute/)
-   [Building Welcoming Communities](https://opensource.guide/building-community/)

🚧 This is a living document and will be updated over time to help make contributions easier. Please make sure to read this guide from time to time and check what has changed. Check out the [changelog](#changelog), where we surface changes in ways of working.

## Types of Contributions

We're all just regular folks, those that write code, add comments, oversee the projects and of course those that use it. The rule of thumb is: if in doubt, **be kind** 🙏💗.

### Opening issues
Filing issues with the project is a great step in helping the project — you're helping us learn what's not working, what you might want to see in the project or what we can do better. Help us know where documentation may be lacking. 

Even questions like 'how do I do X?' can be put in as an issue (or you can leverage the discussions option if enabled within a repository).

Before raising an issue, make sure you have checked the open and closed issues to see if an answer is provided there.

When opening an issue, please make sure to follow the issue templates if existing, otherwise provide as much information as possible to allow us to triage the issue.

### Commenting
Adding meaningful comments to issues and pull requests, helps the community as a whole. Providing suggestions, helping solving issues, giving feedback — it all helps. Once again, the main guideline we have here is 'be kind' 💚.

### Documentation
Improving the project documentation (mainly ReadMe's) is a huge help. You don't need to be an expert in the project, or understand all the bits and pieces. Have you dealt with an issue and think that if there was better documentation it'd have been easier? Document that part! If you tried going through the documentation and found it hard to navigate — improve that!

## I'm ready to contribute code

Awesome! We have some guidelines here that will help your PR be accepted.

> TL;DR; 🚀
>
> * it's better to open an issue (or comment in existing issue) to discuss the suggested change before actually making the change
> * Smaller changes are better. If you're working on a large change, it'd be much better to use smaller pull requests 

### Code Contribution Types
Code changes can come in several forms, and the way they're handled differ.

#### Documentation
For the most part, documentation PRs would be accepted after an initial review. Be aware that a large documentation change may require longer review and potentially a discussion.

#### Bug fixes
Bug fixes are always welcome as PRs. If you found a bug and would like to fix it, it's almost always better to open a ticket describing the issue alongside the PR solving it. Sometimes, bug fixes can be controversial. If you think this may happen with your fix, please start a discussion through a ticket before filing an actual fix.

#### Features
Adding features is a great way to improve an open source project. That said, each project has its own roadmap, requirements, constraints and needs. Before submitting a PR for _any_ feature, please file an issue first describing the change you want to make, and wait for feedback. Trying to analyze a feature contribution directly through a pull request is stressful for both sides, and a lot of concerns can be avoided by having an initial discussion. Sometimes a feature may not be relevant for all users but raising visibility of the feature in a fork can be useful (or providing guidance on how to consume the project on a fork).

#### Branching model

- Feature branches should be prefixed with `feat/`.
- Bugfix branches should be prefixed with `bug/` or `fix/`.
- After the forward slash, include a short description of what you're fixing. For example: `bug/fix-the-bug`.

#### Committing

- Break your commits into logical atomic units. Well-segmented commits make it _much_ easier for others to step through your changes.
- Limit your subject (first) line to 69 characters (GitHub truncates more than 70).
- Use the imperative, present tense when possible: "change" not "changed" nor "changes"

#### Pull requests

* Summarize your changes in the PR body. If in doubt, write a bullet-point list titled `This PR does the following:`.
* Write tests for any changes
* Follow existing code style and conventions
* Separate unrelated changes into multiple pull requests
* For bigger changes, make sure you start a discussion first by creating an issue and explaining the intended change


## Changelog

| Version |Release date  |Change notes  |
| --- | --- | --- |
| 1.0.0 |2023-10-16  | Initial Contribution Guide version |
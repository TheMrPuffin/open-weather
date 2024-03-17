
# Contributing to Open Weather

First off, thanks for taking the time to contribute! ❤️

All types of contributions are encouraged and valued. See the [Table of Contents](#table-of-contents) for different ways to help and details about how this project handles them. Please make sure to read the relevant section before making your contribution. It will make it a lot easier for us maintainers and smooth out the experience for all involved. The community looks forward to your contributions. 🎉

## Table of Contents

- [I Have a Question](#i-have-a-question)
- [I Want To Contribute](#i-want-to-contribute)
    - [Reporting Bugs](#reporting-bugs)
    - [Suggesting Enhancements](#suggesting-enhancements)
    - [Your First Code Contribution](#your-first-code-contribution)
    - [Improving The Documentation](#improving-the-documentation)
- [Styleguides](#styleguides)
    - [Commit Messages](#commit-messages)
- [Join The Project Team](#join-the-project-team)

## I Have a Question

> If you want to ask a question, we assume that you have read the available [Documentation](https://github.com/TheMrPuffin/open-weather/blob/main/README.md).

Before you ask a question, it is best to search for existing [Issues](https:github.com/themrpuffin/open-weather/issues) that might help you. In case you have found a suitable issue and still need clarification, you can write your question in this issue. It is also advisable to search the internet for answers first.

- Open an [Issue](https:github.com/themrpuffin/open-weather/issues/new).
- Provide as much context as you can about what you're running into.

We will then take care of the issue as soon as possible.

## I Want To Contribute

> ### Legal Notice
> When contributing to this project, you must agree that you have authored 100% of the content, that you have the necessary rights to the content and that the content you contribute may be provided under the project license.

### Reporting Bugs

<!-- omit in toc -->
#### Before Submitting a Bug Report

A good bug report shouldn't leave others needing to chase you up for more information. Therefore, we ask you to investigate carefully, collect information and describe the issue in detail in your report. Please complete the following steps in advance to help us fix any potential bug as fast as possible.

- Make sure that you are using the latest version.
- Determine if your bug is really a bug and not an error on your side (Make sure that you have read the [documentation](https://github.com/TheMrPuffin/open-weather/blob/main/README.md). If you are looking for support, you might want to check [this section](#i-have-a-question)).
- To see if other users have experienced (and potentially already solved) the same issue you are having, check if there is not already a bug report existing for your bug or error in the [bug tracker](https:github.com/themrpuffin/open-weatherissues?q=label%3Abug).
- Collect information about the bug:
    - What OS are you running.
    - Version of the Mod and Minecraft you are using.
    - Are you using any additional mods?
    - Can you reliably reproduce the issue? 

<!-- omit in toc -->
#### How Do I Submit a Good Bug Report?

> You must never report security related issues, vulnerabilities or bugs including sensitive information to the issue tracker, or elsewhere in public. Instead sensitive bugs must be sent by email to <>.

We use GitHub issues to track bugs and errors. If you run into an issue with the project:

- Open an [Issue](https:github.com/themrpuffin/open-weather/issues/new). (Since we can't be sure at this point whether it is a bug or not, we ask you not to talk about a bug yet and not to label the issue.)
- Explain the behavior you would expect and the actual behavior.
- Please provide as much context as possible and describe the *reproduction steps* that someone else can follow to recreate the issue on their own. 
- Provide the information you collected in the previous section.

Once it's filed:

- The project team will label the issue accordingly.
- If the team is able to reproduce the issue, it will be marked `needs-fix`, as well as possibly other tags (such as `critical`), and the issue will be left to be [implemented by someone](#your-first-code-contribution).

### Suggesting Enhancements

This section guides you through submitting an enhancement suggestion for Open Weather, **including completely new features and minor improvements to existing functionality**. Following these guidelines will help maintainers and the community to understand your suggestion and find related suggestions.

#### Before Submitting an Enhancement

- Make sure that you are using the latest version.
- Read the [documentation](https://github.com/TheMrPuffin/open-weather/blob/main/README.md) carefully and find out if the functionality is already covered, maybe by an individual configuration.
- Perform a [search](https:github.com/themrpuffin/open-weather/issues) to see if the enhancement has already been suggested. If it has, add a comment to the existing issue instead of opening a new one.
- Find out whether your idea fits with the scope and aims of the project. It's up to you to make a strong case to convince the project's developers of the merits of this feature. Keep in mind that we want features that will be useful to the majority of our users and not just a small subset. If you're just targeting a minority of users, consider writing an add-on/plugin library.

<!-- omit in toc -->
#### How Do I Submit a Good Enhancement Suggestion?

Enhancement suggestions are tracked as [GitHub issues](https:github.com/themrpuffin/open-weather/issues).

- Use a **clear and descriptive title** for the issue to identify the suggestion.
- Provide a **step-by-step description of the suggested enhancement** in as many details as possible.
- **Describe the current behavior** and **explain which behavior you expected to see instead** and why. At this point you can also tell which alternatives do not work for you.
- **Explain why this enhancement would be useful** to most Open Weather users. You may also want to point out the other projects that solved it better and which could serve as inspiration.

<!-- You might want to create an issue template for enhancement suggestions that can be used as a guide and that defines the structure of the information to be included. If you do so, reference it here in the description. -->

### Your First Code Contribution

#### Setup

1. Begin by cloning the repository via SSH:
```
git@github.com:TheMrPuffin/open-weather.git
```
Or, clone via HTTPS:
```
https://github.com/TheMrPuffin/open-weather.git
```

2. In the root of the repository, run:
```
gradlew eclipse
```

Or, if you plan to use IntelliJ, run:
```
gradlew idea
```

3. Run:
```
gradlew genEclipseRuns
```

Or, to use IntelliJ, run:
```
gradlew genIntellijRuns
```
4. Begin to code! 

## Styleguides

### Commit Messages
For the Open Weather project we follow the ``Conventional Commits`` specification. The website for it can be found [here](https://www.conventionalcommits.org/en/v1.0.0/#specification).

Before a ``Pull Request`` can be merged into the ``main`` branch, all commits must be in this that format or it will not pass the CI workflows. 

If you are stuck, check out any previous commits or just give someone in the project team a shout. 

## Attribution
This guide is based on the **contributing-gen**. [Make your own](https://github.com/bttger/contributing-gen)!

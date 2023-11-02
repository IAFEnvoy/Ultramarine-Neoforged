# Contributing to Ultramarine Mod 

First of all, thanks for taking your time to contribute to this project!

In this document are guidelines for contributing to the development of the Ultramarine Mod. These are mostly guidelines, not rules. Use your best judgment, and feel free to propose changes to this document in a pull request.

## Contributing

You can choose your way of contributing that fits your interest, which are mainly with issues or code contributions. 

### Issues

You can use issues to report bugs and/or problems you find playing the mod, or request new features that may make a great addition or enchancement to the mod. While we don't have a templete for issues, please be concise and thoughtful when describing the problem encountered or the feature requested.

### Code Contributions

You can also get yourself involved by making code contributions to the project codebase. Please be aware of the contribution policy in the README file before deciding to contribute. Currently we're only accepting **code** contributions, which does not incluse artistic resources, without prior arrangements. 

A great place to start would be the issues of this project. You could try to tackle one of the issues we have and provide your solutions. When you're happy with your work, please submit a pull request. We'll review the PR and merge it if the standards are met and no problems were found. We may ask for changes to be made before a PR can be merged.

#### Code Style Guide

* All commits must be tagged with a relevant *gitmoji* at the start of the commit message. The commit message itself must be descriptive.
* No code format rules are enforced, but please use common sense.
* Try to integrate into existing systems when implemeting new logic to reduce redundancy and avoid breaking changes.
* The assets and data files (e.g. block state definitions, recipes, etc.) except non-standard models (e.g. most decorative blocks) are to be generated with data generation when possible.

#### About Porting

You're welcome to help port the mod to other versions, but we'll only accept PRs for certain versions:
* We choose a Minecraft version to be the "main" version to focus the developement effort on (usually the main branch), this "main" version will change as new Minecraft versions get released.
* Current and past "main" version branches will be maintained in this repo, you're welcome to backport new features to older versions (both past "main" versions and other versions lower than current "main" version), if a branch needs to be created to accomodate a backport, please contact the repo maintainers.
* PRs adding new features not present on current "main" version to older versions will not be accepted.
* PRs with ports to versions higher than current "main" version will not be accepted to avoid confusion and possible future conflict.
* PRs with ports to other APIs are not allow either, we currently don't have the avaibility to supervise other versions.
* However, you're free to create another fork of this repo for ports that are not currently maintained on this repo, under the license terms.

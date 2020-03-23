# Contributing

Please take a moment to review this document in order to make the contribution
process easier and effective. Following these guidelines helps to communicate that you respect the time of the developer managing these files.

<br>

## Using the issue tracker

The issue tracker is the preferred channel for content [issues](#issues) and [requests](#requests). Please **do not** use the issue tracker for personal support regarding the character builder (use info@aurorabuilder.com or [Discord](https://discord.gg/MmWvNFV)).

<br>

<a name="issues"></a>
## Content Issues

Create an [issue](https://github.com/aurorabuilder/elements/issues/new/choose) using the _Content Issue_ template.<br>
A content issue might be one of the following:

* missing content from an existing source <sup>1</sup>
* typo in a (sheet) description or and outdated description (due to errate for example)
* incorrect values, traits, or features being added

<sup>1</sup> The source might be marked as incomplete or has an additional information indicator with more information about why it's incomplete. This might be a contribution that was included in an incomplete state in the past. This will not be done in the future to avoid having multiple incomplete sources that are never finished.

<br>

<a name="requests"></a>
## Content Requests

Create an [issue](https://github.com/aurorabuilder/elements/issues/new/choose) using the _Content Request_ template.
Provide a link to the website where the content is presented and more information about the source can obtained (e.g. a link to the creator's website or a blog post). **Do not** post direct links to copyrighted material.

When making a request make sure it's in the [project scope](#scope). Out of scope requests will be closed.

Disclaimer: _Making a request does not guarantee it will be included._

<br>

<a name="pull-requests"></a>
## Pull Requests

Good pull requests are a great help. They should remain focused in scope and avoid containing unrelated commits. Make sure to **not** create one from your master branch, instead create a new branch for it.

Please ask first before embarking on any significant pull request (e.g. adding significant content, refactoring files), otherwise you risk spending a lot of time working on something that the project's developer might not want to merge into the repository.

Next, make sure the content contribution falls in the [project scope](#scope) and adheres to the following guidelines to make checking and testing contributes easier and less time consuming.

* Give your commits a meaningful name instead of just _updated file1.xml_
* When making changes to an existing file, increment the version (e.g. from 0.1.2 to 0.1.3)
* Indent (tabs) the files properly to make them readable
* Make sure the IDs of new elements only contain alphanumeric characters and underscores (`[A-Z]`, `[0-9]`, `_`) and no spaces or other special characters.
* Make sure to check and test your files - for example: when making a class make sure you've tested it with all archetype combinations for levels 1-20
* Ensure the contribution is complete and ready to checked and merged. If you're working on something large, you can create an issue with a todo list to communicate your progress.

<br>

<a name="scope"></a>
## Project Scope

### In the Project Scope

* Official Core Rulebooks and Supplements
* Unearthed Arcana <sup>1</sup> (Playtest Material)
* Third-Party <sup>2</sup>

<sup>1</sup> some playtest material might require features that are not implemented, in which case they are not included in the repository<br>
<sup>2</sup> following one or more of these guidelines:

* content published under the OGL license
* material that has been playtested (but not playtest material)
* documented changes and not prone to frequent changes (maintainablility)
* published as hardcover / softcover / available in print
* popular, highly rated, and well designed documents show care and are a plus 
* quality over quantity

This will help keep things maintainable. You can host content that falls out of the project scope yourself or together with others.

<a name="scope-out"></a>
### Out of the Project Scope

* personal homebrew content
* content from reddit <sup>1</sup>, dnd wiki <sup>2</sup>, dnd beyond, and other sites that allow uses to post uncurated homebrew content
* content from other franchises converted to 5e (e.g. lord of the rings, pokemon, final fantasy, etc)
* content that has features not supported by the character builder or 5e rules in general

<sup>1</sup> There is a community repository for content from reddit [here](https://github.com/community-elements/elements-reddit).<br>
<sup>2</sup> There is a community repository for content from dnd wiki [here](https://github.com/community-elements/elements-dndwiki).


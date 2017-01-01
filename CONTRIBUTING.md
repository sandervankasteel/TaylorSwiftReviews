# Contributing guide

This will be a simple guide on how to contribute to this repository (TaylorSwiftReviews). This guide is currently in **DRAFT status** and is therefor a request for comments. This guide will layout some provide some basic guidelines for contributing to this repository, the topics be talked about in this guide are; a definition list, general contributing, file structure, document structure and unit testing.

- **Definitions**

	* **Owner**
	The person (or Github user) who is responsible for maintaining the repository and approving or denying `Pull Requests`.
	
	* **Repository owner** 
	See `owner`

	* **Pull Request(s)** 
	A indication of a third party, that he/she wants to contribute to this repository. The owner is at his/her own discretion to refuse and/or accept a pull request(s). The owner is required to give an explanation why he/she has denied the pull request. The refusal of a pull request cannot be based on a difference of opinion about the matter in subject (in this case; the music of Taylor Swift) .
	
	* **PR**
	Shorthand textual form of `Pull Request`
	
	* **Markdown**
	Markdown is a lightweight markup language. More info: https://en.wikipedia.org/wiki/Markdown
	
**- General contributing**
All contributing to this repository should be done via `Pull Requests`. In case of external contributors, they are required to make a fork of this repository, make his/her changes and then create a `Pull Request` when he/she is satisfied about the changes.

**- File structure **
All contributor (including the owner of the repository) are bound to the current file structure; `<github username>/<album name>/<track number>-<song name>` within the directory `reviews`. Track numbers should including a trailing 0, if applicable. Any spaces in the name of an album or track name, should be replaced with `_` (underscore) and all names should be in lowercase. 

*Example:*
`reviews/sandervankasteel/speak_now/02-sparks_fly.md`

**- Grading **
Grading should be on a scale from 1 through 100. Where 1 is the lowest score possible and 100 the highest score possible. 

**- Document structure of song reviews**

All documents should be provided in a Markdown format with the extension `.md`. The review of a song should adhere to the following structure.

```
# Songname
## Album: <name of the album> (year of release)
## Grade: <grade>/100
### Reviewer: <github username> (date of writing this review in ISO 8601 format)

<reviewers opinion>

Sources:
```

Any references sources that are mentioned in the reviews, should be a numerical list with the following structure. URL's should be marked as URL via the Markdown syntax and alt text and URL should be the same. (see example)
`1. <name of the source>, <url of the source>` 

*Example;*
```
# Our Song
## Album: Taylor Swift (2006)
## Grade: 77/100
### Reviewer: sandervankasteel (31-12-2016)

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus in est pretium, interdum quam iaculis, auctor neque. Maecenas a volutpat mi. Donec vitae ligula arcu. Pellentesque eleifend odio arcu, nec imperdiet risus euismod sed. Morbi auctor odio quis quam rhoncus semper. Vivamus id orci sem. Praesent id luctus nibh. Morbi suscipit turpis vitae lobortis tempor. Maecenas laoreet nunc mauris, sit amet imperdiet massa commodo id. Vivamus facilisis mollis malesuada. Sed et vulputate purus. Nullam a libero magna. Pellentesque finibus diam libero, eget lacinia metus tempor a. Sed et elit non turpis efficitur dictum ut eget mauris. Sed at lobortis neque. Vestibulum non mi nisi.

Cras sit amet dui ac felis iaculis laoreet sed sed felis. Maecenas luctus dictum volutpat. Nulla et consequat magna. Nulla consequat turpis sed varius consequat. Interdum et malesuada fames ac ante ipsum primis in faucibus. Maecenas accumsan sagittis nunc, ultrices luctus purus tincidunt interdum. Cras tempus sed felis sit amet eleifend. Sed mollis pharetra sodales.[1] 

Sources:
1. Wikipedia, [https://en.wikipedia.org/wiki/Taylor_Swift_(album)](https://en.wikipedia.org/wiki/Taylor_Swift_(album)) 

```

**- Quality of the reviews **
The repository owner will not make any assumption and/or judgment on the perceived quality of the contributed reviews. However, any review placement pull request made to this repository should at least have a lower limit of 20 words. This is to prevent the submission of reviews where the only review text is `Awesome song. 10/10 would listen again` and such (arguably) low quality reviews. Discrimination, hate speech and/or any other forms of harassment are not allowed in the reviews.

**- Error reporting**
Any errors found by readers of the review, should report those errors in the form Github Issues. Errors including but not limited to, typos, grammatical errors and/or errors in dates. Github Issues are not the place for creative differences!

**- UNIT testing**
TODO

(c) 2017 Sander van Kasteel
Version 0.1
MIT License

** Changelog **

* 0.1
	Initial version
	
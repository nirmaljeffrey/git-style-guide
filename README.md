# My Git Style Guide:

## Commit Message Format:

```
type : subject

body

footer
```

## Types:
__build:__ Changes that affect the build system or external dependencies (example scopes: gradle, libraries)<br>
__ci:__ Changes to CI configuration files and scripts (example scopes: Travis, Circle, github ci)<br>
__docs:__ Documentation only changes<br>
__feat:__ A new feature<br>
__fix:__ A bug fix<br>
__perf:__ A code change that improves performance<br>
__refactor:__ A code change that neither fixes a bug nor adds a feature<br>
__style:__ Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)<br>
__test:__ Adding missing tests or correcting existing tests

## Subject:
Subjects should be no greater than 50 characters, should begin with a capital letter and do not end with a period.

Use an imperative tone to describe what a commit does, rather than what it did. For example, use change; not changed or changes.

## Body:
Not all commits are complex enough to warrant a body, therefore it is optional and only used when a commit requires a bit of explanation and context. Use the body to explain the what and why of a commit, not the how.

When writing a body, the blank line between the title and the body is required and you should limit the length of each line to no more than 72 characters.

##  Footer:
The footer is optional and is used to reference issue tracker IDs.

## Example commit message:

```
feat: Summarize changes in around 50 characters or less

More detailed explanatory text, if necessary. Wrap it to about 72
characters or so. In some contexts, the first line is treated as the
subject of the commit and the rest of the text as the body. The
blank line separating the summary from the body is critical (unless
you omit the body entirely); various tools like `log`, `shortlog`
and `rebase` can get confused if you run the two together.

Explain the problem that this commit is solving. Focus on why you
are making this change as opposed to how (the code explains that).
Are there side effects or other unintuitive consequences of this
change? Here's the place to explain them.

Further paragraphs come after blank lines.

 - Bullet points are okay, too

 - Typically a hyphen or asterisk is used for the bullet, preceded
   by a single space, with blank lines in between, but conventions
   vary here

If you use an issue tracker, put references to them at the bottom,
like this:

Resolves: #123
See also: #456, #789
```

## Attribution:
- [Udacity git style guide](https://udacity.github.io/git-styleguide/)
- [Angular git style guide](https://github.com/angular/angular/blob/master/CONTRIBUTING.md#commit)

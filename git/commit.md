# Commit Message Format

Each commit message consists of a header, a body and a footer. The header has a special format that includes a type, a scope and a subject:

    <type>: <subject>
    <BLANK LINE>
    <body>
    <BLANK LINE>
    <footer>

Any line of the commit message cannot be longer 100 characters! This allows the message to be easier to read on github as well as in various git tools.

## Type

Must be one of the following:

- feat: A new feature  
- fix: A bug fix  
- docs: Documentation only changes  
- style: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
- refactor: A code change that neither fixes a bug or adds a feature
- test: Adding missing tests
- chore: Changes to the build process or auxiliary tools and libraries such as documentation generation
- data: Changes to content related files (database or images)

## Subject

The subject contains succinct description of the change:

use the imperative, present tense: "change" not "changed" nor "changes"
don't capitalize first letter
no dot (.) at the end

## Body

Just as in the subject, use the imperative, present tense: "change" not "changed" nor "changes" The body should include the motivation for the change and contrast this with previous behavior.

## Footer

The footer should contain any information about Breaking Changes and is also the place to reference GitHub issues that this commit Closes.

These commit conventions comes from [angular.js](https://github.com/angular/angular.js/blob/master/CONTRIBUTING.md#commit-message-format)

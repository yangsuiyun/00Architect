# Best practice to use github

## Dailly development work flow
* Before coding, each developer should fork the centrol repo.
* Developer suggested to create one branch for each new feature and push to his own forked repo.
* Developer should write the commit comments as follows.
* Developer should create a pull request of the new feature, and label the PR 'Code review'.
* There should be another developer to revew this the pull request. If something wrong is found, label the PR 'Code review fix'; If everythin is fine, label the PR 'ship it'.
* Developer should merge the pull request after it labelled as 'ship it'.
* When there is new demand, a issues should be created.

## Commit comments requirement
Please be aware that you need to follow the patterns below when writing commit comments.

Commit message format

```
<type>[(#<ISSUE_NO>)]: <description>
```

The key words “MUST”, “MUST NOT”, “REQUIRED”, “SHALL”, “SHALL NOT”, “SHOULD”, “SHOULD NOT”, “RECOMMENDED”, “MAY”, and “OPTIONAL” in this document are to be interpreted as described in [RFC 2119](https://www.ietf.org/rfc/rfc2119.txt).

* Commits MUST be prefixed with a type, which consists of a noun: feat, fix, etc., followed by a colon and a space.
* Commits message MUST be less than 50 characters.
* Commits body MUST wrap at 72 characters.
* The type feat MUST be used when a commit adds a new feature to your application or library.
* The type fix MUST be used when a commit represents a bug fix for your application.
* A description MUST immediately follow the type/scope prefix. The description is a short description of the code changes, e.g., fix: array parsing issue when multiple spaces were contained in string.
* Types other than feat and fix MAY be used in your commit messages.


Commit message

```
docs: correct spelling of CHANGELOG
```

Commit message with issue no

```
feat(#17): export purchases
```

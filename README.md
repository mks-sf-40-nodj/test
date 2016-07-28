# gitworkflow
A repo to test git, pull request, and rebase.

## Git Commit Conventions
Please follow Karma for your commits and pull-request.

Excerpt from [Karma Git Commit Msg](http://karma-runner.github.io/1.0/dev/git-commit-msg.html)
### Template:

```text
<type>(<scope>): <subject> (required)

<body> (optional)

<footer> (optional)
```

#### type (required)
- feat (new feature for the user, not a new feature for build script)
- fix (bug fix for the user, not a fix to a build script)
- docs (changes to the documentation)
- style (formatting, missing semi colons, etc; no production code change)
- refactor (refactoring production code, eg. renaming a variable)
- test (adding missing tests, refactoring tests; no production code change)
- chore (updating grunt tasks etc; no production code change)

#### scope (optional)
- init
- runner
- watcher
- config
- web-server
- proxy
- etc.

#### body (optional)
- uses the imperative, present tense: “change” not “changed” nor “changes”
- includes motivation for the change and contrasts with previous behavior

#### footer (optional)
- Closed issues should be listed on a separate line in the footer prefixed with "Closes" keyword like this:
- Closes #123, #245, #992

### Example
```text
feat(init): create some test files

Create test file to start with

Closes #0, #0, #0
<footer>
```

# Kodstugan - Guidelines

## git

### Branches
It is **strictly forbidden** to push to master. If this is bypassed you will automatically be kicked and banned for life.
Whenever you do a change to this repo you should do it by using **pull requests**, if possible assign a current issue in your PR message and it will be automatically closed once the PR is approved.
```
closes #1 // will automatically close issue #1 on approval
```
Close the branch if it's not necessary to keep.

### Naming convention of branches
Naming of branches should follow our naming convention:
```
<dev:misc>/<markup:js:other>/<issue:feature:bug>

dev/markup/profile-view
dev/socket/oauth-fix
misc/guideline-update
misc/logo-update
```

### Commits
Commit often, a rule of thumb is if you can write a sentence about what you've done so far it's worth to make it into a commit.

## javascript

### variables
We only use **let** and **const** variables. People who use **var** will automatically be kicked and banned for life.
```
let isRaining = true // re-assignable, although it wont change often in Sweden...
const kilometer = 1000.0 // not re-assignable
```
When in need of **global variables** use capitalised variables. Avoid if possible.
```
let CLIENTS = []
const PI = 3.14159265358979323846
```

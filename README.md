# Analisis-de-Sistema

### Introduction to Git commit
- 'git commit'
- 'git commit'

### Branching in Git
- 'git branch bugFix'
- 'git checkout bugFix'

### Merging in Git
- 'git checkout -b bugFix'
- 'git commit'
- 'git checkout main'
- 'git commit'
- git merge bugFix'

### Rebase Introduction
- 'git checkout -b bugFix'
- 'git commit'
- 'git checkout main'
- 'git commit'
- 'git checkout bugFix'
- 'git rebase main'

### Detach yo' HEAD
- 'git checkout c4'

### Relative refs (^)
- 'git checkout bugFix^'

### Relative refs #2 (~)
- git branch -f main C6
- git branch -f bugFix C0
- git checkout C1

### Reversing Changes in Git
- 'git reset local~1'
- git checkout pushed'
- 'git revert pushed'

### Cherry pick Intro
- 'git cherry-pick c3 c4 c7'

### Interactive Rebase Intro
- 'git rebase -i main~4 --aboveAll'

### Grabbing Just 1 Commit
- 'git checkout master'
- 'git cherry-pick C4'

### Juggling Commits
- 'git rebase -i caption~2 --aboveAll'
- 'git commit --amend'
- 'git rebase -i caption~2 --aboveAll'
- 'git branch -f main caption'

### Juggling Commits #2
- 'git checkout main'
- 'git cherry-pick C2'
- 'git commit --amend'
- 'git cherry-pick C3'

### Git Tags
- 'git tag v0 C1'
- 'git tag v1 C2'
- 'git checkout C2'

### Git Describe
- 'git commit'

### Rebasing over 9000 times
- 'git rebase main bugFix'
- 'git rebase bugFix side'
- 'git rebase side another'
- 'git rebase another main'

### Multiple parents
- 'git branch bugWork main~^2~'

### Branch Spaghetti
- 'git checkout one'
- 'git cherry-pick C4 C3 C2'
- 'git checkout two'
- 'git cherry-pick C5 C4 C3 C2'
- 'git branch -f three C2'

## Remote
### Clone Intro
- 'git clone'

### Remote Branches
- 'git commit'
- 'git checkout o/main'
- 'git commit'

### Git Fetchin’
- 'git fetch'

###  Git Pullin’
- 'git pull'

### Fakeing Teamwork
- 'git clone'
- 'git fakeTeamwork main 2'
- 'git commit'
- 'git pull'

### Git Pushin’
- 'git commit'
- 'git commit'
- 'git push'

### Diverged History
- 'git clone'
- 'git fakeTeamwork'
- 'git commit'
- 'git pull --rebase'
- 'git push'

### Push Master!
- 'git checkout -b feature'
- 'git checkout main'
- 'git reset --hard o/master'
- 'git push origin feature'
- 'git checkout feature'

### Push Master!
- 'git fetch'
- 'git rebase o/main side1'
- 'git rebase side1 side2'
- 'git rebase side2 side3'
- 'git rebase side3 main'
- 'git push'

### Merging with remotes
- 'git checkout main'
- 'git pull'
- 'git merge side1'
- 'git merge side2'
- 'git merge side3'
- 'git push'

### Remoting Tracking
- 'git checkout -b side o/main'
- 'git commit'
- 'git pull --rebase'
- 'git push'

### Git Push Arguments
- 'git push origin main'
- 'git push origin foo'

###  Git Push Arguments -- Expanded!
- 'git push origin main~1:foo'
- 'git push origin foo:main'

###  Fetch Arguments
- 'git fetch origin main~1:foo'
- 'git fetch origin foo:main'
- 'git checkout foo'
- 'git merge main'

### Source of Nothing
- 'git push origin :foo'
- 'git fetch origin :bar'

### Pull Arguments
- 'git pull origin bar:foo'
- 'git pull origin main:side'



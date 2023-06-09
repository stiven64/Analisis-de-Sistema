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
- 'git checkout main'
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
- 'git reset --hard o/main!
'
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

![Captura de pantalla (4)](https://user-images.githubusercontent.com/124651311/226494662-e196352d-b6e3-4c16-b473-9efa03c0cd9c.png)
![Captura de pantalla (5)](https://user-images.githubusercontent.com/124651311/226494667-7121d383-bf12-43cc-88de-dcd13c621866.png)
![Captura de pantalla (6)](https://user-images.githubusercontent.com/124651311/226494691-6851f8e4-673c-4b0e-b746-1f5d82b89426.png)

![Imagen1](https://user-images.githubusercontent.com/124651311/226495022-f38aec92-782d-493d-917c-208060422428.png)
![Imagen2](https://user-images.githubusercontent.com/124651311/226495029-ca423074-e894-41dd-a814-3ad586e4a390.png)
![Imagen3](https://user-images.githubusercontent.com/124651311/226495036-677a3f7f-2ee2-4491-9d43-fdc27be47969.png)
![Imagen4](https://user-images.githubusercontent.com/124651311/226495046-19c7e7c8-3c87-4afe-93bb-f0a426e5479c.png)
![Imagen5](https://user-images.githubusercontent.com/124651311/226495057-be42b3f1-cbc5-4e31-b492-3f1591d1017b.png)



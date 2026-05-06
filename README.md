# PORTFOLIO SITE

## Git verziókezelés
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Simon0D/Portfolio.git
git push -u origin main

## Ellenőrizni kell, hogy sikeres-e a telepítés. 
### VsCode meg kell nyitni a felső menüben, egy terminált. Az új terminál létrejöttekor (a jobb oldali plusz jel mellett, a lenyíló gombra kattintva válszd a git bash-t.)
### Git ellenőrzése:
git -v 
### Nodejs szerver ellenőrzése:
node -v
### NPM csomagkezelő ellenőrzése:
npm -v


## Így PUSH-old amikor már a fenti setup kész van:
git remote add origin https://github.com/Simon0D/Portfolio.git
git branch -M main
git push -u origin main
## Így PULL-old amikor más valalki módosította a fájlokat:
git pull origin main
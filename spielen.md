## hier kommt mein testen

## linux kommandos

## ls listet dateien
ls 

## kommando dann mit CTRL-C und CTRL-V im Terminal ausprobieren

## github konto erstellen
https://github.com/

https://github.com/devops1222/spielwiese.git

## git lokal initialisieren
git init

## Set initial git configuration
## Can replace --global with --local to set values for a specific repo if required
git config --global --list    #care about username and email

git config --global user.name "Marcus"
git config --global user.email devops1222@schuerstedt.com

## lokales git mit github verbinden
git remote add origin https://github.com/devops1222/spielwiese.git

## alle dateien ins git aufnehmen
git add .

## commit 
git commit -m "first commit"

## ins github mergen
git push -u origin 

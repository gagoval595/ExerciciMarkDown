# Exercici 4

**Exercici 1**

***Crea una nova branca bibliografia i mostrar les branques del repositori.***

- git branch bibliografia 
- git branch 

**Exercici 2**

***Crear el fitxer capítols/capitol4.txt i afegir el següent text***

- nano capitol4.txt

En aquest capítol veurem com utilitzar Git Hub per allotjar repositoris en remot.

***Afegir els canvis a la zona d'intercanvi temporal.***

- git add capitol4.txt

***Fer un commit amb el missatge "Afegit capítol 4."

- git commit -m "Afegit capítol 4."

***Mostrar la història del repositori incloent totes les branques.***

- git log

**Exercici 3**

***Canvia a la branca bibliografia.***

- git checkout bibliografia

***Crea el fitxer bibliografia.txt i afegir la següent referència:***

- nano bibliografia.txt

- Chacon, S. and Straubm B. Pro Git. Apress

***Afegeix els canvis a la zona d'intercanvi temporal.***

- git add bibliografia.txt

***Fes un commit amb el missatge "Afegida primera referència bibliogràfica."***

- git commit -m "Afegida primera referència bibliogràfica."

***Mostra la història del repositori incloent totes les branques.***

- git log --all --graph –decorate

**Exercici 4**

***Fusiona la branca bibliografia amb la branca master.***

- git checkout master

- git merge bibliografia


***Resol el conflicte deixant el fitxer bibliografia.txt amb les referències:***

- Chacon, S. and Straubm B. Pro Git. Apress

- Loeliger, J. and McCullogh, M. Version control with Git. O'Relly

- Hodson, R. Ry's Git Tutorial. Smashwords (2014)


***Mostra la història del repositori incloent totes les branques.***

- git log --all --graph --decorate


***Elimina la branca bibliografia.***

- git branch -d bibliografia


***Mostra de nou la història del repositori incloent totes les branques.***

- git log --all --graph –decorate

**Exercici 5**

***Crea la branca bibliografia.***

- git branch bibliografia

***Canvia a la branca bibliografia.***

- git checkout bibliografia

***Canvia el fitxer bibliografia.txt perquè continga les següents referències:***

- nano bibliografia.txt

- Chacon, S. and Straubm B. Pro Git. Apress
- Ryan Hodson. Ry's Git Tutorial. Smashwords (2014)


***Afegeix els canvis a la zona d'intercanvi temporal i fer un commit amb el missatge "Afegida nova referència bibliogràfica."***

- git * add

- git commit -m "Afegida nova referència"

***Canvia a la branca master.***

- git checkout master

***Canvia el fitxer bibliografia.txt perquè continga les següents referències:

- nano bibliografia.txt

- Chacon , S. and Straubm B. Pro Git. Apress

- Loeliger, J. and McCullogh, M. Version control with Git. O'Relly

- Hodson, R. Ry's Git Tutorial. SmashWords (2014)


**Afegeix els canvis a la zona d'intercanvi temporal i fer un commit amb el missatge "Afegida nova referència bibliogràfica."***

- git commit -m "Afegida nova referència bibliogràfica."


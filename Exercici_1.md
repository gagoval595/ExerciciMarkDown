# ExerciciMarkDown
**Exercici 1**

***Crea un repositori nou amb el nom llibre i mostrar el seu contingut.***
- mkdir llibre 
- cd llibre
- git init llibre 

***Configura Git definint el nom de l'usuari, eñ correu electrònic i activar l'eixida en color***

- git config --global user.name "Gabriel"
- git config --global user.email "gongoragabrielvalle@gmail.com"
- git config --global color.ui auto

***Mostrar la configuració final***
- git config --list

**Exercici 2**

***Comprova l'estat del repositori***

- git status

***Crea un fitxer index.txt amb el següent contingut:***

Capítol 1: Introducció a Git
Capítol 2: Fluxe de treball bàsic
Capítol 3: Repositoris remots

 ***Comprova de nou l'estat del repositori.***

- nano index.txt

***Afegeix el fitxer a la zona d'intercanvi temporal.***

- git add index.txt

***Tornar a comprovar una vegada més l'estat del repositori.***

- git status

  **Exercici 3**

***Realitza un comit dels últims canvis amb el missatge "Afegit índex del llibre." i veure l'estat del repositori.***

- git commit --m "Afegit índex del llibre."
- git status

  **Exercici 4**

  ***Canvia el fitxer índex.txt perquè continga el següent***

- nano index.txt

Capítol 1: Introducció a Git
Capítol 2: Fluxe de treball bàsic
Capítol 3: Gestió de branques
Capítol 4: Repositoris remots

***Mostra els canvis respecte a l'ultima versió guardada al repositori***
- git diff

***Fer un commit dels canvis amb el missatge "Afegit el capítol 3 sobre la gestió de branques."***

**Exercici 5**

***Mostrar els canvis de l'última versió del repositori respecte a l'anterior***

- git log -p -1

***Canviar el missatge de l'últim commit a "Afegit capítol 3 sobre la gestió de branques a l'índex. "***

- git commit --aemend -m "Afegit capítol 3 sobre la gestió de branques a l'index".

***Torna a mostrar els últims canvis del repositori***

- git log -p -1

**Exercici 6**

***Indica a Git que vols ignorar tots els fitxers que comencen per "daw", tots els que tenen l'extensió out i les imatges (jpg, png, bmp i gif).***

- touch .gitignore
- nano .gitignore

  daw*
  *.out
  *.jpg
  *.png
  *.bmp
  *.gif

  

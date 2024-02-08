# Exercici 3

**Exercici 1**

***Elimina l'última línia del fitxer índex.txt i guarda-ho.***

- sed -i '$d' index.txt

***Comprova l'estat del repositori.***

- git status

***Desfés els canvis realitzats al fitxer índex.txt per tornar a la versió anterior del fitxer.***

- git checkout –index.txt

***Torna a comprovar l'estat del repositori.***

- git status

**Exercici 2**

***Elimina l'última línia del fitxer índex.txt i guarda-ho.***

- sed -i ‘$d’ index.txt

**Exercici 3**

***Elimina l'última línia del fitxer índex.txt i guardar-ho.***

- sed -i ‘$d’ index,html

***Elimina el fitxer capítols/capitol3.txt.***

- rm capitols/capitol3.txt

***Afegeix un fitxer nou capítols/capitol4.txt buit.***

- touch capitols/capitol4.txt

***Afegeix els canvis a la zona d'intercanvi temporal.***

- git add index.txt capitols/capitol4.txtComprova de nou l'estat del repositori.
- git status

***Treu els canvis de la zona d'intercanvi temporal, però mantin-los al directori de treball.***

- git reset HEAD index.txt capitols/capitol4.txt

***Comprova de nou l'estat del repositori.***

- git status

***Desfés els canvis realitzats per tornar a la versió del repositori.***

- git checkout -- index.txt capitols/capitol3.txt capitols/capitol4.txt

***Torna a comprovar l'estat del repositori.***

- git status

**Exercici 4**

***Elimina l'última línia del fitxer índex.txt i guardar-ho.***

- sed -i ‘$d’ index,html

***Elimina el fitxer capítols/capitol3.txt.***

- rm capítols/capitol3.txt

***Afegeix els canvis a la zona d'intercanvi temporal i fer un commit amb el missatge "Borrat accidental."***

- git add index.txt capítols/capitol3.txt

- git commit -m "Borrat accidental."

***Comprova l'historial del repositori.***

- git log

***Desfés l'últim commit, però mantin els canvis anteriors al directori de treball i a la zona d'intercanvi temporal.***

- git reset HEAD~1

***Comprova l'historial i l'estat del repositori.***

- git log

- git status

***Torna a fer el commit amb el mateix missatge d'abans.***

- git commit -m "Borrat accidental."

***Desfés l'últim commit i els canvis anteriors al directori de treball, tornant a la versió anterior del
repositori.***

- git reset --hard HEAD~1

***Comprova de nou l'historial i l'estat del repositori.***

- git log

- git status

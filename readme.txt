18-05-2019 Oscar

He comen�at amb els primers apartats, ja que s�n necessaris per a l'an�lisi estad�stic posterior.
He comen�at els apartats 1,2 i 3.1. Cap d'ells est� finalitzat, ja que preferia anar a la part t�cnica (neteja).

Si amb alguna decisi� de neteja o similar no est�s d'acord, ho parlem.

Dem� continuar�.


19-05-2019 Oscar

He arribat fins l'exercici 4.2

Falta:

- 4.1: planificaci� de l'an�lisi (ho vull parlar amb tu abans).
- 4.2: an�lisi vari�ncia.
- 3.2: possibles outliers detectats

errors pendets d'arreglar:
- 3.0: error al passar a raw l'atribut survived
- Espai buit al finalitzar els gr�fics

Qualsevol cosa hem dius.

19-05-2019 Carlos
Afegeixo lo que m'ha donat temps a mirar-me avui.

Al punt 3 afegeixo codi per a comprobar els tipus de dades.
Al punt 3.1. afegeixo codi per a que es vegi clarament els valors NA i buits. Substitueixo la forma d'emplenar els valors NA d'Age (k-Nearest Neighbors).
A m�s a m�s, modifico la manera d'emplenar el valor NA de "Fare".
A mi no m'ha donat error a l'hora de convertir l'atribut survived a "raw". De totes maneres, he pensat que potser es millor convertir l'atribut a "logical".

He anat fent probes tamb� per a crear histogrames i gr�fics de densitat de diferents variables, per a mostrar les dades d'una manera m�s visual. Afegir� el codi dem�. Dem� continuar� mirant els errors que t'han donat, juntament amb els outliers, i anir� mirant aquests dies la planificaci� de l'an�lisi i la vari�ncia.

Anem parlant.

20-05-2019 Carlos
A l'hora de modificar els valors nuls del camp "Age", per saber si afecta a la densitat de les dades, creo un dataFrame per a tenir les dades sense modificar, y poder comparar la distribuci� abans i despr�s de modificar els valors nuls d'Age.
Per als valors nuls de la variable "Fare", modifico el codi per a que calculi correctament la mitjana, excloent els valros nuls.

Afegeixo un possible model per a predir si una persona sobreviur� o no. Per a generar aquest arbre de predicci� he hagut de modificar el camp "Survived" de logical a factor, ja que el output ha de ser un factor.

Pendent:
- Els valors "Embarked" que estan buits, ser�a correcte assignar "S" a aquests valors? O lo millor ser�a descartar aquests registres?
- Outliers: Potser tindr�a sentit tractar �nicament els outliers del camp "Age"
- No entenc el teu error de "Espai buit al finalitzar els gr�fics". No me trobat amb cap error jo.


23/05/2019 Oscar

- Ampliat outliers
- comen�ada regressi� lineal m�ltiple (4.3)

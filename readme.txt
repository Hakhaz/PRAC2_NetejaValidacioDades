
18-05-2019 Oscar

He començat amb els primers apartats, ja que són necessaris per a l'anàlisi estadístic posterior.
He començat els apartats 1,2 i 3.1. Cap d'ells està finalitzat, ja que preferia anar a la part tècnica (neteja).

Si amb alguna decisió de neteja o similar no estàs d'acord, ho parlem.

Demà continuaré.


19-05-2019 Oscar

He arribat fins l'exercici 4.2

Falta:

- 4.1: planificació de l'anàlisi (ho vull parlar amb tu abans).
- 4.2: anàlisi variància.
- 3.2: possibles outliers detectats

errors pendets d'arreglar:
- 3.0: error al passar a raw l'atribut survived
- Espai buit al finalitzar els gràfics

Qualsevol cosa hem dius.

19-05-2019 Carlos
Afegeixo lo que m'ha donat temps a mirar-me avui.

Al punt 3 afegeixo codi per a comprobar els tipus de dades.
Al punt 3.1. afegeixo codi per a que es vegi clarament els valors NA i buits. Substitueixo la forma d'emplenar els valors NA d'Age (k-Nearest Neighbors).
A més a més, modifico la manera d'emplenar el valor NA de "Fare".
A mi no m'ha donat error a l'hora de convertir l'atribut survived a "raw". De totes maneres, he pensat que potser es millor convertir l'atribut a "logical".

He anat fent probes també per a crear histogrames i gràfics de densitat de diferents variables, per a mostrar les dades d'una manera més visual. Afegiré el codi demà. Demà continuaré mirant els errors que t'han donat, juntament amb els outliers, i aniré mirant aquests dies la planificació de l'anàlisi i la variància.

Anem parlant.

20-05-2019 Carlos
A l'hora de modificar els valors nuls del camp "Age", per saber si afecta a la densitat de les dades, creo un dataFrame per a tenir les dades sense modificar, y poder comparar la distribució abans i després de modificar els valors nuls d'Age.
Per als valors nuls de la variable "Fare", modifico el codi per a que calculi correctament la mitjana, excloent els valros nuls.

Afegeixo un possible model per a predir si una persona sobreviurà o no. Per a generar aquest arbre de predicció he hagut de modificar el camp "Survived" de logical a factor, ja que el output ha de ser un factor.

Pendent:
- Els valors "Embarked" que estan buits, sería correcte assignar "S" a aquests valors? O lo millor sería descartar aquests registres?
- Outliers: Potser tindría sentit tractar únicament els outliers del camp "Age"
- No entenc el teu error de "Espai buit al finalitzar els gràfics". No me trobat amb cap error jo.

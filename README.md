# javaScript-exe1
Exercici Javascript
Exercici per practicar funcionalitats bàsiques i tractar amb arrays, llistes i conèixer altres estructures. L’exercici consisteix en mostrar per consola quantes vegades apareix cada lletra del teu nom i cognoms.

Fase 1

Crea una array amb el teu nom on cada posició correspongui a una lletra.
Fes un bucle que recorri l’array i mostri per consola cadascuna de les lletres.

Fase 2

Al bucle, si la lletra és una vocal imprimeix a la consola: ‘VOCAL’. Sinó, imprimeix: ‘CONSONTANT’.
Es pot fer de diferents formes:
Creant una nova array que contingui les vocals (A, E, I, O, U) i comprovant si cadascuna de les lletres del teu nom és en aquesta array amb el mètode indexOf
Comprovar si cadascuna de les lletres del teu nom és igual a ‘a’, ‘e’, ‘i’, ‘o’, ‘u’ concatenant les comprovacions amb ||

Extra: Si trobes un numero, mostra per pantalla: ‘Els noms de persones no contenen números!’.
Pista: Mira’t la funció isNaN

Fase 3

Pensa una forma per emmagatzemar tant les lletres del array com el nombre de vegades que apareixen i implementa’l.
Pista: Map

Fase 4

Crea una array amb el teu cognom on cada posició correspongui a una lletra.
Passa de les dues arrays a una sola. A més, afegeix una posició amb un espai buit entre la primera i la segona. És a dir, abans tenies les arrays name i surname i ara només tens una que es dirà fullName.

	FullName: [‘N’, ‘A’, ‘M’, ‘E’, ‘ ‘, ‘S’, ‘U’, ‘R‘, ‘N’, ‘A’, ‘M’, ‘E’]
Pista: Feu servir aquesta funció (enteneu què esteu fent)
	var myFullName = [];
myFullName.push(...myName);

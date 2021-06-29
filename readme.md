 QUÉ COMANDOS HE USADO?

PASSO 11: git reset --hard HEAD~1
	He querido eliminar los cambios del último commit

PASSO 12 a: git reflog
	Visualizo los números de los commits 

PASSO 12 b: git reset 616ec9a
	He comprobado el número de hash del commit y lo he restablecido

PASSO 13: git merge master
	He hecho que Styled absorbe master, pero parece que no ha funcionado. 
	El git-nuestro.md es el que había en master, sin editar

PASSO 19: git merge htmlify
	Des de la branch styled he hecho el merge. He tenido que eliminar el git-nuestro.md de htmlify y 
	subir el correcto para poder completar el merge.
	Ha habido conflicto porque quería hacer un merge de dos archivos distintos de brancas diferentes

PASSO 21: git merge styled
	Hago un merge desde master.
	No tengo ningún conflicto

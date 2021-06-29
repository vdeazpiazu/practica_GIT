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

PASSO 25: git log --graph --pretty
        Utilizo ese comando para crear un gráfico bonito

PASSO 26: git merge --no-ff title
        He hecho un merge de master a title.
        Hubo conflicto pero con el --no-ff he forzado la resolución del conclifto

PASSO 27: git reset HEAD~1
        He vuelto a un commit anterior

PASSO 28: git stash
	Descarto los cambios

PASSO 29: git branch -D title
	Hay dos comandos, con -d y con -D. No he entendido la diferencia

PASSO 30 a: git reflog
	Compruebo  mi historial de hashes

PASSO 30 b: git reset --hard f4c8272
	Elijo el hash donde hay el commit "he añadido un título ridículo y lo reestablezco



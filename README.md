# aspirantes-mir-ejercicio-3

MacBook-Air-de-Jesus:~ jesusedlv$ git init
Reinicializado el repositorio Git existente en /Users/jesusedlv/.git/
MacBook-Air-de-Jesus:~ jesusedlv$ git add index.html
MacBook-Air-de-Jesus:~ jesusedlv$ git commit
advertencia: no se pudo abrir el directorio '.Trash/': Operation not permitted
advertencia: no se pudo abrir el directorio '.Trash/': Operation not permitted
En la rama rama-1

Confirmación inicial

Archivos sin seguimiento:
  (usa "git add <archivo>..." para incluirlo a lo que será confirmado)
	.CFUserTextEncoding
	.DS_Store
	.bash_history
	.bash_sessions/
	.cups/
	.gitconfig
	.lesshst
	.profile
	.vscode/
	.zsnes/
	Applications/
	Creative Cloud Files/
	Desktop/
	Documents/
	Downloads/
	Ejercicios/
	Library/
	Movies/
	Music/
	Pictures/
	Public/
	mi-carpeta/

no hay nada agregado al commit pero hay archivos sin seguimiento presentes (usa "git add" para hacerles seguimiento)
MacBook-Air-de-Jesus:~ jesusedlv$ git branch develop
fatal: nombre de objeto no válido: 'rama-1'
MacBook-Air-de-Jesus:~ jesusedlv$ git branch develop develop
fatal: nombre de objeto no válido: 'develop'
MacBook-Air-de-Jesus:~ jesusedlv$ clear

MacBook-Air-de-Jesus:~ jesusedlv$ git init
Reinicializado el repositorio Git existente en /Users/jesusedlv/.git/
MacBook-Air-de-Jesus:~ jesusedlv$ touch index.html
MacBook-Air-de-Jesus:~ jesusedlv$ cd index.html
MacBook-Air-de-Jesus:index.html jesusedlv$ git commit -m "primer commit"
advertencia: no se pudo abrir el directorio '.Trash/': Operation not permitted
En la rama rama-1

Confirmación inicial

Archivos sin seguimiento:
  (usa "git add <archivo>..." para incluirlo a lo que será confirmado)
	../.CFUserTextEncoding
	../.DS_Store
	../.bash_history
	../.bash_sessions/
	../.cups/
	../.gitconfig
	../.lesshst
	../.profile
	../.vscode/
	../.zsnes/
	../Applications/
	../Creative Cloud Files/
	../Desktop/
	../Documents/
	../Downloads/
	../Ejercicios/
	../Library/
	../Movies/
	../Music/
	../Pictures/
	../Public/
	../mi-carpeta/

no hay nada agregado al commit pero hay archivos sin seguimiento presentes (usa "git add" para hacerles seguimiento)
MacBook-Air-de-Jesus:index.html jesusedlv$ git branch develop
fatal: nombre de objeto no válido: 'rama-1'
MacBook-Air-de-Jesus:index.html jesusedlv$ git checkout develop
error: ruta especificada 'develop' no concordó con ningún archivo conocido por git
MacBook-Air-de-Jesus:index.html jesusedlv$ touch .env
You have new mail in /var/mail/jesusedlv
MacBook-Air-de-Jesus:index.html jesusedlv$ touch .env
MacBook-Air-de-Jesus:index.html jesusedlv$ touch .gitignore
MacBook-Air-de-Jesus:index.html jesusedlv$ touch .gitignore
MacBook-Air-de-Jesus:index.html jesusedlv$ echo ".env" >> .gitignore
MacBook-Air-de-Jesus:index.html jesusedlv$ git add .gitignore
MacBook-Air-de-Jesus:index.html jesusedlv$ git add index.html
fatal: ruta especificada 'index.html' no concordó con ningún archivo
MacBook-Air-de-Jesus:index.html jesusedlv$ git add index.html
fatal: ruta especificada 'index.html' no concordó con ningún archivo
MacBook-Air-de-Jesus:index.html jesusedlv$ git commit -m "Cambios en la rama develop"
[rama-1 (commit-raíz) 46a1da4] Cambios en la rama develop
 1 file changed, 1 insertion(+)
 create mode 100644 index.html/.gitignore
MacBook-Air-de-Jesus:index.html jesusedlv$ git checkout main
error: ruta especificada 'main' no concordó con ningún archivo conocido por git
MacBook-Air-de-Jesus:index.html jesusedlv$ cat index.html
cat: index.html: No such file or directory
MacBook-Air-de-Jesus:index.html jesusedlv$ git merge develop
merge: develop - no es nada que se pueda fusionar
MacBook-Air-de-Jesus:index.html jesusedlv$ cat index.html
cat: index.html: No such file or directory
MacBook-Air-de-Jesus:index.html jesusedlv$ git ls-files --other --ignored --exclude-standard
.env
MacBook-Air-de-Jesus:index.html jesusedlv$ 

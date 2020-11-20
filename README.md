# casa-insti

Muy buenas,(En este README están incluidos el desarrollo de la practica de tags y la de ramas)
En la siguiente práctica he ejecutado dos commits, uno desde carpetahome y otro desde carpeta insti.
Desde carpetahome hice un git log --pretty=online para ver el listado de commits.
Nombré al primer commit como v1.0, con la siguiente función: git tag -a v1.0 y cogiendo los 7 primeros digitos de la confirmacion.
Luego hice un git push incluyendo al final la etiqueta para que se suba al remoto.
hice un git checkout v1.0 para volver a la primera version, comprobé en mi carpeta que había a la primera version, modifique el codigo.
hice un git add para añadir la modificación, git commit, git push y pasó que me decia que todo estaba up-to-date.
volví a la ultima version con un git checkout master y me salió este mensaje:


Warning: you are leaving 1 commit behind, not connected to
any of your branches:

  93b22ba Actualizacion en el codigo

If you want to keep it by creating a new branch, this may be a good time
to do so with:

 git branch <new-branch-name> 93b22ba

Switched to branch 'master'

entonces, empezando la siguiente practica de ramas, entendí que para poder hacer cambios desde cualquier version, hay que crear ramas.
Voy a carpeta instituto y recupero las etiquetas con git pull --tags origin.

Creacion del readme desde git hub.

Bryan Jesus Rodriguez Rios

Practica de creación de ramas

Estos cambios, son pruebas para el siguiente proyecto de ramas.

Desde carpetahome hice la creacion de nueva rama, con un git branch y nombrando a la nueva rama la cual llamé nueva-rama.
Hice cambios en el readme, hice el primer commit de la nueva rama.
Y un git push con el nombre de la nueva rama al final del origin.
Aparece en el remoto la nueva rama.
Cambio a la rama master con un git checkout.
Desde carpeta instituto bajo la rama creada desde carpetahome, con un git checkout -b nueva-rama, se descarga la nueva rama.
Desde carpeta home y carpeta instituo hago git status en cada rama para no dejarme nada atras, vuelvo a la master en cada carpeta y hago un git merge nueva-rama para unir las dos ramas y subirlas.

Bryan Jesus Rodriguez Rios




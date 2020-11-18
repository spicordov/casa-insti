# casa-insti

Muy buenas,
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

y aquí me he quedado...



Creacion del readme desde git hub.

Bryan Jesus Rodriguez Rios


Estos cambios, son pruebas para el siguiente proyecto de ramas.


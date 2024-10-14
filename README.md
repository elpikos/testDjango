#para iniciar el entorno hay que estaren la terminal
 en la carpeta de scripts e iniciar el Activate.ps1 con:
 .\Activate.ps1 #
 

 Para hacer tu primer git push, sigue estos pasos:

Configura tu nombre de usuario y correo electrónico (solo la primera vez):
git config --global user.name "Tu Nombre"
git config --global user.email "tuemail@example.com"

Inicializa tu repositorio local (si aún no lo has hecho):
git init

Agrega los archivos al área de preparación (staging area):
git add .

Confirma los cambios:
git commit -m "Primer commit"

Enlaza tu repositorio local con el remoto:
git remote add origin https://github.com/elpikos/testDjango.git

Envía tus cambios al repositorio remoto:
git push -u origin main

Estos pasos te permitirán subir tus cambios al repositorio remoto por primera vez12. Si necesitas más detalles, puedes revisar este tutorial en GitHub o ver este video que explica el proceso paso a paso.
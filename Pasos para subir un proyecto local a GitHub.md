Pasos para subir un proyecto local a GitHub

Desde GitHub:
  Creamos un nuevo repositorio en https://github.com. Le damos nombre, descripción, seleccionamos si va a ser un proyecto publico o privado si es el caso, y dejamos el check de crear README sin marcar. Le damos a crear repositorio y con esto ya tenemos el repositorio donde alojaremos nuestro proyecto.

 Deste la terminal local:
  Nos ubicamos en la carpeta del proyecto y abrimos una terminal donde ejecutaremos los siguientes códigos:
    git init
	
	git add .

	git commit -m "first commit"

	git remote add origin https://github.com/NOMBRE_USUARIO/NOMBRE_PROYECTO.git

	git push -u origin master

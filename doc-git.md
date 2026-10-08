##Para inicializar un repositorio en GIT:
git init
cuando inicializamos un archivo los archivos estan inicialmente en "untrakend"/sin seguimiento
git add index.html (esto le dá seguimiento al archivo index html)
o
git add (esto le dá seguimiento a todos los archivos de tu directorio root(raíz))
##para exceptuar o no dar seguimiento a archivos:
o pueden ignorar archivos creando la raiz archivo .gitignore 
##Para versionar
para versionar el codigo debe estar añanido, el codigo que se versiona es el que esta añadido hasta el momento.
git commit-m "primera version en GIT"(crea una version en tu repositorio)
##Para cambiar el nombre de branch principal(opcional)
 branch -M main
 ##configuramos una posicion remota para nuestro repositorio local
git remote add origin https://github.com/melisa-velarde/UTN_2026-PWI_LUN_MIER_TM_-TEST_REPOSITORIO.git
##Enviar el codigo a la direccion remota
git push -u origin main
##como subir cambios a GitHub?
git add.
git commit-m "descripcion"
git push

##Para crear una rama usamos
 git checkout -b <nombre de la rama>

 ##Para movernos entre ramas
 git checkout <nombre de la rama>

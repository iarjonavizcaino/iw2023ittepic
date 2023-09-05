# iw2023ittepic

Creación de repositorios en GitHub
Crear un repositorio en GitHub llamado iw2023ittepic
Clonar el repositorio en local

git clone https://github.com/iarjonavizcaino/iw2023ittepic

Creación de archivo README

Crear en tu repositorio local un documento README.md

Se creó al momento de crear el repositorio en Github de manera visual

Commit Inicial
Añadir al README.md los comandos utilizados hasta ahora y hacer un commit inicial con el mensaje Initial commit

git commit -am 'Initial commit'

PUSH Inicial
Subir los cambios al repositorio remoto

git push origin main

Ignorar archivos

Crear en el repositorio local un fichero llamado privado.txt

touch privado.txt

Crear en el repositorio local una carpeta llamada privada

mkdir privada

Realizar los cambios oportunos para que tanto el archivo como la carpeta sean ignorados por git

vim .gitignore

Añadir las siguientes líneas

privado.txt
privada/

Añadir archivo
Añadir archivo 1.txt al repositorio local

touch 1.txt

Creación de Tag
Crear un tag v0.1

git tag -a v0.1 -m 'My versión v0.1'

Subir cambios
Subir los cambios al repositorio remoto

git add .
git commit -am 'v0.1'
git push origin main


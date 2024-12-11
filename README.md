# PracticaExtra


![imagen](https://github.com/user-attachments/assets/7ca00beb-1d32-4b20-8768-f4dcbca74a1b)

Creamos la estructura de ficheros 

![imagen](https://github.com/user-attachments/assets/4ea623cf-d5b0-4f36-b6ad-f9e9adafdb42)

Creamos el repositorio con el comando

git init .

![imagen](https://github.com/user-attachments/assets/39b87330-784f-4187-9f8b-b6f1b701a6b9)

Añadimos al area de stage solo los archivos que sean .txt del fichero docs y mostramos el estado

git add docs/*.txt
git status
git commit -m “”

![imagen](https://github.com/user-attachments/assets/5bc99e8a-55f4-4035-99dc-2eb81ccb6163)

![imagen](https://github.com/user-attachments/assets/04bd7d73-10a3-4428-84e0-4d977dbe0567)

Añadimos todos los archivos .js del fichero scripts excepto config.js

git add scripts/*.js
git reset scripts/config.js
git commit -m "Commit 2"

![imagen](https://github.com/user-attachments/assets/09b93f40-22ea-4978-9694-e64fd264dbd4)

Añadimos todas las imagenes excepto los gif y mostramos el estado 

git add images/*.png images/*.jpg
git status 

![imagen](https://github.com/user-attachments/assets/77302108-2b01-4571-8985-6d1aab17c39a)


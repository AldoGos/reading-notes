# Bienvenido al laboratorio 3
- ¿Qué es el control de versiones?  
  es un sistema que permite hacer un trackeo de las distintas versiones que a lo largo de su desarrollo atraviesa un proyecto
- ¿Qué es la “cloning” en Git?  
  es copiar el repositorio que tenemos en la nube (o en un servidor particular) a nuestra pc local 
- ¿Cuál es el comando para rastrear y preparar archivos?  
  git add . (el punto indica que todo lo que esta en esa carpeta se va a ir al stagin area)  
  git status (para visualizar los archivos presentes en el stagin)
- ¿Cuál es el comando para tomar una instantánea de los archivos modificados?  
  git commit -m "mensaje humano"
- ¿Cuál es el comando para enviar los archivos modificados a Github?  
  git push

## las 4 areas de los archivos para pasar del local al repositorio remoto
Working dir  (vestuario)
- git add archivo 1 <> git reset (baja del escenario para volver a mandar al vestuario)
- git add archivo 2
stagin area (es como un scenario donde se toma la foto a los artistas)
- git commit (captura de la "foto" de los archivos)
local repo (album de artistas)
- git push
remote repo  

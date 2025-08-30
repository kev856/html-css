Markdown (.md) es un formato de texto plano que permite agregar imágenes, enlaces, títulos, listas, etc.
Previsualiza en VS Code
Pulsa Ctrl + Shift + V (o clic derecho → Open Preview).
. (Opcional) Instala extensiones para mejorar
Markdown Preview Enhanced → permite más opciones, incluso diagramas.
Markdown All in One → atajos útiles y soporte completo para Markdown

Un repositorio local es el que se tiene en el pc y el remoto es el que está en github

Para clonar un repositorio que está en remoto, se copia la url del repositorio
![alt text](image-1.png) la url que está arriba
-En una carpeta vacia, click derecho/click bash here
-Se escribe git clone y al lado se pega la url
-Para saber el nombre del repositorio remoto el cual por defecto es origin, hacer git remote -v
-Saldría algo así  origin  https://github.com/usuario/proyecto.git (fetch)
origin  https://github.com/usuario/proyecto.git (push) osea que origin es el nombre del repositorio remoto
-Para saber cual es la rama, git branch

-Para hacer una actualización al repositorio local
-Hay que entrar dentro de la carpeta del repositorio y hacer click bash here
-git pull nombre del repositorio remoto que por defecto es origin nombre de la rama que normalmente es master y ya
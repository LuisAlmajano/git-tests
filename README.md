## Aprendiendo Git con Udemy


### Comandos habituales Git

Inicializar repositorio local:
> git init

Incluir fichero(s) al stage
> git add .

> git add fichero

Commit de los cambios
> git commit -m "Mensaje commit"

> git commit -am "Mensaje commit" Nota: Este comando nos permite subir al stage y hacer commit.



### Comandos habituales Git - Github

Incluir repositorio remoto en Github:
> git branch -M main  (podemos dejar la branch en master y omitir este paso)

> git remote add origin <link_repositorio>  (link puede ser en HTTPS o SSH)

> git push -u origin main

Realizar un clone de un repositorio en Github:
> git clone <link_repositorio>

Listar repositorio remoto (útil para verificar si la connexión es via HTTPS o SSH):
> git remote -v

> origin  https://your_server/your_user_name/your_project_name.git (fetch)

> origin  https://your_server/your_user_name/your_project_name.git (push)


Editar la URL del repositorio remoto para usar HTTPS o SSH:
> git remote set-url origin git@your_server:your_user_name/your_project_name.git

Referencia: https://kamarada.github.io/en/2019/07/14/using-git-with-ssh-keys/#.X-IJUuB7nyl


### Settings Seguridad

#### 

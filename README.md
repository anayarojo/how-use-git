# Como usar git
Mis notas de como usar git

## Comandos más utilizados

|Comando|Utilización|
|-------|-----------|
|`git status`|Ver los cambios.|
|`git log`|Ver el arbol de cambios.|
|`git pull origin <branch_name>`|Obtener `pull` (bajar) de una rama especifica.|
|`git add -A`|Agregar todos los cambios al `staging`.|
|`git commit -m "<name>"`|Crear `commit`con los cambios en el `staging`.|
|`git push origin <branch_name>`|Hacer `push` (subir) en una rama especifica.|
|`git clone <url>`|Clonar proyecto.|
|`git remote add <name> <url>`|Agregar`remote` por ejemplo `origin`.|
|`git branch <branch_name>`|Crear nueva rama.|
|`git checkout <branch_name>`|Cambiar de rama.|
|`git checkout <branch_name>`|Cambiar de rama.|
|`git fetch <remote_name> <branch_name`|Obtener rama desde el origin u otro remote, es requerido antes de hacer `git branch <branch_name> FETCH_HEAD`.|
|`git branch <branch_name> FETCH_HEAD`|Crear rama desde el origin HEAD.|
|`git commit --amend`|Renombrar el último commit.|
|`git push --force example-branch`|Subir el cambio de nombre del último commit en caso de que este ya esté arriba.|
|`git checkout -b <branch_name>`|Crear nueva rama con los cambios no comiteados.|

## Referencias

[How do I fetch only one branch of a remote Git repository?](https://stackoverflow.com/questions/6368987/how-do-i-fetch-only-one-branch-of-a-remote-git-repository)

[Changing a commit message](https://help.github.com/articles/changing-a-commit-message/#commit-has-not-been-pushed-online)




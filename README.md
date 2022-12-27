# Este es un repositorio para explicar los comandos mas utiles de GIT

## ESTE ES SOLO UN APUNTE

ACTUALIZANDO. EJEMPLO.

```
git init    // inicializamos el repositorio GIT LOCAL

git add .   // subimos todos los cambios pendientes y archivos nuevos al STAGE

git commit -m "comentario"  // saca una foto para la enternidad de lo que esté en el
							STAGE


git config --global alias.lg "log --oneline --decorate --all --graph"
// para luego ejecutar solo git lg
git  config --global alias.s "status -s -b"
// para luego ejecutar solo git s 

git log  // ver listado de commits realizados

git reset --hard <<id commit>>      // CUIDADO PORQUE ELIMINA CAMBIOS QUE ESTEN PENDIENTES DE SUBIR EN EL STAGE.  este comando deja tal cual como estaba el codigo cuando dimos el commit.

git reset --soft <<id commit>>      // vuelve al commit indicado sin eliminar cambios.

git reflog : comando similar al log pero que muestra el historial de todos los cambios o reset realizados.
```

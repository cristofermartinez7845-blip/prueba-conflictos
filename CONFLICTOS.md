\# Documentación del conflicto de fusión



\## Ramas involucradas

\- feature/postre-a: modificó la línea de recetas.txt a "versión chocolate"

\- feature/postre-b: modificó la misma línea a "versión fresa"



\## Conflicto

Al fusionar feature/postre-b sobre main (que ya tenía la versión de postre-a),

Git marcó un conflicto en recetas.txt por modificar la misma línea en ambas ramas.



\## Resolución

Se editó manualmente recetas.txt combinando ambas versiones, eliminando los

marcadores <<<<<<<, =======, >>>>>>>, y se confirmó con:

git add recetas.txt

git commit -m "Resuelve conflicto entre postre-a y postre-b en recetas.txt"



\## Revisión

Revisado por: \[nombre de tu compañero], vía Pull Request #\[número] en GitHub.


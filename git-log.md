
### Historial de confirmaciones

Con git log nos muestra todo el historial de los commits

-git log
-git log --oneline
-git log --graph
-git log --oneline --graph
-git log -2    con este le estoy diciendo que me muestre los dos ultimos commits y puedo cambiar el número


`git log --pretty=format: "%h - %an, %ar : %s"

-%h nos muestra el codigo del commit
-%an muestra el nombre del autor del commit
-%ar muestra hace cuanto se creo el commit
-%s muestra el mensaje del commit


limitar la salida del historial por un rango de fechas

git log --after="2018-03-18"  muestra los commits despues de esa fecha
git log --before="2018-03-01"  muestra los commits antes de esa fecha

se puede combinar como en un rango
git log --after="2018-03-05" --before="2018-03-22"




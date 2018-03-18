
### Para renombrar un archivo en git usamos el comando de abajo
//  git mv oldName.txt newName.txt   

se especifica el archivo como se llama antes junto con su extensión y después de 
un espacio se pone como se va llamar el archivo nuevo junto con la extensión
es bueno usar este comando ya que renombrando el archivo con clic derecho
después tenemos que hacer muchos pasos para que git se entere del renombramiento
que nosotros hicimos con clic derecho

El comando git mv es equivalente a los siguientes pasos que tendriamos que hacer a mano si hacemos lo del texto anterior:

1. Renombrar el archivo manualmente
2. git rm  para eliminar el archivo con git
3. git add para agregar el archivo con el nuevo nombre


# Branching and merging

Los siguientes ejercicios los debes realizar en tu máquina real, no es necesario que los subas a un repositorio en github. Indica los pasos seguidos para realizar cada ejercicio en este mismo fichero.

1. Crea un directorio llamado _**branch_time**_
mkdir branch_time

2. Cámbiate a dicho directorio.
cd branch_time

3. Inicializa un repositorio vacío.
git init

4. Crea un fichero llamado first.txt después añade y haz commit con un solo comando.
nano first.txt
 git commit -m "prueba"

5. Crea una nueva rama llamada _**amazing_feature**_.
 git checkout -b rama

6. Cámbiate a dicha rama.
7. Crea un nuevo fichero llamado best.txt con el contenido "this is the best file".
nano best.txt

8. Añade el fichero al área de preparación.
git add best.txt

9. Haz commit del fichero con el mensaje "added best.txt".
git commit -m "added best.txt"

10. Vuelve a la rama master.
git checkout master

11. Une (merge) la rama feature a la rama master.
git merge rama

12. Borra la rama feature.
git branch -d rama

13. Crea la rama _**conflict**_ y cámbiate a ella con un solo comando.
git checkout -b conflict

14. Crea tu propio conflicto al mezclar dos ramas! Para ello trabaja en el mismo fichero en dos ramas separadas y une (merge) las dos ramas. Arregla los conflictos y finaliza la unión. En el mundo real nunca intentarás crear un conflicto en una unión de ramas, pero es importante que no te sientas intimidado por los conflictos al realizar una unión de ramas y ser capaz de arreglarlos con confianza.


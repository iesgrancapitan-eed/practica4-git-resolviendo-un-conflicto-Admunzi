1. Asegúrate de que tienes configurado el editor Visual Studio Code como tu editor de Git. (git config --global core.editor "code --wait")

![Imagen 1](imgs/imagen1.PNG)

2. Crea un repositorio local y avanza en la rama "master" añadiendo un fichero "index.html" con la estructura básica html. El body estará vacío

![Imagen 2](imgs/imagen2.PNG)

3. Crea y salta a "rama-1". Avanza en un commit con tu nombre de pila en un párrafo dentro del body

![Imagen 3](imgs/imagen3.PNG)

4. Vuelve a la rama master

![Imagen 4](imgs/imagen4.PNG)

5. Crea y salta a "rama-2". Avanza en un commit con tu apellido en un párrafo dentro del body

![Imagen 5](imgs/imagen5.PNG)

6. Muestra el estado del repositorio de forma gráfica y resumida

![Imagen 6](imgs/imagen6.PNG)

7. Haz un merge a rama-1. Intentas fusionar ambas ramas. Aparecerá un conflicto porque ambos commits trabajan en la misma porción <body></body> de un mismo archivo index.html. Git no será capaz de fusionarlas directamente. 

![Imagen 7](imgs/imagen7.PNG)

8. El editor VS Code reconoce los conflictos de fusión. Las diferencias se resaltan y hay acciones en línea para aceptar los cambios. Deja un único párrafo con tu nombre de pila y apellido.

![Imagen 2](imgs/imagen8.PNG)

9. Una vez que se resuelto el conflicto confirma el archivo en conflicto para que pueda realizar esos cambios

![Imagen 9](imgs/imagen9.PNG)

10. Muestra de nuevo el estado del repositorio de forma gráfica y resumida

![Imagen 10](imgs/imagen10.PNG)

11. Vuelve a la rama master y realiza otro merge. Es una fusión fast-forward. Los dos commits a fusionar tienen relación de ancestro. Entonces el merge no produce un commit nuevo, sencillamente avanza la rama, "avance rápido"

![Imagen 11](imgs/imagen11.PNG)

12. Visualiza las ramas que han sido fusionadas con la rama master

![Imagen 12](imgs/imagen12.PNG)

13. Elimina las ramas correctamente fusionadas (sin asterisco) para quedarte SOLO con la rama master. 

![Imagen 13](imgs/imagen13.PNG)

14. Realiza una copia a este repositorio remoto


15. Recuerda añadir estas instrucciones con los pantallazos en el fichero README.md


16. En GitHub entra en Insights/network y visualiza el gráfico del repositorio con los merge y cinco commits  
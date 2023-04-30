# Esta es la documentacion del proyecto

## Estado de git

- Espacio de trabajo
    - git en este estado no les da seguimiento
- Area de preparacion
    - git prepara los archivos para indicar que se realizo
- Repositorio


## comandos

- git status
    > este nos indica el estado de los archivos que estan en el espacio de trabajo

- git add
    > este comando de git pasa los archivos que tenemos en el espacio de trabajo al area de preparacion
- git commit
    > este comando nos permite pasar los archivos del area de preparacion al repositorio, se debe de ingresar un mensaje que indique lo que se realizo

- git commit -am "Mensaje del commit"
    > este comando realiza el paso de mandar el espacio de trabajo, pasando por el area de preparacion llendo gasta el reporsitorio en un solo comando pero que solo trabaja con los archivos modificados

- git checkout <archivo del cual se quiere deshacer el cambio>
    > este comando deshace los cambios que se han realizado en un archivo desde el ultimo commit

- git checkout -f
    > este comando fuerza a deshacer todos los cambios desde el ultimo commit pero de todos los archivos

- git restore --staged <Nombre del archivo que se quiere sacar del area de preparacion>
    > este comando puede sacar del area de preparacion los archivos que hemos agregado del area de trabajo

- git diff <archivo>
    > este comando muestra las diferencias o cambios que se han realizado con respecto a lo que ya esta almacenado en el repositorio

- git checkout <hahs del commit a cual se quiere volver para revisar>
    > este comando permite volver a una de los commits anteriores para poder revisarlo u o cambiarlo

- git checkout master
    > este comando se usa cuando no se esta en el ultimo commit para volver a el ultimo
    
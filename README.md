Entrego el exámen, les cuento un poco de cómo lo encaré.

Al principio me sentí un poco abrumado por tanta funcionalidad en un modal pero luego lo diagramé en un cuaderno y pude encontrar el método.
Implementé el uso Material UI como librería de componentes, su uso no me convenció del todo, ya que se hace complicado customizar los componenetes, por esto mantuve el css global para cambios puntuales.

Utilicé HOOKS, para simular una app grande donde los datos deben fluir a lo largo del árbol de componenetes. Mi principal preocupación era la magnitud del form por sus campos y funcionalidad, ante esto lo fragmenté en secciones/componenetes que se derivan en un form padre. Por temas de tiempo no pude hacer un post en Firebase, lo tenía planeado para consolidar el objetivo del form. Agregué los comentarios necesario, de haber cosas confusas o mal explicadas, pueden preguntar.

En testing no tengo conocimientos y estuve viendo un poco de git-flow, se ve muy bueno pero no alcancé a implementarlo, de seguro estudiaré sobre estos temas más allá de la decisión que tomen.






# Project requirement

### Introduccion
Este es el test de frontend. La idea es que demuestres todos tus conocimientos en desarollo y que idealmente le permita tanto a otros colegas como a clientes conocer tus habilidades no solo como programador que escribe código, sino como desarrollador que resuelve problemas.

### Diseño de UI
La UI a implementar deberia reproducir el siguiente diseño: http://www.landhsoft.com/UI-test.png

### Stack
La idea es que este challenge se resuelva usando React / JavaScript / HTML / CSS.

### Implementación

Implementar la siguiente ventana (debería ser un popup que se levanta cuando se abre el sitio).
* 'Select the school' debería permitir al usuario seleccionar una escuela dentro de una lista del 10 escuelas hardcodeadads.
* Admision type debería ser un combo con 4 opciones hardcodeadas.
* La implementación debería chequear que el usuario ingrese un monto en todos los campos (Institution, Government, etc). En caso de no ingresar mostrar mensaje de error debajo del campo de input de monto.
* Si el usuario chequea el campo 'Yes, it's renewable' se debería computar por 4 (la duración de la carrera) ese monto.
* Total Grants & Scholarshipts debería presenter la suma de los campos anteriores atendiendo el caso en que sea renovable

### Deseables
* Uso de gitflow
* Uso de UnitTest, Integration Test o algún tipo de test que ayude a garantizar buena calidad del código
* Documentación del código (buenos comentarios en casos que sirvan)


# Implementation

### Available Scripts

In the project directory, you can run:

#### `yarn start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

#### `yarn test`

Launches the test runner in the interactive watch mode.<br />

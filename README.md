Repositorio para interactuar entre usuarios de Git

# Glosario de términos relacionados con Git y GitHub

## Repository (Repositorio)

Un repositorio se utiliza generalmente para organizar un solo proyecto. Los repositorios pueden contener carpetas y archivos, imágenes, videos, hojas de cálculo y conjuntos de datos, todo lo que un proyecto necesite. Se recomienda incluir un README o un archivo con información sobre su proyecto. GitHub facilita la adición de uno al mismo tiempo que crea su nuevo repositorio. También ofrece otras opciones comunes, como un archivo de licencia.

### Crear un nuevo repositorio

1. En la esquina superior derecha, junto a tu avatar, haga clic en `+` y luego selecciona **New repository**.

2. Nombre su repositorio como `hello-world`

3. Escriba una corta descripción

4. Seleccione **Initialize this repository with a README**

5. Haga click en **Create repository**

## Branching (Ramificación)

La ramificación es la forma de trabajar en diferentes versiones de un repositorio al mismo tiempo.

De forma predeterminada, su repositorio tiene una rama llamada `master` que se considera como la rama definitiva. Se usan ramas para experimentar y hacer ediciones antes de hacer commit a `master`.

Cuando se crea una rama distinta a la rama `master`, se está realizando una copia, o una foto instantánea, del `master` tal como estaba en ese momento del tiempo. Si alguien hizo cambios en la rama `master` mientras trabajaba en su branch, podría obtener esas actualizaciones.

Este diagrama muestra:

+ La rama `master`

+ Una nueva rama llamada `feature` 

+ El viaje que `feature` toma antes de que se funda en el `master`

GRAFICA DE BRANCH

¿Ha guardado distintas versiones de un archivo? Algo así como:

+ story.txt

+ story-joe-edit.txt

+ story-joe-edit-reviewed.txt 

Las ramas logran objetivos similares en los repositorios de GitHub.

En GitHub, los desarrolladores, escritores y diseñadores usan ramas para mantener separadas las correcciones de errores y el trabajo destacado de la rama `master` (producción). Cuando un cambio está listo, se fusionan la rama `master`.

### Para crear una nueva rama

1. Vaya a su nuevo repositorio `hello-world`

2. Haga click en la lista despleagable en la parte superior de la lista de archivos, donde dice branch: master

3. Digite el nombre de la rama `readme-edits` dentro del cuadro de texto de la nueva rama

4. Seleccione el cuadro azul **Create branch** o presione "Enter" en su teclado.

Ahora tiene dos ramas, `master` y `readme-edits`. Se ven exactamente iguales, pero no por mucho tiempo. A continuación agregaremos nuestros cambios a la nueva rama.

## Realizar cambios y hacer commit

¡Listo! Ahora, está en la vista de código de su rama `readme-edits`, que es una copia de `master`. Hagamos algunos cambios.

En GitHub, los cambios guardados se llaman _commits_. Cada commit tiene un _commit message_ (mensaje de confirmación) asociado, el cual es una descripción que explica por qué se realizó un cambio particular. Los mensajes de confirmación capturan el historial de sus cambios, así otros contribuyentes pueden entender lo que usted ha hecho y por qué.

### Realizar cambios y hacer commit

1. Haga click en el archivo `README.md`

2. Haga click en el ícono del lapiz en la esquina superior derecha de la lista de archivos para editar

3. En el editor, escriba algo.

4. Escriba un mensaje de confirmación que describa sus cambios

5. Haga click en el botón **Commit changes**

Estos cambios se harán sólo en el archivo README de su rama de `readme-edits`, por lo que ahora esta rama contiene contenido que es diferente a la rama `master`.

## Abrir un Pull Request

Ahora que tiene cambios en una rama distinta a la `master`, puede abrir un **pull request** (solicitud de extracción).

Las solicitudes de extracción son el corazón de la colaboración en GitHub. Cuando abre una solicitud de extracción, está proponiendo los cambios y solicitando que alguien revise y extraiga su contribución y los fusione en la rama de ese alguien. Las solicitudes de extracción muestran _diffs_, o diferencias, del contenido de ambas ramas. Los cambios, adiciones y sustracciones se muestran en verde y rojo.

Tan pronto como realice un commit, puede abrir una solicitud de extracción e iniciar una discusión, incluso antes de que finalice el código.

Mediante el uso del sistema @mencion de GitHub en su mensaje de solicitud de extracción, puede solicitar retroalimentación de personas o equipos específicos, ya estén cerca o a zonas horarias de distancia.

Incluso puede abrir solicitudes de extracción en su propio repositorio y fusionarlas usted mismo. Es una gran manera de aprender el flujo de GitHub antes de trabajar en proyectos más grandes.

### Abrir un Pull Request para hacer cambios en el README

1. Haga click en el botón **Pull Request**, luego, desde la página de solicitud de extracción, haga click en el botón verde **New pull request**

2. Seleccione la rama alterna que creó, `readme-edits` para compararlo con `master` (el original)

3. Revise los cambios en los diffs en la página Compare, asegúrese de que son los que desea enviar.

4. Cuando esté satisfecho de que se trata de los cambios que desea enviar, haga clic en el botón verde **Create pull request**.

5. Dele un título a su solicitud de extracción y escriba una descripción breve de sus cambios.

6. Cuando haya terminado con su mensaje, haga clic en **Create pull request**.

**Tip:** Puede utilizar emojis y arrastrar y soltar imágenes y gifs en los comentarios y solicitudes de extracción.






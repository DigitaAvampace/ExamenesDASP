# ExamenesDASP
Para subir los exámenes de Digitalización
# Exámenes DASP

Este repositorio contiene una serie de exámenes de opción múltiple de nivel universitario basados en contenidos de transformación digital, protección de datos y seguridad en la economía digital.

## Estructura del repositorio


- **/examenes/**: Carpeta que contiene los archivos JSON de cada examen.
- **indice.json**: Archivo JSON que lista todos los exámenes y sus rutas relativas.
- **index.html**: Página web que permite seleccionar, cargar y resolver un examen.  
  - El usuario puede responder las preguntas, enviar el examen y se mostrará el resultado junto con el banco de explicaciones para cada pregunta.
- **README.md**: Este archivo, que explica la estructura y el uso del repositorio.

## Uso

1. Abre el archivo `index.html` en tu navegador.
2. Selecciona el examen deseado desde el menú desplegable y haz clic en **"Cargar Examen"**.
3. Responde las preguntas del examen.
4. Al enviar el examen, se verifican las respuestas y se muestra el puntaje junto con las explicaciones de cada pregunta.

## Notas

- Los archivos de examen (`examen1.json` a `examen9.json`) deben estar ubicados en la carpeta `/examenes/` según la ruta indicada en `indice.json`.
- Puedes modificar o ampliar los exámenes editando los respectivos archivos JSON.
- La comprobación de respuestas y la visualización de explicaciones se realizan de manera dinámica mediante JavaScript en `index.html`.

¡Disfruta estudiando y evaluando tus conocimientos con estos exámenes!


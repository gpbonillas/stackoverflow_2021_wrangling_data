# Wrangling Data - Stack Overflow Annual Developer Survey 2021

Este repositorio contiene el notebook que permitió realizar el preprocesamiento del dataset con los resultados de la _Encuesta Anual de desarrolladores Stack Overflow 2021_, que se encuentra en el respectivo [portal](https://insights.stackoverflow.com/survey). 


Se ha seleccionado este [dataset](https://info.stackoverflowsolutions.com/rs/719-EMH-566/images/stack-overflow-developer-survey-2021.zip) porque examina todos los aspectos de la experiencia de los programadores de la comunidad (Stack Overflow), desde la satisfacción profesional y la búsqueda de empleo hasta la educación y las opiniones sobre el software de código abierto.

## Contenido 

El contenido del repositorio es:

1. **Notebook (M2.859_20211_A9_gbonillas)**: Es el archivo *.ipynb* (se abre y ejecuta con Jupyter Notebook) y que contiene todo el código que permite realizar las tareas de limpieza y filtros previo a la carga de los datos en el portal [Flourish Studio](https://flourish.studio/).

2. **environment_uoc20211A9.yml**: Archivo que contiene la configuración del ambiente de ejecución del notebook.

3. **survey_results_public.csv**: Dataset de los reusltados de la encuesta realizada a los programadores de la comunidad de Stack Overflow en el 2021. Se obtuvo desde el portal.

4. **flourish_data/** : Directorio que contiene todo los datos que se cargaron a Flourish Studio para responder las cuestiones planteada en la práctica.

5. **docs/** : Directorio que contiene los documentos generados a partir del notebook. Hay 2 archivos, uno en formato PDF y otro en formato HTML.

6. **LICENSE**: Archivo que contiene la declaración de la licencia usada para este proyecto. En este caso se ha usado la licencia MIT.

7. **README.md**: Archivo que contiene una breve descripción del proyecto

## Cuestiones a responder

Con esta visualización se pretende responder las siguientes preguntas:

- Según la autodeterminación de la etnia, ¿Qué etnia tiene un mayor sueldo anual?
- ¿Cuáles son los porcentajes de programadores que trabajan a tiempo completo, medio tiempo o freelance?
- ¿Cuáles son los países con mayor número de programadores profesionales que son activos en la comunidad Stack Overflow?
- ¿Cuál es el nivel educativo que mayores ingresos registra entre los encuestados?
- ¿Existe brecha salarial entre hombres y mujeres u otros géneros?, y de ¿Cuánto es la diferencia? ¿Cuáles son los peores países en cuanto a brecha salarial? ¿Cuáles son los países que han reducido esta brecha salarial entre programadores?
- ¿Cuáles son los ingresos promedios según los rangos de edad? ¿Cuál es el rango de edad con el mejor y peor ingreso?
- ¿Cuáles son las tecnologías que permiten tener un mejor ingreso salarial anual?
- ¿Cuántas tecnologías en promedio domina un programador profesional?
- ¿En qué rango de edad se inició la mayoría de los programadores en la programación?
- ¿Cuántos años como programadores se requiere para obtener un ingreso salarial alto?
- ¿Cuáles son los perfiles que registran los mejores ingresos?
- ¿Cuáles son las 10 tecnologías más usadas entre los programadores por países?
- ¿Cuáles el sistema operativo más usado entre los encuestados?
- ¿Qué proporción de programadores tiene algún desorden mental por país?
- ¿Cuáles son los países que tienen los mejores sueldos entre los programadores?
- ¿Cuáles son los 10 lenguajes de programación más usados entre los programadores?
- ¿Cuáles son las bases de datos más usadas entre los programadores?
- ¿Cuáles son las plataformas más usadas entre los programadores?
- ¿Cuáles son los frameworks web más usados entre los programadores?
- ¿Cuáles son las herramientas tecnológicas más usadas entre los programadores?
- ¿Cuáles son las herramientas colaborativas más usadas entre programadores?
- ¿Cuáles son los países con mayor número de programadores trabajando a tiempo completo?

## Respuesta a las cuestiones

Las respuestas a las preguntas planteadas previamente se encuentran en la visualización de tipo storytelling publicada en [Flourish](https://public.flourish.studio/story/1092327/)


## Licencia

* **Licencia del repositorio**: *MIT License*
* **Licencia del dataset**: *Open Database License* [ODbL](http://opendatacommons.org/licenses/odbl/1.0/). You are free to share, adapt, and create derivative works from The Public 2020 Stack Overflow Developer Survey Results as long as you attribute Stack Overflow, keep the database open (if you redistribute it), and continue to share-alike any adapted database under the ODbl.
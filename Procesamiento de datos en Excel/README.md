# README - PF SANCHO Dashboard

## Descripción

El Dashboard "PF SANCHO" es una herramienta diseñada para mostrar datos analizados de tres tablas: "general_data," "manager_survey_data," y "employee_survey_data." Este Dashboard se enfoca en el análisis exploratorio de Recursos Humanos (RRHH) de una empresa. A continuación, se detallan la fuente de los datos, el uso del Dashboard y los criterios utilizados a lo largo del trabajo.

## Estructura de Archivos

El archivo "PF SANCHO.xlsx" contiene el Dashboard principal. También encontrará:

- Una hoja auxiliar con tablas dinámicas utilizadas en los gráficos.
- Hoja de Preguntas y Respuestas (Q+A) de la preentrega.
- Las tablas originales de los datos y la auxiliar están ocultas para simplificar la visualización para la entrega del Trabajo Final.

## Fuente de los Datos

Los datos utilizados en este proyecto se obtuvieron de tres tablas descargadas de Kaggle:

- "general_data": Contiene información general sobre los empleados.
- "manager_survey_data": Incluye datos relacionados con las encuestas de los gerentes.
- "employee_survey_data": Contiene datos de las encuestas realizadas a los empleados.
- "data_dictionary": Proporciona una descripción detallada de las variables y campos presentes en las tablas principales, así como la validación de datos.

## Uso del Dashboard

El Dashboard "PF SANCHO" permite a los usuarios explorar y analizar los datos de RRHH de la empresa de manera interactiva. Los elementos clave del Dashboard incluyen:

- Cinco gráficos de torta que muestran información en porcentajes.
- Un gráfico de barras al 100%.
- Un gráfico de barras apiladas que muestra las edades de los empleados.
- Dos segmentadores que permiten filtrar los datos por género y departamento de la empresa.

## Criterios Utilizados

A lo largo del trabajo, se aplicaron criterios específicos para analizar y visualizar los datos de RRHH:

- Se calcularon porcentajes en los gráficos de torta para resaltar la distribución de género, nivel educativo, estado civil, rendimiento y otros aspectos.
- Los segmentadores permiten a los usuarios filtrar los datos según sus preferencias para obtener información detallada sobre género y departamento.
- El gráfico de barras al 100% muestra la distribución de los empleados en diferentes categorías.
- El gráfico de barras apiladas presenta la edad de los empleados de manera desglosada.

## Correcciones de los Datos

Los datos han sido importados de una base de datos de Kaggle.com, y se realizaron las siguientes correcciones:

- Corrección del orden de las columnas.
- Adición de datos en la hoja data_dictionary para la utilización de la validación de datos.

## Notas Adicionales

- Los segmentadores se guardan por defecto de Excel como filtro individual. Para corregir esto, puedes presionar el botón derecho sobre el segmentador y seleccionar la opción "Selección múltiple de 'Departamento'" (o "Género" según corresponda).
- El segmentador de género no afecta al gráfico de género, ya que el objetivo del gráfico es mostrar la diferencia en los departamentos seleccionados.

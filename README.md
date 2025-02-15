# Proyecto end to end: Ciclo completo de datos para postulaciones de trabajo
__Flujo completo de datos por AppSheet, Google Sheets y Looker Studio__

<image src="https://github.com/BastianLQ/Analisis-de-postulaciones-en-tiempo-real/blob/main/Images/banner.png" alt="banner">

## Descripción del proyecto
Este proyecto trata de la costrucción de un ciclo completo de datos para seguir mis postulaciones de trabajo en análisis de datos. Los datos son recopilados mediante una app que creé usando AppSheet, donde pasan a ser almacenados en una hoja de Google Sheets y, finalmente, ser analizados usando Looker Studio en tiempo real.

## Herramientas utilizadas
- Appsheet.
- Google Sheets.
- Looker Studio.

## Proceso del proyecto
- __Definir la base de datos:__ Considerando que las postulaciones serán entre 7 y 10 a la semana, lo más apropiado es algo simple y modificable, como Google Sheets.
- __Definir las variables a estudiar:__ Para este caso, mi interés fue recopilar:
  - __Nombre de la empresa__.
  - __Rubro de la empresa__.
  - __Fecha de postulación__,
  - __Plataforma de postulación__,
  - __Estado de postulación__ (postulación enviada, vista, entrevista, etc.)
  - __Seniority de la posición (trainee, junior, ssr, etc.)__.
  - __Área/modalidad de trabajo (remoto, hibrido santiago, presencial santiago, etc.)__
 
<image src="https://github.com/BastianLQ/Analisis-de-postulaciones-en-tiempo-real/blob/main/Images/sheets.jpg" alt="Sheets">

- __Desarrollar el formulario de la app:__ Usando AppSheet desarrollé una app para trackear las postulaciones priorizando ahorrar el máximo tiempo posible. Esto se logró gracias a que:
  - Implementé listas desplegables en la mayoría de los campos.
  - Dejé valores predeterminados en los siguientes campos:
    - __Fecha de postulación:__ Mostrará de forma predeterminada la fecha en la que se está ingresando a la app.
    - __Estado de postulación:__ El estado inicial de una postulación siempre será "Postulación enviada".
    - __Plataforma de postulación:__ La plataforma que más uso es LinkedIn, por ende, está predeterminada en la lista de opciones.
- __Desarrollar la vista de tabla de la app:__ La app también tiene una vista de tabla, que permite modificar los registros existentes, esto es útil para actualizar el estado de las postulaciones y para corregir errores de tipeo al ingresar datos.
- __Creación del panel de control en Looker Studio:__ Finalmente nos conectamos a la hoja de cálculo desde Looker Studio y construímos un panel interactivo para seguir los principales objetivos de la postulación, que son:
  - Realizar mínimo 7 postulaciones semanales.
  - Completar 200 postulaciones.
  - Encontrar trabajo remoto.
  - Apuntar a vacantes Junior o Trainee.

## Resultados del proyecto
- Tardo menos de 5 segundos en registrar mis postulaciones, que es __la tercera parte de lo que tardaba antes__.
- Si recibo una actualización del estado de postulación, __puedo actualizarla en segundos desde mi smartphone__.
- Si no tengo internet, la app igual funcionará, y los cambios serán ingresados cuando vuelva a tener conexión.
- Gracias al panel automatizado, puedo identificar rápidamente las áreas a mejorar y las estrategias que me quedan por probar.


                                                              


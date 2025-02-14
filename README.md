# Proyecto end to end: Ciclo completo de datos para postulaciones de trabajo
__Flujo completo de datos por AppSheet, Google Sheets y Looker Studio__

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
- __Desarrollar el formulario de la app:__ Usando AppSheet desarrollamos una app para trackear las postulaciones priorizando ahorrar el máximo tiempo posible. Esto se logró gracias a que:
  - Implementé listas desplegables en la mayoría de los campos.
  - Dejé valores predeterminados en los siguientes campos:
    - __Fecha de postulación:__ Mostrará de forma predeterminada la fecha en la que se está ingresando a la app.
    - __Estado de postulación:__ El estado inicial de una postulación siempre será "Postulación enviada".
    - __Plataforma de postulación:__ La plataforma que más uso es LinkedIn, por ende, está predeterminada en la lista de opciones.

                                                              


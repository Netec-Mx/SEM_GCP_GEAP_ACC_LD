# Demostración para Instructores - Gemini Enterprise: IA para encontrar, entender y actuar

El propósito de este documento es sugerir la demostación que el instructor puede realizar durante la entrega del seminario Gemini Enterprise: IA para encontrar, entender y actuar. Los siguientes pasos son generales, se entiende que el instructor tiene las habilidades para comprenderlo. Están organizados en orden de los slides de Power Point adjuntos. 

## Formular una pregunta sobre varias fuentes empresariales

* Ingresar a GCP, luego a Gemini Enterprise y ver las diversas fuentes desde donde se pueden crear data stores.
* Ingresar a BigQuery, crear un data set, crear una tabla con datos de ejemplo.
* Crear un data store en gemini con conexión a BigQuery
* Probar con una consulta en Gemini

## Resumir y comparar varios documentos

* Cargar documentos desde varias fuentes en Gemini y solicitar comparar y resumir

## Recorrer la galería de agentes y seleccionar un agente según una necesidad concreta de negocio

* Ingresar a Gemini y buscar los agentes disponibles en la galería, creados por google y del marketplace
* Ingresar a Gemini en GCP y ver cómo activar y desactivar agentes o agregar nuevos. 

## Utilizar un agente de investigación para recopilar, sintetizar y presentar información

* Usar Deep Research para una investigación. (Hacerlo con anticipación porque el resultado se requiere analizar en una demo más adelante)

## Utilizar un agente especializado para convertir información en un entregable

* Usar Gemini Notebook para convertir información de varias fuentes en un entregable. 

## Observar un flujo de varios pasos en el que el agente consulta información, procesa la solicitud y entrega un resultado final

* Volver a Deep Reseach y validar el flujo de razonamiento autónomo y el entregable. 

## Preparar un brief para una reunión comercial utilizando información distribuida

* Depende si tienes acceso a Google Workspace o no:
  - Si tienes Google Workspace, habilitar la integración desde Gemini (App), solicitar extraer información de correos, chats, calendarios, etc (previamente creados para esta demo) y lanzar la solicitud del brief
  - Si no, entonces usar documentos en Cloud Storage

## Localizar una política o procedimiento interno y convertirla en un checklist para el usuario

* Crear un bucket de Cloud Storage, agregar algunos documentos con políticas y procedimientos de ejemplo en PDF, cargarlos como data store en Gemini y realizar la consulta. 

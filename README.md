# Estudio AG — Automatización de Registro de Clientes

## Descripción

Proyecto de automatización desarrollado con n8n para optimizar la gestión de consultas de una barbería ficticia llamada Estudio AG.

El sistema permite recibir solicitudes de clientes, registrar sus datos automáticamente y enviar notificaciones por correo electrónico al administrador del negocio.

## Problema que resuelve

En muchos pequeños negocios, las consultas de clientes se registran manualmente, lo que consume tiempo y puede ocasionar errores u olvidos.

Esta automatización permite centralizar la información y reducir las tareas administrativas repetitivas.

## Funcionamiento

1. El cliente completa un formulario con su nombre, teléfono y servicio solicitado.
2. n8n recibe la información.
3. Google Sheets registra automáticamente los datos en una planilla.
4. Gmail envía una notificación al administrador con los detalles de la consulta.

## Tecnologías utilizadas

- **n8n:** creación y ejecución del workflow.
- **Google Sheets:** almacenamiento de las consultas.
- **Gmail:** notificaciones automáticas por correo.
- **n8n Form Trigger:** recepción de datos mediante formulario.

## Cómo utilizarlo

1. Importar el archivo `Estudio_AG_workflow_publico.json` en n8n.
2. Conectar una cuenta de Google Sheets y seleccionar una planilla con las columnas correspondientes.
3. Conectar una cuenta de Gmail y configurar el destinatario.
4. Ejecutar una prueba del workflow.
5. Publicar el workflow en n8n para recibir nuevas consultas mediante el formulario de producción.

## Resultados

El workflow fue probado satisfactoriamente:

- Recepción de datos mediante formulario.
- Registro automático en Google Sheets.
- Envío automático de notificaciones por Gmail.

## Alcance

Esta primera versión registra consultas de clientes. No confirma reservas ni comprueba disponibilidad de horarios.

## Estado del proyecto

Primera versión funcional completada.

**Proyecto de portfolio — AI Automation.**

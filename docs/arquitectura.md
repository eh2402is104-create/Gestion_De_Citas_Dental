
# Arquitectura del Sistema

## Módulos principales

- Consulta de horarios disponibles.
- Registro de citas.
- Confirmación o aviso de disponibilidad.
- Sugerencia de horarios alternativos.

## Arquitectura propuesta

El sistema se organizará en tres partes:

1. **Interfaz de usuario:** permite consultar horarios e ingresar los datos de la cita.
2. **Lógica de aplicación:** revisa la disponibilidad y propone horarios alternativos.
3. **Base de datos:** se contempla para almacenar usuarios, horarios y citas en una futura versión.

## Funcionamiento

El usuario selecciona un horario y proporciona sus datos. El sistema verifica la disponibilidad y muestra una confirmación o sugiere hasta tres horarios alternativos.

## Estado actual

La arquitectura es una propuesta para el prototipo. La base de datos todavía no está conectada.

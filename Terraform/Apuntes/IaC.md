# Infraestructura como codigo

## Principios

- Los sistemas se pueden reproducir fácilmente
- Los sistemas son desechables
- Los sistemas son consistentes
- Los sistemas son repetibles
- El diseño siempre esta cambiando

## Pŕacticas generales

- Utilizar archivos de definición
- Sistemas y procesos autodocumentados
- Versionar todas las cosas
- Preferir cambios pequeños
- Mantener los servicios continuamente disponibles

## Archivos de definición

Son archivos que sirven para impulsar la implementación.

## Herramientas para definición de Infraestructura

- Permiten especificar recursos de Infra se desean crear y como debe configurarse

## Herramientas para configuración de Infraestructura

- Nos permite configurar los servidores con el estado deseado.

### Aprovisionamiento

Es el proceso que permite que un elemento este listo para usarse.

## Factores a tener en cuenta

- Modo desatendido para herramientas de linea de comandos
- Idempotencia
- Parametrizable

## Objetivos de la automatización

- Los servidores pueden ser aprovisionados a demanda.
- Un nuevo servidor puede ser aprovisionado sin interversión humana.
- Cada cambio puede ser aplicado a un conjunto de servidores.
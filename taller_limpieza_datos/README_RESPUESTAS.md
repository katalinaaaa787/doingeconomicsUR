# Respuestas del estudiante

**Nombre:**
Tannia Katalina Matallana Castro

**Usuario de GitHub:**
katalinaaaa787
## 1. Diagnóstico del archivo

**Delimitador identificado:**
El archivo usaba como delimitador el punto y coma (;) para separar variables.

**Codificación identificada:** 
La base de datos se encontraba en codificación UTF-8; sin embargo, algunos caracteres especiales como tildes y la letra ñ presentaban errores de visualización, por lo que se realizaron ajustes en las variables afectadas.

**Problemas encontrados en las fechas:**
Las fechas presentaron múltiples problemas de entradas que no cumplían con el formato AAAA-MM-DD.

**Problemas encontrados en las variables numéricas:**
Se encontraron valores numéricos que podían estar representados como texto o formatos inconsistentes 

**Problemas encontrados en las variables de texto:**
Se encontraron espacios adicionales, diferencias en mayúsculas y minúsculas, y errores de escritura en algunos nombres.

**Valores usados para representar datos faltantes:**
Se identificaron valores como "NA" y otros registros representados como ausencia de información.


## 2. Decisiones de limpieza

Explique brevemente las principales decisiones que tomó:

1. Se unificaron los formatos de las variables de la base de datos con el propósito de que la información pudiera ser utilizada correctamente en los análisis.
2. Depure las variables de tipo texto mediante la corrección de inconsistencias como espacios innecesarios, diferencias en escritura y errores asociados a caracteres especiales.
3. Se realizó una revisión general de la información antes del análisis, verificando que los datos fueran coherentes y que las modificaciones aplicadas respondieran únicamente a problemas identificados durante el proceso de limpieza.

## 3. Enlace de entrega

https://github.com/katalinaaaa787/doingeconomicsUR/blob/main/taller_limpieza_datos/scripts/limpieza_base_datos.r


# Taller integrador individual — Cortes 1 y 2

**Estudiante:** Samuel Domínguez

## Descripción

Este proyecto consiste en auditar y corregir una calculadora web que calcula el promedio de tres notas y muestra si el estudiante aprueba o reprueba.

## Hallazgos de la auditoría

| Defecto encontrado | Por qué era un problema | Cómo se corrigió |
|---|---|---|
| Nombre de archivo HTML con espacios y mayúsculas | Dificulta mantener una convención uniforme. | Se renombró a `index.html`. |
| Nombre de archivo CSS con espacios y mayúsculas | Puede generar confusiones al enlazar archivos. | Se renombró a `styles.css`. |
| Título genérico de la página | No describe claramente el contenido. | Se cambió a `Calculadora de notas`. |
| Variables con nombres poco descriptivos | No permiten entender fácilmente su propósito. | Se utilizaron nombres como `cantidadNotas` y `promedio`. |
| Función llamada `calc()` | El nombre no explica su función. | Se cambió a `calcularPromedio()`. |
| Identificadores `n1`, `n2` y `n3` | No describen claramente los datos que almacenan. | Se cambiaron a `nota1`, `nota2` y `nota3`. |
| Identificadores `r` y `r2` | No explican qué resultado presentan. | Se cambiaron a `promedioResultado` y `estadoResultado`. |
| Variable sin uso y código antiguo comentado | Aumentaban el código innecesariamente. | Se eliminaron. |
| Selectores CSS desactualizados | No coincidían con los nuevos identificadores del HTML. | Se actualizaron los selectores de los resultados. |
| Código duplicado después de `</html>` | Dejaba contenido innecesario fuera del documento. | Se eliminó el bloque duplicado. |

## Tecnologías utilizadas

- HTML
- CSS
- JavaScript
- Git y GitHub

## Enlace al sitio publicado

https://calculadora-notas-samuel.netlify.app

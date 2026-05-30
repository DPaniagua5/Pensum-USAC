# Escanear Notas

El módulo de escaneo extrae automáticamente tus cursos aprobados desde un PDF de notas oficial de la USAC (Actualmente funciona mejor al imprimir la pestaña de cursos aprobados dentro de tu portal de ingeniería, el certificado de cursos aprobados puede dar un mayor número de falsos positivos).

## ¿Cómo funciona?

1. Sube tu hoja de notas en PDF
2. La app extrae el texto en tu navegador (el archivo nunca sale de tu dispositivo)
3. Compara los códigos de curso encontrados con el pensum activo
4. Muestra los cursos detectados para que los revises antes de aplicar

## Requisitos del PDF

- Debe ser un PDF con texto seleccionable (no una imagen escaneada)
- Funciona con los reportes oficiales del CIG / SIA de la USAC

## Opciones al aplicar

### Ver notas y aplicar

Abre un editor donde puedes:

- Ver todos los cursos detectados con sus notas
- Editar notas si el escaneo tuvo errores
- Agregar o eliminar filas manualmente
- Ver el promedio calculado automáticamente

### Aplicar sin editar

Marca directamente todos los cursos seleccionados como ganados.

## Niveles de confianza

| Nivel | Descripción |
| :-------: | :-------------: |
| ✓ Alta | Código de curso encontrado con nota |
| ? Baja | Solo se encontró el código, sin nota |

> ⚠️ Revisa siempre los resultados antes de aplicar, especialmente los de baja confianza.

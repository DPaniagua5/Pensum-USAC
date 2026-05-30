# Pensum

El módulo de Pensum muestra todos los cursos organizados por semestre.

## Visualización

Cada curso se muestra como una card con:

- **Código** del curso
- **Nombre** del curso
- **Créditos** que da el curso al ser aprobado
- **Estado** (ganado, disponible, planeado o bloqueado)

### Colores de estado

| Color | Significado |
| :-------: | :-------------: |
| Verde | Curso ganado |
| Amarillo | Disponible para cursar |
| Azul | Planeado en el planificador |
| Gris | Bloqueado (faltan prerrequisitos) |

## Marcar un curso como ganado

Haz clic en el **checkbox** de la card del curso. Al marcar un curso, sus prerrequisitos se marcan automáticamente también.

## Ver árbol de prerrequisitos

Haz clic en cualquier parte de la card (excepto el checkbox) para abrir el **árbol de dependencias** del curso, que muestra:

- ↑ Cursos que necesitas haber ganado antes
- El curso seleccionado
- ↓ Cursos que se desbloquean al ganar este

## Filtros

- **Solo Obligatorios** — oculta los cursos opcionales y electivos
Si no se selecciona, se mostrarán todos los cursos disponibles en el pensum seleccionado.

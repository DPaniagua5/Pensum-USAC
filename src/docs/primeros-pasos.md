# Primeros pasos

## Requisitos

Solo necesitas un navegador moderno. La aplicación funciona completamente en el lado del cliente, sin necesidad de crear una cuenta.

## Abrir la aplicación

Abre el archivo `index.html` desde un servidor local o desde GitHub Pages. No funciona abriéndolo directamente como archivo (`file://`) si usas Live Server de VS Code, pero sí funciona abriéndolo como página estática normal.

## Seleccionar tu pensum

Al abrir la app, selecciona tu pensum desde el selector en el header:

```
Pensum: [ Antiguo ▼ ]
```

Cada pensum guarda su propio progreso en el navegador (localStorage), por lo que puedes cambiar entre ellos sin perder datos.

## Exportar e importar tu progreso

Puedes guardar tu progreso en un archivo JSON y cargarlo en otro dispositivo:

1. Haz clic en **Exportar** para descargar tu progreso
2. En otro dispositivo, haz clic en **Importar** y selecciona el archivo

> ⚠️ El archivo exportado incluye el pensum activo, cursos ganados, plan de semestres y promedio de zona.

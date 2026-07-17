# Bresenham-PC
Pedro Caso - 241286
Pequeño proyecto en Rust para implementar el algoritmo de Bresenham y dibujar líneas sobre un framebuffer, exportando el resultado a un archivo BMP.

## Qué hace
- Crea un framebuffer en memoria.
- Dibuja líneas con el algoritmo de Bresenham usando solo aritmética entera.
- Guarda la imagen resultante en un archivo BMP llamado `out.bmp`.

## Cómo ejecutar
Desde la carpeta del proyecto, ejecuta:

```bash
cargo run
```

El archivo generado aparecerá como `out.bmp` en la raíz del proyecto.

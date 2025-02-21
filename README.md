# Pipeline-2D-a-3D-con-Stable-Diffusion-y-Point-E

Este proyecto es una combinación sencilla pero poderosa de **Stable Diffusion** (para generar imágenes 2D) y **Point-E** (para convertirlas en nubes de puntos 3D). Perfecto para crear modelos 3D desde texto sin complicaciones.

---

## Funcionamiento del Pipeline

1. **Genera una imagen 2D**  
   Ingresa un prompt textual (e.g., "un robot futurista") y Stable Diffusion genera la imagen para ti.

2. **Conviértela a 3D**  
   Point-E toma la imagen generada y crea una nube de puntos 3D detallada.

3. **Exporta o visualiza**  
   Guarda el resultado como archivo `.ply` para usarlo en Blender o MeshLab, o simplemente visualízalo directamente.

---

## Cómo Probarlo

### Opción 1: Google Colab
- Abre el notebook `pipeline_2d_to_3d.ipynb`.
- Asegurate de cambiar el prompt por el que quieras
- Ejecuta las celdas una por una. Listo


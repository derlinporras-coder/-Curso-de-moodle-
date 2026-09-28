# Cómo montar el Momento 1 (Unidad 1) en Moodle

Entra al curso y pulsa **Modo de edición**. Todo se agrega en la sección **Momento 1**.

## Orden final de la sección (8 recursos)

| # | Tipo de recurso en Moodle | Nombre | Contenido (archivo de esta carpeta) |
|---|---|---|---|
| 1 | Área de texto y medios (Etiqueta) | *(sin nombre)* | `paginas/00_presentacion_momento1.html` |
| 2 | Foro (tipo *Foro para uso general*) | Foro: conformación de grupos y elección de la organización | `actividades/0_foro_grupos_organizacion.md` |
| 3 | Página | Tema 1. Evolución de la administración | `paginas/01_evolucion_administracion.html` |
| 4 | Página | Tema 2. Conceptos, grupos de interés y entornos | `paginas/02_conceptos_grupos_entornos.html` |
| 5 | Página | Tema 3. Primeras teorías de la administración | `paginas/03_teorias_administracion.html` |
| 6 | Cuestionario | Autoevaluación Unidad 1 (práctica, sin nota) | `preguntas/autoevaluacion_unidad1.gift.txt` |
| 7 | Página + Tarea | Caso de estudio y 1.1 Estudio de caso aplicado (10%) | `paginas/04_caso_estudio.html` + `actividades/1_estudio_de_caso.md` |
| 8 | Tarea | 1.2 Caracterización inicial de la organización (20%) | `actividades/2_caracterizacion_inicial.md` |

## A. Pegar el contenido HTML (Etiqueta y Páginas)

1. En GitHub abre el archivo `.html`, pulsa **Raw**, selecciona todo (Ctrl+A) y copia (Ctrl+C).
2. En Moodle: **Añadir una actividad o recurso → Página** (o *Área de texto y medios* para la presentación).
3. En el editor del contenido, pulsa el botón **`</>` (Código fuente / HTML)**. En TinyMCE está en *Ver → Código fuente*.
4. Pega, vuelve a la vista normal y pulsa **Guardar cambios y regresar al curso**.

## B. Foro

1. **Añadir una actividad o recurso → Foro**. Tipo: *Foro para uso general*.
2. En **Descripción** pega el texto de `0_foro_grupos_organizacion.md`.
3. **Modo de suscripción:** *Suscripción forzosa*, para que todos reciban las publicaciones.

## C. Tareas 1.1 y 1.2

1. **Añadir una actividad o recurso → Tarea**. En **Descripción** pega el texto del `.md`.
2. **Fechas de entrega:** 1.1 en la semana 3 y 1.2 en la semana 4.
3. **Tipos de entrega:**
   - 1.1: *Archivos enviados* (PDF).
   - 1.2: *Archivos enviados* y *Texto en línea* (para el enlace del video).
4. **Entrega en grupo:**
   - 1.1: individual o en parejas, según decidas.
   - 1.2: *Los estudiantes envían en grupos = Sí*.
5. En la Tarea 1.1 puedes enlazar la página del caso, o pegar el caso directamente al final de la descripción.

## D. Autoevaluación (Cuestionario de práctica)

1. Descarga `autoevaluacion_unidad1.gift.txt` desde GitHub (**Download raw file**).
2. **Más → Banco de preguntas → Importar → Formato GIFT** → sube el archivo → **Importar** → **Continuar**.
   Se crea la categoría *Unidad 1 - Autoevaluación* con 13 preguntas:
   - 11 de opción múltiple con retroalimentación.
   - 1 de emparejamiento (teorías y autores).
   - 1 de verdadero o falso.
3. **Añadir una actividad o recurso → Cuestionario** con esta configuración:
   - Intentos: **ilimitados**.
   - Comportamiento: *Retroalimentación inmediata*.
   - Calificación: si no quieres que cuente en la nota, en *Libro de calificaciones* pon su peso en 0, o déjalo fuera de la categoría del corte.
4. **Preguntas → Agregar → del banco de preguntas**, elige la categoría y agrégalas todas.

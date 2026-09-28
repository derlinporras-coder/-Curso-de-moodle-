# Cómo montar el Momento 2 (Unidad 2) en Moodle

Entra al curso y pulsa **Modo de edición** (arriba a la derecha). Todo se agrega en la sección **Momento 2**.

## Orden final de la sección

| # | Tipo de recurso en Moodle | Nombre | Contenido (archivo de esta carpeta) |
|---|---|---|---|
| 1 | Área de texto y medios (Etiqueta) | *(sin nombre)* | `paginas/00_presentacion_momento2.html` |
| 2 | Página | Tema 1. Planeación | `paginas/01_planeacion.html` |
| 3 | Página | Tema 2. Organización | `paginas/02_organizacion.html` |
| 4 | Tarea | 2.1 Taller de planeación y organización (10%) | `actividades/1_taller_planeacion_organizacion.md` |
| 5 | Página | Tema 3. Dirección y liderazgo | `paginas/03_direccion_liderazgo.html` |
| 6 | Página | Tema 4. Evaluación y control | `paginas/04_evaluacion_control.html` |
| 7 | Cuestionario | 2.2 Laboratorio de simulación: liderar, decidir y controlar (10%) | `preguntas/laboratorio_simulacion_2_2.gift.txt` |
| 8 | Tarea | 2.3 Avance 2 del proyecto integrador (10%) | `actividades/3_avance2_proyecto.md` |

## A. Pegar el contenido HTML (Etiqueta y Páginas)

1. En GitHub abre el archivo `.html` y pulsa **Raw**. Selecciona todo (Ctrl+A) y copia (Ctrl+C).
2. En Moodle: **Añadir una actividad o recurso → Página** (o *Área de texto y medios* para la presentación).
3. En el editor de *Contenido de la página*, pulsa el botón **`</>` (Código fuente / HTML)**. En TinyMCE está en *Ver → Código fuente*.
4. Pega el código, vuelve a la vista normal y pulsa **Guardar cambios y regresar al curso**.

> Si pegas el HTML sin activar el modo de código fuente, verás las etiquetas `<p>`, `<h3>`… como texto.

## B. Crear las Tareas 2.1 y 2.3

1. **Añadir una actividad o recurso → Tarea**.
2. Nombre: el de la tabla. En **Descripción** copia el texto del archivo `.md` correspondiente.
3. **Disponibilidad:** pon la fecha de entrega según el cronograma (2.1 en la semana 7, 2.3 en la semana 10).
4. **Tipos de entrega:** Archivos enviados y Texto en línea (para pegar enlaces de Canva o Trello).
5. **Configuración de entrega en grupo** (solo para la 2.3): *Los estudiantes envían en grupos = Sí*.
6. **Calificación:** 100 puntos o 5.0, según lo que use tu institución.

## C. Laboratorio de simulación 2.2 (Cuestionario)

**Paso 1. Importar las preguntas**
1. Descarga `laboratorio_simulacion_2_2.gift.txt` desde GitHub (botón **Download raw file**).
2. En el curso: **Más → Banco de preguntas → Importar**.
   En Moodle 4.x, busca el menú desplegable que dice *Preguntas* y elige *Importar*.
3. Formato: **GIFT** → arrastra el archivo → **Importar** → **Continuar**.
4. Se crea la categoría *Unidad 2 - Laboratorio de simulación* con 13 preguntas: 12 de selección con retroalimentación y 1 de ensayo.

**Paso 2. Crear el cuestionario**
1. En la sección Momento 2: **Añadir una actividad o recurso → Cuestionario**.
2. **Temporalización:** límite de 30 minutos. **Calificación:** intentos permitidos = 1.
3. **Comportamiento de las preguntas:** *Retroalimentación diferida*.
4. **Revisar opciones:** marca *Retroalimentación específica* para que el estudiante vea por qué acertó o se equivocó.
5. Guarda. Luego entra a **Preguntas → Agregar → del banco de preguntas**, elige la categoría del laboratorio, selecciona todas y agrégalas.
6. La pregunta 13 (ensayo) se califica manualmente en *Resultados → Calificación manual*.

## Pendiente

- Tus propios materiales (lecturas, presentaciones, videos) pueden ir en esta sección, debajo de cada tema.
- Fechas exactas de entrega según el calendario académico 2026-2.

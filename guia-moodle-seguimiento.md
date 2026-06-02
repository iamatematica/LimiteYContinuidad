# Guía: seguimiento por alumno en Moodle 4
### Unidad 2 — Límite y Continuidad · Campus Virtual UTN-INSPT

Esta guía te lleva paso a paso para que Moodle registre **qué alumno completó cada una
de las 7 etapas**, por usuario y sincronizado. Está pensada para tu rol de **profesor**
(no administrador). No requiere tocar código.

---

## Antes de empezar (requisito)

Las etapas tienen que estar **publicadas en GitHub Pages**, porque vas a pegar la
dirección (URL) de cada una. Si todavía no las publicaste, hacelo primero (ver el
archivo `README.md`). Vas a necesitar a mano las 8 direcciones, del tipo:

```
https://iamatematica.github.io/LimiteYContinuidad/index.html                          (campus)
https://iamatematica.github.io/LimiteYContinuidad/etapa1-limite-y-limites-laterales.html
https://iamatematica.github.io/LimiteYContinuidad/etapa2-algebra-e-infinitesimos.html
https://iamatematica.github.io/LimiteYContinuidad/etapa3-indeterminaciones.html
https://iamatematica.github.io/LimiteYContinuidad/etapa4-infinitos-y-asintotas.html
https://iamatematica.github.io/LimiteYContinuidad/etapa5-funciones-racionales.html
https://iamatematica.github.io/LimiteYContinuidad/etapa6-continuidad.html
https://iamatematica.github.io/LimiteYContinuidad/etapa7-cierre-integrador.html
```

> Reemplazá `LimiteYContinuidad` por el nombre real que le hayas puesto a tu repositorio.

---

## PASO 1 — Activar el rastreo de finalización en el curso (una sola vez)

1. Entrá a tu curso de **Análisis Matemático I**.
2. Arriba a la derecha, activá el botón **"Activar edición"** (o el ícono de engranaje
   ⚙ → "Activar edición").
   - *Si no ves ese botón:* no tenés permisos de edición en el curso. Pedíselos al
     área de sistemas (ver el recuadro "Si algo está bloqueado" al final).
3. Hacé clic en el menú **"Configuración"** del curso (pestaña arriba, junto a
   "Participantes", "Calificaciones", etc.).
4. Bajá hasta la sección **"Rastreo de finalización"**.
5. En **"Habilitar rastreo del grado de finalización"** elegí **"Sí"**.
6. Bajá del todo y tocá **"Guardar cambios"**.

> ✅ Con esto, a partir de ahora cada actividad y recurso del curso va a tener opciones
> de finalización. Si la opción "Rastreo de finalización" **no aparece** en la
> configuración, está desactivada a nivel del sitio: mirá el recuadro final.

---

## PASO 2 — Cargar la Etapa 1 como recurso URL (con seguimiento)

Vas a hacer esto una vez por etapa. Empecemos por la 1; las otras son idénticas.

1. Con la edición activada, en la sección del curso donde quieras el material, hacé
   clic en **"Añadir una actividad o recurso"**.
2. En el listado, elegí **"URL"**.
3. Completá:
   - **Nombre:** `Etapa 1 — Límite y límites laterales`
   - **URL externa:** pegá la dirección de la etapa 1.
4. *(Opcional, recomendado)* En **"Apariencia"**, en "Mostrar", elegí **"En ventana
   emergente"** o **"Abrir"** — así la etapa se abre cómoda, ocupando la pantalla.
5. Bajá hasta la sección **"Finalización de actividad"** y configurá:
   - **"Rastreo de finalización":** elegí
     **"Mostrar la actividad como completada cuando se cumplan las condiciones"**.
   - Marcá la casilla **"El estudiante debe ver esta actividad para finalizarla"**.
   - *(Alternativa más exigente:* en vez de "ver", podés dejar
     **"Los estudiantes pueden marcar manualmente la actividad como completada"**
     si preferís que el alumno confirme él mismo que la terminó. Para tu caso, "ver"
     es lo más automático y fiable.*)*
6. Tocá **"Guardar cambios y regresar al curso"**.

> Resultado: al lado de la Etapa 1 aparece un indicador de finalización. Cuando un
> alumno la abra, Moodle lo registra automáticamente.

---

## PASO 3 — Repetir para las etapas 2 a 7

Repetí exactamente el Paso 2 para cada etapa, cambiando solo **el nombre** y **la URL**:

| Recurso | Nombre sugerido | URL |
|--------|------------------|-----|
| Etapa 2 | Etapa 2 — Álgebra de límites e infinitésimos | `.../etapa2-algebra-e-infinitesimos.html` |
| Etapa 3 | Etapa 3 — Indeterminación 0/0 | `.../etapa3-indeterminaciones.html` |
| Etapa 4 | Etapa 4 — Límites infinitos y asíntotas | `.../etapa4-infinitos-y-asintotas.html` |
| Etapa 5 | Etapa 5 — Funciones racionales | `.../etapa5-funciones-racionales.html` |
| Etapa 6 | Etapa 6 — Continuidad | `.../etapa6-continuidad.html` |
| Etapa 7 | Etapa 7 — Cierre integrador | `.../etapa7-cierre-integrador.html` |

> **Consejo de orden:** podés agregar también el **campus** (`index.html`) como un
> recurso URL al principio, a modo de "portada / punto de entrada", aunque sin
> finalización — así el alumno tiene desde dónde empezar y navegar.

> **Atajo:** una vez creada la Etapa 1, podés **duplicarla** (en el menú de tres
> puntos del recurso → "Duplicar") y solo cambiarle el nombre y la URL. Ahorra clics.

---

## PASO 4 — Ver quién completó qué (el reporte)

1. En el curso, andá a **"Informes"** (en el menú del curso o en
   ⚙ → "Más" → "Informes").
2. Elegí **"Finalización de actividad"**.
3. Vas a ver una **grilla**: los alumnos en las filas y las 7 etapas en las columnas,
   con un tilde en cada etapa que el alumno completó.
4. Podés **descargarla en Excel** con el botón de descarga, para tu registro.

---

## (Opcional) PASO 5 — Finalización del curso completo

Si querés que Moodle marque "Unidad completa" cuando el alumno termine las 7 etapas:

1. En **Configuración del curso**, activá también **"Habilitar finalización del curso"**.
2. En el menú del curso aparecerá **"Finalización del curso"**.
3. Ahí elegís la condición: **"Se completan todas las actividades seleccionadas"** y
   marcás las 7 etapas. Guardás.

Así cada alumno tiene un indicador global de "Unidad 2 completada".

---

## Si algo está bloqueado (pedido al área de sistemas)

Como sos profe y no administrador, hay dos cosas que *podrían* estar desactivadas a
nivel del sitio. Si te pasa, escribíle al área de sistemas del campus. Texto sugerido:

> *Hola, soy profesor en el Campus Virtual. Estoy preparando material en mi curso de
> Análisis Matemático I y necesito usar el seguimiento de finalización de actividades.
> ¿Podrían verificar que estén habilitadas a nivel del sitio las opciones
> "enablecompletion" (rastreo de finalización) y, si es posible, "enablecompletion" a
> nivel curso? También necesitaría confirmar que tengo permisos de edición en mi curso.
> Gracias.*

Señales de que necesitás este pedido:
- En el Paso 1 no aparece la sección **"Rastreo de finalización"**.
- No ves el botón **"Activar edición"** en tu curso.

---

## Resumen en una línea

Activar rastreo en el curso (1 vez) → cargar las 7 etapas como recursos URL con
"finalizar al ver" (7 veces) → mirar el informe de Finalización de actividad. Listo:
seguimiento por alumno, sincronizado, sin tocar código.

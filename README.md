# Unidad 2 — Límite y Continuidad
### Material interactivo · Análisis Matemático I · INSPT–UTN

Material didáctico interactivo de 7 etapas más una página de inicio (campus) que las
reúne. Cada etapa es un archivo HTML autónomo: funciona con doble clic, sin instalar
nada y sin conexión a internet.

---

## 1. Los archivos

La unidad son **8 archivos** que deben vivir **todos en la misma carpeta**:

```
index.html                            ← página de inicio (el "campus")
etapa1-nocion-de-limite.html
etapa2-algebra-e-infinitesimos.html
etapa3-indeterminaciones.html
etapa4-infinitos-y-asintotas.html
etapa5-funciones-racionales.html
etapa6-continuidad.html
etapa7-cierre-integrador.html
```

> **Importante:** no cambies los nombres de los archivos. Los enlaces del campus y el
> "mapa de retorno" de la Etapa 7 apuntan a estos nombres exactos. Si renombrás uno,
> esos enlaces dejan de encontrarlo.

---

## 2. Probarlo en tu computadora (antes de publicar)

1. Poné los 8 archivos en una carpeta, por ejemplo `Unidad2-Limites`.
2. Hacé doble clic en **`index.html`**.
3. Se abre el campus en tu navegador. Desde ahí entrá a cada etapa con "Abrir etapa".

Si funciona así, va a funcionar igual publicado. (En esta prueba local sí se guarda el
progreso de los círculos; ver la sección 5.)

---

## 3. Publicar en GitHub Pages

El mismo flujo que usaste para la Unidad 1.

1. Entrá a **github.com** e iniciá sesión.
2. Creá un repositorio nuevo (botón **New**). Ponele un nombre, por ejemplo
   `LimiteYContinuidad`. Marcalo como **Public**. Confirmá con **Create repository**.
3. En la página del repo vacío, hacé clic en **uploading an existing file**
   (o **Add file → Upload files**).
4. **Arrastrá los 8 archivos** a la zona de carga (los 7 de etapas + `index.html`).
5. Abajo, escribí un mensaje (ej. "Primera versión Unidad 2") y tocá **Commit changes**.
6. Activá Pages: andá a **Settings → Pages**. En **Source** elegí **Deploy from a branch**;
   en **Branch** elegí **main** y carpeta **/ (root)**. Tocá **Save**.
7. Esperá 1–2 minutos. GitHub te muestra la URL publicada, del tipo:
   `https://iamatematica.github.io/LimiteYContinuidad/`

Como el archivo se llama `index.html`, esa URL abre **directamente el campus**.

> Para ver cambios después de re-subir un archivo, recargá con **Ctrl + Shift + R**
> (fuerza recarga y evita la versión vieja en caché).

---

## 4. Incrustar en Moodle

Igual que la Unidad 1, con un recurso de tipo **Etiqueta** (Label) o **URL**.

**Opción simple (enlace):**
- En tu curso, activá edición → **Añadir una actividad o recurso → URL**.
- Pegá la dirección del campus de GitHub Pages.
- Guardá. El alumno entra al campus y desde ahí recorre las 7 etapas.

**Opción incrustada (tarjeta de presentación):**
- Activá edición → **Añadir una actividad o recurso → Etiqueta**.
- En el editor, usá el botón **`< >`** (HTML) y pegá un bloque que enlace al campus,
  o un `<iframe>` apuntando a la URL de GitHub Pages.

> **Seguimiento de avance en serio:** si querés registrar qué alumno completó cada
> etapa (con su usuario, sincronizado), conviene cargar cada etapa como un recurso de
> Moodle y activar **finalización de actividad**. Ese seguimiento lo da Moodle, es más
> confiable que el del HTML, y no requiere tocar el código.

---

## 5. Sobre el progreso (los círculos del campus)

El campus tiene una barra de progreso con un círculo por etapa, que el alumno tilda al
terminar. Ese tilde se guarda **en el navegador del alumno** (localStorage):

- ✅ Funciona **publicado en GitHub** y **abriendo local con doble clic**.
- ⚠️ **No** se prueba dentro de la vista previa de claude.ai (ese entorno lo bloquea).
- ⚠️ Es **por dispositivo y navegador**: si el alumno entra desde otra computadora o
  desde el celular, el progreso no lo sigue (arranca de cero ahí).
- ⚠️ Si el alumno limpia el historial del navegador, se borra.

Es útil como autoevaluación informal ("¿por dónde iba?"), pero **no es un registro
confiable**. Para registro real, usá la finalización de actividad de Moodle (sección 4).

---

## 6. Navegación entre etapas

- Desde el **campus**, cada "Abrir etapa" abre la etapa en una **pestaña nueva**.
- Cada **etapa** tiene arriba a la derecha un enlace **"← Campus"** que vuelve a la
  página de inicio (útil si el alumno llegó directo desde Moodle sin pasar por el campus).
- En la **Etapa 7**, el "mapa de retorno" enlaza a las etapas que conviene repasar
  según los errores cometidos.

---

## 7. Créditos

Material didáctico interactivo basado en el apunte de cátedra (Galli, Bermejo, Baioni),
para Análisis Matemático I — Tecnicatura Superior en Informática Aplicada, INSPT–UTN.
Prof. Ariel Cardozo.

# 🥷 CSS Ninja Training - Módulo 2 Semana 2

Bienvenido al entrenamiento de HTML y CSS para el **Módulo 2 Semana 2**. Este proyecto incluye una práctica completa de estructura HTML, selectores CSS, personalización visual, modelo de caja, layout con `display` y `position`, y efectos visuales con animaciones y pseudoclases.


## ✅ Instrucciones de desarrollo

### Paso 1: Estructura básica HTML

- Crea un archivo `index.html`.
- Asegúrate de incluir las etiquetas principales (`<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`).
- Enlaza correctamente tu archivo CSS:
  ```html
  <link rel="stylesheet" href="CSS/styles.css">
  ```

---

### Paso 2: Selectores y especificidad

- Crea `styles.css` dentro de la carpeta `CSS/`.
- Usa selectores por etiqueta (`h1`, `p`), clase (`.clase`) e ID (`#id`).
- Crea conflictos de estilo y resuélvelos usando la **especificidad** de CSS.

---

### Paso 3: Personalización visual

- Aplica colores personalizados a fondo, texto, bordes y sombras:
  ```css
  background-color: #facc15;
  border: 2px solid #4f46e5;
  box-shadow: 0 4px 8px rgba(0,0,0,0.2);
  ```

---

### Paso 4: Modelo de caja

- Ajusta márgenes, padding y bordes con:
  ```css
  margin: 10px;
  padding: 20px;
  border: 5px solid var(--primary);
  ```

---

### Paso 5: Distribución con `display` y `position`

- Usa `flexbox` para organizar el layout:
  ```css
  display: flex;
  flex-direction: column;
  align-items: center;
  ```

- Aplica `position: relative | absolute | fixed` para controlar ubicaciones precisas.

---

### Paso 6: Efectos visuales y animaciones

- Utiliza transformaciones para escalar, rotar o mover elementos:
  ```css
  transform: rotate(45deg);
  transition: transform 0.5s ease-in-out;
  ```

- Agrega pseudoclases como `:hover` y pseudoelementos como `::before`.

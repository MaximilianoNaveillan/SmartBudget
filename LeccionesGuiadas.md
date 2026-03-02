# 📘 Proyecto Integrador ABP-M3

## SmartBudget -- Desarrollo de la Interfaz de Usuario Web

---

# 1️⃣ M4 AE1 👨🏽‍🏫 Clase: Del diseño a la implementación de un producto digital

## 🎯 Objetivo Pedagógico

Comprender cómo se traduce un diseño visual (Figma o mockup) en una
estructura HTML semántica funcional.

## 🧠 Paso a Paso

### Paso 1: Analizar el diseño

- Identificar Header, Hero, Secciones, Cards, Footer.
- Detectar componentes repetibles.
- Analizar jerarquía visual.

### Paso 2: Crear estructura HTML semántica

Utilizar: - `<header>` - `<nav>` - `<main>` - `<section>` -
`<article>` - `<footer>`

### Paso 3: Documentar el código

Agregar comentarios estratégicos:

```html
<!-- Componente Hero Principal -->
```

### Paso 4: Reflexión

El front-end transforma diseño en experiencia funcional, cuidando
semántica, accesibilidad y escalabilidad.

---

# 2️⃣ Del diseño a la implementación de un producto digital

## 🔎 Buenas prácticas clave

- HTML limpio y jerárquico
- Separación de responsabilidades (HTML estructura / CSS estilos)
- Componentización mental desde el inicio

---

# 3️⃣ M4 AE2 👨🏽‍🏫 Clase: Metodologías de organización y modularización de estilos

## 🎯 Objetivo

Aplicar una metodología CSS escalable.

---

# 4️⃣ Metodologías de organización y modularización de estilos

## 🧩 Paso a Paso

### Paso 1: Elegir metodología

Recomendado: **BEM**

Ejemplo:

```css
.card {
}
.card__title {
}
.card--highlight {
}
```

### Paso 2: Organizar por componentes

Crear carpetas:

    /css
      /components
      /layout
      /base

### Paso 3: Justificar elección

Explicar por qué BEM permite escalabilidad y mantenimiento.

---

# 5️⃣ M4 AE3 👨🏽‍🏫 Clase: El preprocesador SASS

## 🎯 Objetivo

Modularizar estilos usando SASS con patrón 7-1.

## 🧠 Paso a Paso

### Paso 1: Instalar SASS

    npm install -g sass

### Paso 2: Crear estructura 7-1

    /sass
      /abstracts
      /base
      /components
      /layout
      /pages
      /themes
      /vendors
      main.scss

### Paso 3: Usar variables y mixins

```scss
$primary-color: #4caf50;

@mixin flex-center {
  display: flex;
  justify-content: center;
  align-items: center;
}
```

### Paso 4: Compilar

    sass sass/main.scss css/styles.css

---

# 6️⃣ M4 AE4 👨🏽‍🏫 Clase: El modelo de cajas y el layout

## 🎯 Objetivo

Implementar layout responsivo.

## 🧠 Paso a Paso

### Paso 1: Aplicar box-sizing

```css
* {
  box-sizing: border-box;
}
```

### Paso 2: Utilizar Flexbox

```css
.container {
  display: flex;
  justify-content: space-between;
}
```

### Paso 3: Aplicar Grid si es necesario

```css
.grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
}
```

### Paso 4: Media Queries

```css
@media (max-width: 768px) {
  .container {
    flex-direction: column;
  }
}
```

---

# 7️⃣ M4 AE5 👨🏽‍🏫 Clase: Utilizando Bootstrap 4 como framework CSS

## 🎯 Objetivo

Integrar Bootstrap sin romper modularidad.

## 🧠 Paso a Paso

### Paso 1: Integrar Bootstrap 4

CDN en `<head>`.

### Paso 2: Reemplazar secciones por componentes

- Cards
- Navbar
- Modals
- Botones

### Paso 3: Usar clases utilitarias

- `mt-3`
- `text-center`
- `d-flex`
- `container`

### Paso 4: Evitar sobreescrituras innecesarias

Mantener estructura SASS modular.

---

# 8️⃣ Secuencia Pedagógica - FRONTEND

## 📚 Progresión del aprendizaje

1.  Comprensión del diseño
2.  Implementación semántica
3.  Organización CSS
4.  Modularización con SASS
5.  Layout responsivo
6.  Integración de framework
7.  Optimización y documentación

---

# ✅ Checklist Final

- HTML semántico correcto
- Metodología CSS aplicada coherentemente
- Estructura SASS 7-1 implementada
- Layout responsivo validado
- Bootstrap integrado correctamente
- Código limpio y comentado
- Documento de justificación incluido
- Proyecto listo para portafolio

---

# 🚀 Resultado Esperado

Una landing page profesional, modular, escalable y responsiva, lista
para evolucionar hacia una SPA completa.

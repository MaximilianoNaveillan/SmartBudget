# SmartBudget - Desarrollo de Interfaz de Usuario Web 📱💰

¡Bienvenido al repositorio del proyecto **SmartBudget**! Esta aplicación web ha sido desarrollada como parte de la evaluación del **Módulo #3**, enfocándose en la creación de una interfaz moderna, escalable y totalmente responsiva para la gestión de finanzas personales.

---

## 📋 Descripción del Proyecto

SmartBudget es una startup que busca democratizar el control financiero. El objetivo de este proyecto fue transformar prototipos de diseño en una **maqueta funcional (Landing Page)** utilizando las mejores prácticas de la industria en desarrollo Front-End.

### Objetivos alcanzados:

- **Semántica HTML5:** Estructura clara y accesible.
- **Arquitectura SASS:** Uso del patrón 7-1 para modularización.
- **Metodología BEM:** Nomenclatura de clases escalable y mantenible.
- **Diseño Responsivo:** Adaptabilidad total mediante Flexbox, Grid y Media Queries.
- **Bootstrap 4:** Integración de componentes dinámicos y utilitarios.

---

## 🚀 Tecnologías Utilizadas

- **HTML5** (Semántica avanzada)
- **CSS3** (Flexbox & Grid)
- **SASS** (Preprocesador)
- **Bootstrap 4** (Framework UI)
- **Metodología BEM** (Block Element Modifier)

---

## 📂 Estructura del Proyecto (Patrón 7-1)

Siguiendo las buenas prácticas de SASS, el proyecto se organiza de la siguiente manera:

```text
/
├── css/                # CSS compilado
├── scss/               # Archivos fuente de SASS
│   ├── abstracts/      # Variables, mixins y funciones
│   ├── base/           # Reset, tipografía y estilos globales
│   ├── components/     # Botones, cards, modales (BEM)
│   ├── layout/         # Header, footer, grid system
│   ├── pages/          # Estilos específicos de la landing
│   ├── vendors/        # Overrides de Bootstrap 4
│   └── main.scss       # Archivo central de importación
├── assets/             # Imágenes y recursos visuales
├── index.html          # Documento principal
└── README.md           # Documentación del proyecto
```

---

## 🛠️ Metodología y Decisiones Técnicas

### 1. Nomenclatura BEM

Se seleccionó la metodología **BEM** para el desarrollo de componentes. Esto permite que el código sea autodocumentado y evita conflictos de especificidad.

- _Ejemplo:_ `.navbar__link--active`, `.card__button`.

### 2. Layout y Responsividad

Se utilizó un enfoque **Mobile-First**:

- **Bootstrap Grid:** Para la estructura general.
- **Custom Flexbox:** Para alineaciones precisas dentro de los componentes.
- **Breakpoints SASS:** Manejados mediante mixins para mantener el código limpio.

### 3. Integración de Bootstrap 4

Se incorporó el framework para acelerar el desarrollo de elementos complejos como:

- Menús de navegación colapsables.
- Ventanas modales de interacción.
- Sistema de alertas y botones consistentes.

---

## 📈 Proceso de Desarrollo

El proyecto se dividió en 5 etapas clave:

1. **Lección 1:** Estructura semántica inicial y análisis de prototipos.
2. **Lección 2:** Implementación de la metodología BEM.
3. **Lección 3:** Configuración de SASS y arquitectura de carpetas 7-1.
4. **Lección 4:** Ajustes de Box Model y diseño responsivo.
5. **Lección 5:** Integración final de componentes y utilidades de Bootstrap 4.

---

## 📥 Instalación y Uso

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/smartbudget.git
   ```
2. Compila el archivo SASS (si tienes SASS instalado):
   ```bash
   sass scss/main.scss css/style.css --watch
   ```
3. Abre el archivo `index.html` en tu navegador.

---

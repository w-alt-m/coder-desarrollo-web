# Entrega 3

## Objetivos

- Realizar la estructura final de la web.
- Efectuar el estilo final de la web.
- Realizar una correcta implementación de SASS.
- Generar la carga en un repositorio en GitHub.

---

## Requisitos

Este trabajo cuenta con tres instancias (puedes compartir la URL de tu repositorio de GitHub con las tres):

### Estructura del HTML

- Realizar una estructura del HTML prolija, limpia y fácil de leer.
- Agregar elementos HTML según la necesidad de armar contenedores o elementos web determinados, basándose en el framework elegido y la documentación del mismo.
- Usar Bootstrap o Grids + Flexbox.
- Las estructuras se deberán maquetar a la web basándose en el framework elegido, haciendo uso de clases utilitarias para armar grillas, elementos web y estilos propios del framework, además del HTML de contenido.
- Todas las páginas deben tener el contenido estructurado y el estilo linkeado.
- Agregar las diferentes librerías de JavaScript y CSS pertinentes al framework.
- La estructura debe ser entregada en uno o varios archivos HTML según tu proyecto.

### Archivo CSS, Archivos SCSS (en GitHub)

Tu archivo SCSS debe contar con las siguientes características:

- Trasladar los estilos creados en CSS a SCSS.
- Uso correcto del nesting, extend, los mixins, las variables y los operadores de lenguaje SASS.
- Estilos avanzados: Genera una estructura de elementos dinámica aplicando transformaciones, transiciones y/o animaciones.

Los archivos deben estar en el repositorio de GitHub.

### Git y GitHub para brindar acceso al proyecto versionado

Tu repositorio debe contener:

- Archivos: Todos los archivos necesarios para visualizar correctamente la web. Utilizar .gitignore para evitar carga de carpetas como node_modules.
- Historial de versionado: Mostrar los commits usados para actualizar/versionar el código.

El acceso al repositorio de GitHub debe ser proporcionado mediante la URL pública del mismo.

---

## Responsive design y código SASS en el proyecto

---

## Recomendaciones

- Asegúrate de optimizar tu sitio web para la velocidad y la eficiencia. Utiliza técnicas como la compresión de archivos, el uso de CDN (Content Delivery Network) y la optimización de imágenes para garantizar que tu sitio web cargue rápidamente y se ejecute sin problemas.
- Cuando cargues tu sitio web en GitHub, asegúrate de seguir buenas prácticas de control de versiones. Usa ramas separadas para nuevas características o correcciones de errores, y documenta cuidadosamente los cambios que realizas.
- Asegúrate de probar tu sitio web en diferentes navegadores y dispositivos para garantizar que se vea y funcione correctamente para todos los usuarios. Emplea herramientas como BrowserStack o CrossBrowserTesting para simplificar el proceso de pruebas de compatibilidad de navegadores.
- Debes crear una arquitectura de carpetas de SCSS que respete las buenas prácticas del preprocesador.

---

## Criterios de evaluación

### Estructura final de la web (HTML) - Estilo, funcionalidad y contenido

- **Estilo:** Se observa un uso de nombres de clases correcto, sin caer en clases redundantes o irrelevantes. Linkea correctamente a el/los archivos de CSS que son generados por el SCSS.
- **Funcionalidad:** Las páginas tienen enlaces funcionales. Las imágenes están bien cargadas y resultan pertinentes. Las rutas relativas son correctas.
- **Contenido:** La información está correctamente estructurada, usando los tags correctos para cada tipo de contenido, ya sean tablas, listas, titulares, párrafos o imágenes. El contenido se distribuye de forma no monótona y tiene varios niveles de lectura. Las imágenes tienen un tamaño apropiado al que ocupan en el contenido.

### Estructura final de la web (HTML) - Prolijidad del código y tags

- **Prolijidad del código:** Presenta tabulaciones correctas y ordenadas, denotando jerarquía entre los elementos. ¿Hay consistencia entre la estructura HTML de diferentes páginas?
- **Tags:** El nesting es óptimo, usando la menor cantidad de tags posibles. Se observa un uso de tags semánticos correcto y estructuración de la página desde el HTML. El alt de las imágenes es pertinente y descriptivo.

### Estilo final de la web (CSS) - Estilo del diseño web

- **Estilo del diseño web:** Las transiciones y animaciones son apropiadas, y se usan con elementos que merecen la atención del usuario. Hay una paleta de colores con contrastes pertinentes y se respeta a lo largo de las páginas del sitio web. El texto es legible.

### Estilo final de la web (CSS y SCSS/SASS) - Código y diseño de la estructura visual

- **Código de la estructura visual o layout:** ¿Utiliza flex y grid pertinente al tipo de layout a generar? Evita forzar flex o grid para elementos que no lo necesitan y se resuelven con box-modelling.
- **Diseño de la estructura visual o layout:** ¿El diseño del layout es consistente página a página, planteando una navegación intuitiva y navegable? Los elementos de la misma jerarquía y los estilos definidos para los elementos se mantienen consistentes a lo largo de las páginas.

### Estilo final de la web (SCSS/SASS) - Utilización de frameworks

- **Utilización de frameworks:** Utiliza el framework para maquetar y no para traerse solamente componentes (carousel, menú hamb, modal, etc).

### Estilo final de la web (CSS y SCSS/SASS) - Entendimiento

- **Entendimiento del CSS:** ¿Expande sobre elementos que ya había creado con clases que los modifican? ¿Genera estilos que son fáciles de cambiar o transformar para diferentes tamaños de dispositivo?
- **Entendimiento de SCSS/SASS:** ¿Crea mixins y evita repetir código que usa a lo largo de su web? Utiliza operadores como each para armar clases de forma dinámica. Utiliza variables para no tener que repetir valores innecesarios.

### Estilo final de la web (CSS y SCSS/SASS) - Prolijidad del código y media queries

- **Media queries & Responsive:** Usa unidades relativas. El sitio web cuenta con una buena navegación en numerosos tamaños, en particular en mobile, laptop y desktop.
- **Prolijidad del código:** Usa tabulaciones y nesting bien estructurado en el SCSS. Usa & para realizar selectores óptimos con pocas repeticiones.

---

## ✅ Checklist Entrega 3 (HTML + SASS + GitHub)

## 🔹 1. Estructura del proyecto

- [x] ~~Crear la carpeta del proyecto~~
- [x] ~~Configurar la arquitectura de carpetas SCSS (`/scss`, `/scss/base`, `/scss/components`, `/scss/layout`, `/scss/utils`, `/scss/pages`)~~ _(puede requerir ajustar si no existía SCSS)_
- [x] ~~Configurar `.gitignore` (ignorar `node_modules/` y otros innecesarios)~~
- [x] Crear un archivo `main.scss` que importe los parciales

---

## 🔹 2. HTML (estructura final de la web)

- [x] ~~Crear la estructura prolija, limpia y tabulada en los archivos HTML~~
- [x] ~~Usar tags semánticos correctos: `<header>`, `<main>`, `<footer>`, `<section>`, `<article>`, `<nav>`~~
- [x] ~~Insertar contenido estructurado: títulos (`<h1>`–`<h6>`), párrafos, listas, imágenes, tablas si corresponde~~
- [x] ~~Usar atributos alt descriptivos en todas las imágenes~~
- [x] ~~Verificar rutas relativas correctas (para imágenes, CSS y JS)~~
- [x] ~~Agregar enlaces funcionales en menús y navegación~~
- [x] ~~Incluir librerías necesarias (Bootstrap **o** grid+flexbox con CSS propio)~~
- [x] ~~Aplicar clases utilitarias del framework elegido (si es Bootstrap)~~
- [x] ~~Verificar consistencia entre páginas (estructura y jerarquía similares)~~

---

## 🔹 3. CSS / SCSS

- [ ] Traducir todos los estilos CSS a **SCSS**
- [ ] Usar **variables** para colores, tipografías, tamaños
- [ ] Usar **nesting** correcto para selectores
- [ ] Usar **mixins** (ej: para media queries o botones)
- [ ] Usar **@extend** para reutilizar estilos
- [ ] Usar **operadores** de SASS (`+`, `-`, `*`, `darken()`, `lighten()`, etc.)
- [ ] Implementar **mapas o loops (@each)** si es posible (ej: clases dinámicas de color)
- [ ] Implementar **transiciones y/o animaciones** en elementos relevantes
- [ ] Verificar que se genere un único `style.css` compilado a partir del SCSS
- [ ] Linkear el CSS generado en todos los HTML

---

## 🔹 4. Responsive Design

- [ ] Usar unidades relativas (`em`, `rem`, `%`, `vh`, `vw`) en lugar de píxeles fijos donde sea pertinente
- [ ] Usar **grid y flexbox** de forma adecuada según layout
- [ ] Definir media queries SCSS con mixins (ej: breakpoints para mobile, tablet, desktop)
- [ ] Comprobar que el diseño funciona en:
  - [ ] Mobile (≤576px)
  - [ ] Tablet (~768px)
  - [ ] Laptop (~1024px)
  - [ ] Desktop (≥1440px)
- [ ] Asegurar que navegación sea intuitiva y los elementos se mantengan consistentes

---

## 🔹 5. Optimización

- [x] ~~Optimizar imágenes (tamaño apropiado, formato web)~~
- [x] ~~Comprimir archivos si es necesario~~
- [ ] (Opcional) Usar un CDN para librerías externas (ej: Bootstrap, FontAwesome)
- [x] ~~Verificar velocidad y rendimiento (ej: Lighthouse o PageSpeed)~~

---

## 🔹 6. Git & GitHub

- [x] ~~Inicializar repositorio con `git init`~~
- [x] ~~Crear commits frecuentes y descriptivos (ej: `"Estructura HTML terminada"`)~~
- [x] ~~Subir todos los archivos necesarios al repo (HTML, CSS, imágenes, JS)~~
- [x] ~~Verificar que `.gitignore` funcione correctamente~~
- [x] ~~Publicar repo en GitHub con visibilidad pública~~
- [x] ~~Comprobar que el repo tiene historial de commits mostrando versión del proyecto~~

---

## 🔹 7. Testing final

- [x] ~~Probar el sitio en Chrome, Firefox y Edge/Safari~~
- [x] ~~Probar en móvil real o emulador (herramientas dev de Chrome)~~
- [x] ~~Verificar que no haya enlaces rotos~~
- [x] ~~Revisar que todas las imágenes tengan `alt`~~
- [x] ~~Confirmar que el layout sea consistente en todas las páginas~~
- [x] ~~Revisar tabulación y orden del código antes de entregar~~

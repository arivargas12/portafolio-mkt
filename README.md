# Mi portafolio personal (Proyecto Incremental)
## Evaluación de la unidad — HTML + CSS + GitHub (100 puntos totales)

> [!NOTE]
> **Enfoque Pedagógico: Habilidad de Autoaprendizaje y Adaptación**
> En el mundo profesional del desarrollo de software y diseño, la capacidad de adaptación y el autoaprendizaje son fundamentales. A menudo te asignarán tareas o tecnologías de las que no eres especialista. Tu trabajo consistirá en investigar y encontrar la solución. Por ello, este proyecto evalúa activamente tu habilidad para utilizar de forma autónoma las guías de estudio provistas y los recursos externos para resolver tus dudas.

---

# ¿Qué vamos a construir?

Un sitio web personal de **3 páginas** con un **contenedor central** como base de diseño:
- **Inicio (`index.html`):** Tarjeta de presentación.
- **Proyectos (`proyectos.html`):** 3 proyectos destacados.
- **Contacto (`contacto.html`):** Formulario de contacto.

**Tecnologías a utilizar:**
- HTML5 (Estructura y semántica)
- CSS3 (Estilos y Responsive Design)
- AOS (Librería de animaciones)
- Git / GitHub / GitHub Pages

---

# Requisitos generales para cada entrega

Para aprobar cada fase, el sitio debe cumplir obligatoriamente con:
- Estar subido a un repositorio público en **GitHub**.
- Estar publicado y funcionando mediante **GitHub Pages**. **Importante:** Se evaluará la versión del sitio correspondiente al **último deployment (publicación)** realizado antes de la fecha y hora límite de entrega.
- Tener un **mínimo de 3 commits nuevos** por entrega (mínimo 9 en total al final). **Importante:** Se revisará el **último commit a la fecha y hora de entrega**.
- **Configurar visualización de publicaciones:** Debes activar la opción **"Deployments"** en el panel de detalles del repositorio en GitHub (sección *About* -> Haz clic en el engranaje ⚙️ -> marca la opción *Deployments* bajo *Include in the home page* -> *Save changes*). Esto es indispensable para auditar tu historial de publicaciones.
- Presentar rutas relativas y enlaces completamente funcionales.
- Mantener los archivos ordenados (directorios `/css` e `/img`).

> [!IMPORTANT]
> **Uso de Inteligencia Artificial (IA) como asistente:** Se permite usar herramientas de IA como apoyo para resolver dudas puntuales o aprender a implementar elementos específicos (por ejemplo, preguntar *"¿cómo colocar un enlace?"* y seguir las instrucciones de la IA paso a paso). **Sin embargo, no puedes pedirle a la IA que construya todo tu proyecto**. La profesora lo notará rápidamente al evaluar tu código y al pedirte explicaciones de lo que construiste.

---

# Fases del proyecto

El proyecto se desarrolla y evalúa en 3 fases incrementales. Puedes consultar el calendario completo con los plazos oficiales vigentes en la [Guía de Fechas de Entrega](documentacion/fechas_entrega.md):

| Fase | Entrega | Puntaje | Guía Detallada |
|:---|:---|:---:|:---|
| **Formativa 01** | Página de inicio (`index.html`) con tarjeta de presentación | **30 pts** | [Ver Guía Formativa 01](documentacion/guia_formativa_01.md) |
| **Formativa 02** | Navegación completa y páginas de Proyectos y Contacto | **30 pts** | [Ver Guía Formativa 02](documentacion/guia_formativa_02.md) |
| **Parcial (Final)** | Optimización semántica, Responsive Design, Efectos especiales con AOS o CSS | **40 pts** | [Ver Guía Parcial 01](documentacion/guia_parcial_01.md) |
| **Total** | | **100 pts** | |


---

# 📘 ¿Cómo documentar tu Autoaprendizaje?

Para obtener el puntaje completo en el criterio de **Autoaprendizaje y Adaptación** en tus entregas, debes demostrar cómo superaste de forma autónoma tus dudas o desafíos técnicos:

1. **Comentarios en tu código:** Escribe comentarios breves indicando qué guías o recursos te ayudaron a implementar una sección.
   * *Ejemplo HTML:* `<!-- Solucionado con la guía de HTML/CSS: Atributos obligatorios de formulario -->`
   * *Ejemplo CSS:* `/* Aplicado desde guia_diseno.md: Regla de color 60-30-10 para la jerarquía visual */`
2. **Registro de desafíos (Bitácora):** Agrega una sección llamada `## 🛠️ Desafíos y Autoaprendizaje` en tu propio repositorio (en el pie de tu index o en una bitácora) respondiendo brevemente a:
   * **El problema:** ¿Qué error tenías o qué no sabías cómo hacer?
   * **La investigación:** ¿Qué guía de estudio (`guia_diseno.md`, `guia_git.md`, `guia_html_css.md`, `guia_ia.md`), tutorial o documentación oficial consultaste?
   * **La solución:** ¿Cómo lo resolviste finalmente?

---

# Fase 1: Formativa 01 — Mi primera página (30 pts)

### ¿Qué se debe entregar?
* **Estructura HTML5:** Documento base bien organizado.
* **Tarjeta de presentación central:**
  * Foto o avatar.
  * Nombre y descripción personal/profesional.
  * Área de especialidad o intereses.
  * Mínimo 2 enlaces funcionales (ej. redes sociales).
* **CSS básico:** Diseño personalizado centrado, libre elección de colores y tipografía.

---

# Rúbrica Formativa 01 (30 pts)

| Criterio | Logro completo | Logro parcial | Logro insuficiente | Máx |
| :--- | :--- | :--- | :--- | :---: |
| **Estructura HTML** | HTML5 estructurado de forma ordenada y correcta. | Errores menores en etiquetas o anidación. | Incompleto o desorganizado. | **6** |
| **Card de presentación** | Contenedor centralizado con avatar, descripción e intereses. | Faltan campos en la tarjeta de presentación. | Tarjeta incompleta o no centrada. | **6** |
| **CSS y diseño** | CSS externo aplicando pautas de color y contraste de la `guia_diseno.md`. | Personalización limitada o sin seguir las pautas de color/contraste. | CSS ausente o mal vinculado. | **6** |
| **Git & GitHub** | Mínimo 3 commits descriptivos aplicando pautas de la `guia_git.md`. | Commits con mensajes poco claros o menos de 3. | Sin historial de avance en Git. | **4** |
| **GitHub Pages** | Publicado y accesible mediante URL funcional. | Cargado pero con errores de ruta o archivos. | No publicado o inaccesible. | **3** |
| **Autoaprendizaje** | Resuelve un desafío técnico y documenta su proceso de búsqueda y solución (en código o bitácora). | Resuelve problemas autónomamente pero no documenta el proceso. | Depende enteramente de clases; no evidencia uso de guías. | **5** |

---

# Fase 2: Formativa 02 — Mi sitio personal (30 pts)

### ¿Qué se debe entregar?
* **Navegación común:** Enlace fluido entre Inicio, Proyectos y Contacto (sin rutas rotas).
* **Página de Proyectos (`proyectos.html`):** 3 proyectos con nombre, descripción e imagen.
* **Página de Contacto (`contacto.html`):** Formulario funcional visualmente con `label`, `input`, `textarea`, botones y atributos (`required`, tipos correctos).
* **Consistencia visual:** Estilos, colores y tipografías coherentes entre las 3 páginas.

---

# Rúbrica Formativa 02 (30 pts)

| Criterio | Logro completo | Logro parcial | Logro insuficiente | Máx |
| :--- | :--- | :--- | :--- | :---: |
| **Navegación** | 3 páginas conectadas perfectamente mediante menú común. | Errores de consistencia o enlaces rotos. | Sin navegación funcional. | **4** |
| **Proyectos** | 3 proyectos estructurados con texto e imagen según guías. | Faltan elementos, descripciones o imágenes rotas. | Página ausente o muy incompleta. | **5** |
| **Contacto** | Formulario completo con atributos avanzados (`required`, tipos correctos). | Faltan campos clave, etiquetas o atributos de validación. | Formulario no estructurado. | **5** |
| **Consistencia** | Estilos, colores y tipografías coherentes en las 3 páginas. | Inconsistencias visuales marcadas entre páginas. | Diseños totalmente no relacionados. | **4** |
| **Git & GitHub** | Mínimo 3 nuevos commits descriptivos del avance. | Commits insuficientes o sin descripciones claras. | Sin commits correspondientes a esta fase. | **4** |
| **Publicación** | Todo funcional y actualizado en GitHub Pages. | Errores menores de carga en assets (imágenes, CSS). | No publicado en la web. | **3** |
| **Autoaprendizaje** | Investiga y aplica autónomamente soluciones para maquetación o validación basándose en las guías y tutoriales. | Aplica soluciones pero no documenta qué guías o recursos utilizó. | No demuestra resolución autónoma de problemas técnicos. | **5** |

---

# Fase 3: Parcial — Sitio web final (40 pts)

### ¿Qué se debe entregar?
* **HTML Semántico:** Uso de `header`, `nav`, `main`, `section`, `article`, y `footer`.
* **CSS y Responsive:** El contenedor central debe adaptarse a desktop y mobile sin scroll horizontal ni textos cortados.
* **Interactividad CSS:** Estados hover en enlaces y botones.
* **Librería AOS:** Incorporación y funcionamiento de animaciones en al menos 3 elementos.
* **Proceso y calidad:** Aplicación de mejoras según feedback anterior, imágenes con atributo `alt` y estructura de carpetas limpia.

---

# Rúbrica Parcial (40 pts)

| Criterio | Logro completo | Logro parcial | Logro insuficiente | Máx |
| :--- | :--- | :--- | :--- | :---: |
| **Estructura HTML** | HTML5 semántico (`header`, `nav`, `main`, `footer`) y bien organizado. | Errores de semántica o estructuración. | Errores semánticos graves o ausencia de etiquetas HTML5. | **6** |
| **CSS y presentación** | Diseño coherente, personalizado, pulido y limpio. | Inconsistencias visuales menores o estilos descuidados. | CSS incompleto o mal estructurado. | **4** |
| **Funcionamiento** | Enlaces funcionales, imágenes con `alt` y formulario validado. | Errores menores en rutas o carga de assets. | Errores graves de navegación o enlaces rotos. | **5** |
| **Responsive** | Se adapta a móviles y escritorios sin scroll horizontal ni textos cortados. | Problemas menores de adaptación en resoluciones específicas. | No adaptado / se rompe en vistas móviles. | **5** |
| **Librería AOS** | Integración y personalización autónoma de AOS en al menos 3 elementos. | Implementación con errores menores de sincronización o sobrecargada. | AOS no implementado o no funciona. | **4** |
| **Mejoras aplicadas** | Implementa mejoras según feedback previo y las sugerencias de las guías de estudio. | Pocas mejoras o correcciones aplicadas. | Ignora el feedback anterior y las guías. | **4** |
| **Git y proceso** | Mínimo 3 nuevos commits descriptivos (mínimo 9 en todo el proceso). | Commits escasos o mensajes genéricos. | Sin historial estructurado de avance en Git. | **3** |
| **Publicación** | Publicación final impecable en GitHub Pages. | Errores menores de carga remota de recursos. | Inaccesible en línea. | **3** |
| **Autoaprendizaje y Documentación** | Documenta formalmente en el README o bitácora cómo investigó y resolvió de forma autónoma los desafíos de diseño responsivo o librerías externas. | Documenta superficialmente sus hallazgos y fuentes. | No evidencia aprendizaje autónomo ni documenta su proceso. | **6** |

---

# Checklist antes de la entrega final

- [x] ¿El menú de navegación conecta correctamente las 3 páginas?
- [x] ¿El sitio funciona y se lee bien en celulares (sin scroll horizontal)?
- [x] ¿Se usó HTML semántico (`header`, `nav`, `main`, `section`, `article`, `footer`)?
- [x] ¿Las imágenes tienen atributo `alt` y se cargan correctamente?
- [x] ¿El formulario de contacto tiene `label` e inputs apropiados?
- [x] ¿Incorporaste animaciones AOS en al menos 3 elementos?
- [x] ¿Tienes al menos 9 commits en total (mínimo 3 nuevos por fase)?
- [x] ¿Está publicado y actualizado en GitHub Pages?
- [x] ¿Activaste la opción **"Deployments"** en la configuración de **"About"** en tu repositorio de GitHub (haciendo clic en el engranaje ⚙️) para permitir a la profesora ver tu historial de publicación?

---

## 🛠️ Desafíos y Autoaprendizaje — Parcial 01 (Bitácora de Arianna Vargas)

Como parte de esta fase final de consolidación del portafolio web personal, registré los principales desafíos técnicos que enfrenté y cómo los resolví de forma autónoma utilizando las guías de estudio del curso y documentación web:

### Desafío 1: Reestructuración con HTML5 Semántico
* **El problema:** Inicialmente, gran parte de la estructura de las páginas dependía de etiquetas genéricas `<div>`, lo que dificultaba la accesibilidad y no cumplía con los estándares modernos de la web semántica ni con los requisitos de la Parcial 01.
* **La investigación:** Consulté la `documentacion/guia_parcial_01.md` (sección 1: Maquetación Semántica) y la `guia_html_css.md` para entender el significado y correcto uso de `<header>`, `<nav>`, `<main>`, `<section>`, `<article>` y `<footer>`.
* **La solución:** 
  1. Envolví todos los menús de navegación en un `<header class="main-header">` con su respectiva etiqueta `<nav>`.
  2. Transformé cada tarjeta de proyecto en `proyectos.html` de un `div` genérico a un `<article class="project-card">`.
  3. Organicé el avatar, biografía, redes sociales y formulario dentro de etiquetas `<section>`.
  4. Diseñé e incorporé un `<footer class="site-footer">` en las 3 páginas con créditos formales de autoría.

### Desafío 2: Implementación de la librería de animaciones AOS (Animate On Scroll)
* **El problema:** Necesitaba dinamizar el portafolio incorporando animaciones al hacer scroll sin que se sintieran sobrecargadas o afectaran el rendimiento de carga.
* **La investigación:** Revisé la sección 3 de `documentacion/guia_parcial_01.md` y la documentación oficial de [AOS](https://michalsnik.github.io/aos/). Aprendí cómo enlazar la librería vía CDN sin requerir descargas pesadas en el repositorio.
* **La solución:**
  1. Añadí el archivo CSS de AOS en el `<head>` de `index.html`, `proyectos.html` y `contacto.html`.
  2. Inicialicé AOS antes de cerrar el `<body>` con `AOS.init({ duration: 800, once: true });` para una experiencia sutil y elegante.
  3. Apliqué atributos `data-aos="zoom-in"` en el avatar y formulario, `data-aos="fade-down"` en los títulos y `data-aos="fade-up"` con retardos progresivos (`data-aos-delay="100"`, `200`, `300`) en las tarjetas de proyectos para un efecto escalonado visualmente atractivo.

### Desafío 3: Adaptabilidad Responsiva y Prevención de Scroll Horizontal
* **El problema:** Al animar elementos que ingresan con AOS o al visualizar las tarjetas de proyectos en pantallas angostas de celulares, existía riesgo de desbordes o scroll horizontal.
* **La investigación:** Consulté la `guia_diseno.md` y la lista de control de responsive design en `guia_parcial_01.md`.
* **La solución:** 
  1. Añadí la regla global `html, body { overflow-x: hidden; }` en `css/style.css` para neutralizar cualquier desborde provocado por transiciones o animaciones.
  2. Verifiqué que la cuadrícula `.projects-grid` colapse a una sola columna (`grid-template-columns: 1fr;`) en móviles y que el contenedor central (`main.card`) adapte su ancho fluidamente con padding adecuado.

### Desafío 4: Microinteracciones y Estados Hover con Transiciones Suaves
* **El problema:** Lograr que los botones, enlaces e imágenes respondan de forma atractiva y natural cuando el usuario interactúa con ellos.
* **La investigación:** Pautas de color y jerarquía de `guia_diseno.md` e interactividad CSS de `guia_parcial_01.md`.
* **La solución:** Implementé un efecto iluminado en color lila con resplandor suave (`box-shadow` y borde lila resplandeciente) en las tarjetas de proyectos al hover, transformaciones suaves de elevación (`transform: translateY(-6px)`) y ligero zoom en las imágenes (`scale(1.02)`), logrando un diseño interactivo, femenino y profesional.

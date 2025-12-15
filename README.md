# 🐾 TinDog - Remastered (Bootstrap 5 Edition)

> *"A veces, para construir rascacielos complejos, hay que volver a revisar los cimientos."*

Este proyecto es un **fork personalizado y modernizado** del famoso ejercicio "TinDog" del *Complete Web Development Bootcamp* de **Angela Yu** (Udemy).

### 🧐 ¿Por qué este proyecto ahora?
Actualmente estoy inmerso en el desarrollo de una arquitectura compleja Full Stack (**LogicGames Hub**) utilizando **Java Spring Boot, Angular y PostgreSQL**. Es un desafío técnico enorme de lógica y backend.

Sin embargo, aprovechando el ritmo de diciembre, decidí tomarme un "descanso activo": volver a las bases del Frontend. El objetivo fue tomar una plantilla educativa estándar y elevarla a un nivel de producción, aplicando conceptos modernos de CSS y UI/UX que a veces pasamos por alto en el día a día del backend.

### 🐶 El "Plot Twist": Una misión real
Aunque el original es una app de citas para perros, he adaptado el contenido (protagonizado por mi propia mascota, **Puppy**) imaginando cómo sería una plataforma real para **conectar perros rescatados/callejeros con familias adoptivas**. Una interfaz limpia para una causa noble.

---

## 🎨 Mejoras Técnicas Implementadas (Vs. Original)

No es solo copiar y pegar código; he reescrito gran parte de la capa visual:

### 1. CSS Gradients & Geometría
* **Técnica**: Se renderiza un `background-size: 180%` (casi el doble de la pantalla) y se inclina a `300deg`.
* **Animación**: Mediante keyframes, desplazamos el background horizontalmente, creando un efecto de flujo constante sin impacto en el rendimiento.

### 2. Solución al "Layout Shift" (Carousel)
Un problema común en Bootstrap es que el carrusel "baila" si los textos tienen diferente longitud.

* **Fix**: Implementé una altura mínima reservada (`min-height`) y un centrado flexbox para asegurar que la estructura se mantenga sólida al pasar las diapositivas, evitando saltos visuales molestos.

### 3. Imágenes Responsivas Reales
Uso de `aspect-ratio: 3/4` y `object-fit: cover` para transformar fotos caseras en retratos profesionales que no se deforman en ningún dispositivo.

---

## 🛠 Tech Stack
* **Core**: HTML5, CSS3.
* **Framework**: Bootstrap 5.3 (Grid System, Utilities).
* **Inspiración**: Angela Yu / The App Brewery.
* **Personalización**: Mariano Monzon.

---

## 💼 ¿Buscas una Landing Page?
Este proyecto demuestra que se puede tener una web estática, rápida, responsive y elegante en tiempo récord. Si necesitas una landing page para tu negocio o emprendimiento:

**¡Contáctame!**
* **LinkedIn**: https://linkedin.com/in/marianodavidmonzon
* **Github**: https://github.com/monzonmariano
* **Email**: monzonmariano1@gmail.com   

---
*Hecho con ❤️ desde Buenos Aires/Madrid.*
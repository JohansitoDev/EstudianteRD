# EstudianteRD - Sitio Web Oficial (Landing Page)

¡Hola! Soy Johan Mancebo. Como desarrollador de software y estudiante de Ingeniería en Sistemas en la República Dominicana, diseñé y construí este sitio web como la página de presentación oficial de **EstudianteRD**, mi aplicación móvil nativa pensada para resolver el caos del cuatrimestre y ayudar a los universitarios a llevar sus materias completamente limpias.

Este repositorio contiene todo el código fuente de la *landing page*, la cual incluye un prototipo web interactivo para que los usuarios puedan experimentar las funciones clave de la app móvil directamente desde su navegador antes de instalarla.

---

## 🚀 Características del Sitio Web

La página está estructurada para guiar al usuario de forma scannable y atractiva, destacando los beneficios de la aplicación móvil:

*   **Mockups Móviles Interactivos:** Dos emuladores en pantalla que ejecutan lógica real en el frontend. Los usuarios pueden presionar la clase de *Programación React Native* para simular la entrega de tareas o usar el componente estilo Excel para añadir campos de evaluación dinámicamente.
*   **Sección de Características en Alta Fidelidad:** Bloques informativos laterales que explican detalladamente las pestañas de control, el sistema de premios cuatrimestrales (gamificación) y las ventajas de la app móvil.
*   **Carrusel de Testimonios Dinámico:** Un deslizador vertical infinito y continuo con opiniones reales de estudiantes dominicanos de diversas universidades (como la Universidad O&M y la UASD) que han probado la interfaz.
*   **Sección de Conversión (Call to Action):** Botones configurados y listos para dirigir a los usuarios a los contenedores de instalación o descarga en Android e iOS.

---

## 🛠️ Stack Tecnológico

Para lograr que la landing page sea ligera, rápida y sumamente fluida en sus animaciones, utilicé:

*   **HTML5:** Estructura semántica completamente limpia y optimizada, eliminando comentarios redundantes para asegurar un código de producción impecable.
*   **Tailwind CSS:** Framework utilitario con el que gestioné el diseño adaptivo (*mobile-first*), los efectos de desenfoque de fondo (`backdrop-blur`) y las transiciones de interacción (`active:scale-95`).
*   **Animaciones CSS a Medida:** Implementación de `@keyframes` personalizadas (`fadeInUp` y `slideInRow`) con curvas de aceleración fluidas para la entrada de elementos y nuevas filas.
*   **JavaScript (Vanilla JS):** Lógica nativa encargada de manipular los estados interactivos del prototipo móvil y coordinar el ciclo infinito de desplazamiento del carrusel de testimonios sin saltos visuales.
*   **Lucide Icons:** Iconografía vectorial moderna inyectada dinámicamente para mantener el peso de la página al mínimo.

---

## 🧑‍💻 Ejecución Local y Despliegue

Al ser una página web estática optimizada que consume los frameworks mediante CDN, su ejecución local es sumamente sencilla:

1. Clona este repositorio de la landing page:
   ```bash
   git clone [https://github.com/tu-usuario/EstudianteRD-LandingPage.git](https://github.com/JohansitoDev/EstudianteRD-LandingPage.git)

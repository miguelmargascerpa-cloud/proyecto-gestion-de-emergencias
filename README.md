# proyecto-gestion-de-emergencias
aplicacion 

# 🌲 AlertaCom - Sistema de Alerta Temprana Comunitaria

**AlertaCom** es un Prototipo Mínimo Viable (MVP) desarrollado como respuesta al **Desafío N°5: Alerta temprana y coordinación comunitaria ante incendios forestales** (Catálogo Nacional de Desafíos Tecnológicos 2026).

Este proyecto busca empoderar a las comunidades ubicadas en zonas de interfaz urbano-rural, proporcionando una herramienta rápida, resiliente y estructurada para el reporte de focos de incendio y la coordinación de evacuaciones.

## 🚀 Características del Prototipo (MVP)

Basado en el marco de trabajo Scrum y priorizando el mayor valor de negocio (salvar vidas y optimizar la respuesta), el MVP actual incluye:

   **📍 Mapa Interactivo en Tiempo Real:** Visualización de focos activos y zonas seguras de evacuación.
   **🔥 Reporte Rápido bajo Estrés:** Botón de acción flotante (FAB) rojo y de gran tamaño para enviar alertas de humo o fuego en 2 clics, compartiendo automáticamente la ubicación.
   **✅ Validación Ciudadana:** Sistema de "Confirmación" o "Falsa Alarma" liderado por los propios vecinos para evitar la saturación de los equipos de emergencia con información duplicada o falsa.
   **🏃 Protocolos de Evacuación:** Guía rápida de preparación y ubicación de la zona segura asignada más cercana.

## 🛠️ Tecnologías Utilizadas

El prototipo fue construido priorizando la simplicidad técnica y la carga rápida:

   **HTML5 & Vanilla JavaScript:** Lógica de interacción sin frameworks pesados para garantizar fluidez.
   **Tailwind CSS:** Para un diseño responsivo, moderno y adaptado a pantallas móviles.
   **Leaflet.js:** Librería open-source ligera para la renderización del mapa interactivo y los marcadores.
   **FontAwesome:** Iconografía intuitiva para facilitar la comprensión visual rápida.

## 🔄 Metodología Ágil (Scrum)

El desarrollo de este sistema siguió los principios de **Scrum**, enfocándose en la entrega temprana de valor:

1  **Product Owner (Voz de la Comunidad):** Definió que la capacidad de reportar y ver zonas seguras era más crítica que chatear entre vecinos, priorizando esto en el *Product Backlog*.
2  **Scrum Master:** Aseguró que el prototipo se mantuviera simple y no dependiera de arquitecturas complejas en la primera iteración.
3  **Equipo Scrum:** Desarrolló la solución en un *Sprint* corto, integrando diseño UI/UX y lógica de mapas.

## 💻 Cómo ejecutar el proyecto

Dado que es un prototipo *Front-end*, no requiere instalación de servidores ni bases de datos complejas.

1  Descarga el archivo `prototipo_alerta_forestal.html`.
2  Haz doble clic sobre el archivo para abrirlo en cualquier navegador web moderno (Chrome, Firefox, Safari, Edge).
3  *Recomendación:* Utiliza las herramientas de desarrollador de tu navegador (F12) y activa la **vista de dispositivo móvil** para experimentar la interfaz tal como fue diseñada.

## 🗺️ Próximas Iteraciones (Product Backlog)

Para los siguientes Sprints, se planea desarrollar:
   **Módulo Offline:** Capacidad de enviar reportes mediante redes mesh (Bluetooth/Wi-Fi Direct) cuando las antenas celulares colapsen.
   **Integración Institucional:** Dashboard especializado para Bomberos y CONAF (o el organismo de emergencias correspondiente) para visualizar el mapa de calor de las validaciones ciudadanas.
   **Cartografía de Recursos:** Visualización de grifos y piscinas disponibles para uso de bomberos.

---
*Desarrollado para la asignatura Ingeniería de Software I.*
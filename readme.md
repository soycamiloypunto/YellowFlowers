# 🌼 Yellow Flowers 🌼

Un detalle digital interactivo para regalar flores amarillas, inspirado en la cultura popular. 

🔗 **[Ver proyecto en vivo](https://soycamiloypunto.github.io/YellowFlowers/)**

---

## 🌻 ¿Qué hace este proyecto actualmente?
Es una tarjeta o experiencia web inmersiva que genera un campo de flores amarillas animadas. Cuenta con una interfaz moderna y completamente adaptada a dispositivos móviles (estilo app nativa), que incluye:

- **Ciclo de Día y Noche:** Detecta automáticamente si tu dispositivo está en modo oscuro (mostrando luna y estrellas) o modo claro (cielo azul y sol). También permite alternarlo de forma manual con un botón.
- **Reproductor de Música Integrado:** Un control interactivo para reproducir o pausar la música de fondo, diseñado especialmente para evadir las políticas que bloquean la música automática en celulares.
- **Mensaje Sorpresa:** Botón dedicado para revelar u ocultar un texto personalizado en el centro de la pantalla ("¡Aquí están tus flores amarillas!").
- **Interfaz Glassmorphism:** Menús flotantes con un efecto visual de "vidrio líquido" que difumina de forma elegante el paisaje que está por detrás.

---

## 🛠️ Detalles Técnicos
El proyecto está desarrollado completamente en lenguajes nativos (Vanilla), sin librerías externas o frameworks pesados, garantizando un rendimiento óptimo:

- **HTML5:** Estructura básica de la aplicación.
- **CSS3 Avanzado:** 
  - Dibujo de los elementos y de las flores sin imágenes (usando gradientes, pseudoelementos, sombras).
  - Animaciones de fluidez alta (`@keyframes`) para recrear el crecimiento progresivo de las hojas y la iluminación.
  - *Glassmorphism / Liquid Glass* (`backdrop-filter: blur`) aplicado a las tarjetas del menú inferior y del texto principal para su estética transparente.
  - Variables de entorno (`:root`) y media queries (`prefers-color-scheme`) para gestionar temas visuales responsivos.
- **JavaScript (ES6):**
  - Manipulación de DOM para intercambiar visualmente íconos, clases y ambientes.
  - Gestión directa de la API de HTML5 Audio para control de reproducción y pausa según la interacción humana.

---

## 🚀 Instalación y Uso Local

```bash
git clone https://github.com/soycamiloypunto/YellowFlowers.git
cd YellowFlowers
```

¡Es completamente estático! Solo abre el archivo `index.html` en cualquier navegador web moderno para que funcione inmediatamente.

---
<div align="center">
Hecho con código y cariño. 💛
</div>

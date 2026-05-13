# Generadores Studio - Documentación

Este proyecto es una suite de herramientas basadas en HTML, CSS y JavaScript diseñada para creadores de contenido. Permite generar recursos visuales (imágenes y videos) personalizados para YouTube, TikTok, Reels y Shorts de trivia de forma rápida y profesional.

## 📂 Estructura del Proyecto

Para que la navegación entre herramientas funcione correctamente, todos los archivos deben estar en la misma carpeta:

* `index.html`: El menú principal (Hub) para acceder a todas las herramientas.
* `BarraGenerador.html`: Generador de barras de carga animadas.
* `BackgroundGenerador.html`: Generador de fondos dinámicos con partículas.
* `BulletsGenerador.html`: Diseñador de cápsulas de texto para opciones y trivias.
* `CardGenerador.html`: Motor de video para cartas de personajes y trivias animadas.

---

## 🛠️ Descripción de las Herramientas

### 1. Hub Principal (`index.html`)
Es el centro de control. Presenta una interfaz moderna con tarjetas para navegar a cada generador sin necesidad de buscarlos manualmente en la carpeta.

### 2. Progress Bar Studio (`BarraGenerador.html`)
Permite crear barras de carga profesionales con alta personalización técnica.
* **Modos:** Count Up (carga) y Count Down (descarga).
* **Ajustes:** Duración exacta en segundos, ancho y grosor en píxeles, color de barra, efecto *glow* (brillo) y radio de esquinas.
* **Contador:** Muestra el tiempo restante en lugar de porcentajes.
* **Exportación:** Video `.webm` a 60 FPS con soporte para Chroma Key (fondo verde/azul).

### 3. Background Studio (`BackgroundGenerador.html`)
Generador de fondos animados basados en algoritmos matemáticos.
* **Formas:** Lluvia de partículas con formas de corazón, estrella, libro o polígonos (triángulo a hexágono).
* **Formatos:** Soporta resoluciones Horizontal (16:9) y Vertical (9:16) en calidad 720p y 1080p.
* **Personalización:** Control de densidad, velocidad de flotado, tamaño y colores.
* **Exportación:** Video fluido en alta definición.

### 4. Graphic Template Studio (`BulletsGenerador.html`)
Diseña cápsulas de texto tipo "bullet" ideales para preguntas de opción múltiple.
* **Diseño:** Estética de cápsula redondeada con badge circular de letra (a-d).
* **Colores:** Permite elegir colores individuales para cada badge.
* **Estado:** Incluye checkboxes para marcar opciones como "Correctas". Las opciones desmarcadas se vuelven automáticamente traslúcidas.
* **Exportación:** Imagen PNG transparente (alpha channel) para superponer en edición.

### 5. Card Video Studio (`CardGenerador.html`)
Una evolución avanzada para crear trivias visuales comparando personajes o jugadores.
* **Multimedia:** Permite subir imágenes locales para cada carta.
* **Lógica de Juego:** Configura cuál es la respuesta correcta.
* **Animación:** Las cartas realizan movimientos (Flotante, Pulso o Slide) durante un tiempo determinado.
* **Revelación Final:** Al terminar el tiempo, las opciones incorrectas se vuelven grises sólidas (Chroma-Safe) y la correcta resalta en verde con una paloma (✓). Mantiene el resultado visible durante 3 segundos extras para la audiencia.
* **Exportación:** Video `.webm` a 15Mbps para máxima nitidez.

---

## 🚀 Instrucciones de Uso

1.  **Ejecución:** Abre `index.html` en un navegador moderno (preferiblemente Google Chrome o Microsoft Edge).
2.  **Configuración:** Ajusta los parámetros en el panel lateral izquierdo.
3.  **Previsualización:** Usa el botón de "Previsualizar" para ver la animación antes de grabar.
4.  **Exportación:**
    * Para **Imágenes**: Haz clic en "Descargar PNG".
    * Para **Videos**: Haz clic en "Exportar Video". No cierres la pestaña hasta que la descarga se inicie automáticamente.

## 💡 Consejos para Edición (CapCut)

* **Fondo Negro:** En tu editor, usa el modo de mezcla **"Trama" (Screen)** o **"Filtrar"** para eliminar el fondo negro instantáneamente.
* **Chroma Key:** Si exportas con fondo verde o azul, usa la herramienta **"Eliminar color"** o **"Incrustación por croma"**. La versión V5 de las cartas está diseñada para ser opaca y evitar que el croma "perfore" la carta.
* **Transparencia:** Los archivos PNG generados ya vienen con el fondo eliminado. Solo arrástralos sobre tu línea de tiempo.

---
*Desarrollado para flujos de trabajo de alta calidad.*

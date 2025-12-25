# 🍎 iOS Icon Previewer

**Simulador interactivo de iconos iOS** para diseñadores y desarrolladores que permite previsualizar logotipos como iconos de aplicaciones en una pantalla de inicio simulada de iPhone.

![iOS Icon Previewer](https://img.shields.io/badge/version-1.0.0-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 📖 Descripción

iOS Icon Previewer es una herramienta web completamente funcional que simula un iPhone real con una interfaz iOS auténtica. Permite a los diseñadores subir sus logotipos y visualizar en tiempo real cómo se verían como iconos de aplicación, con controles avanzados de transformación y ajustes visuales.

Este proyecto está construido 100% con tecnologías web nativas (HTML5, CSS3 y JavaScript Vanilla ES6+), sin dependencias externas pesadas, lo que garantiza un rendimiento óptimo y una carga rápida.

## ✨ Características Principales

### 🎨 Emulador Visual Realista
- **Frame de iPhone auténtico** con proporciones reales (375x812px)
- **Dynamic Island** simulado (notch de los modelos más recientes)
- **Barra de estado funcional** con hora actualizada en tiempo real, iconos de señal, WiFi y batería
- **Grilla de apps iOS** con 12 iconos placeholder realistas
- **Dock inferior** con efecto glassmorphism (backdrop-filter blur)

### 🔧 Motor de Renderizado Avanzado
- **Máscara Squircle auténtica de iOS** usando clip-path SVG (superelipse)
- **Efecto glossy realista** con gradientes de iluminación interna
- **Sombras sutiles** para profundidad y tridimensionalidad
- **Soporte completo** para PNG, JPG y SVG

### 🎛️ Panel de Control Completo
- **Drag & Drop** para subir imágenes de forma intuitiva
- **Slider de Zoom del Teléfono** (50% - 200%) para ver el icono más de cerca
- **Transformaciones en tiempo real:**
  - Escala/Zoom del logo (0.1x - 5x)
  - Rotación (0° - 360°)
  - Posición X e Y (-50px a 50px)
- **Botón "Fit to Fill"** para ajuste automático tipo `object-fit: cover`
- **Botón Reset** para restaurar valores por defecto
- **Editor de nombre** del icono (hasta 15 caracteres)
- **6 fondos de pantalla predefinidos** estilo iOS
- **Opción de subir fondo personalizado**

### 🌙 Diseño Dark Mode
- Interfaz moderna en modo oscuro
- Colores inspirados en el sistema de diseño de Apple
- Animaciones suaves y transiciones fluidas
- Responsive design adaptado a diferentes tamaños de pantalla

## 🚀 Demo en Vivo

Abre el archivo `index.html` en tu navegador favorito. ¡Es así de simple! No requiere instalación ni configuración.

## 📸 Capturas de Pantalla

El simulador incluye:
- Vista previa del iPhone con tu logo como icono central
- Panel de control lateral con todos los ajustes
- Actualizaciones en tiempo real mientras ajustas los controles
- Vista realista del aspecto final del icono

## 🛠️ Tecnologías Utilizadas

- **HTML5** - Estructura semántica
- **CSS3** - Estilos modernos con Flexbox/Grid, animaciones y efectos visuales
- **JavaScript ES6+** - Lógica de aplicación con FileReader API, transformaciones CSS
- **FontAwesome 6.5.1** - Iconos de la interfaz (vía CDN)
- **SVG** - Clip paths para la máscara Squircle auténtica de iOS

## 📦 Instalación y Uso

### Opción 1: Clonar el repositorio

```bash
git clone https://github.com/amaliogomezlopez/IOS-LOGO-EMULATOR.git
cd IOS-LOGO-EMULATOR
```

### Opción 2: Descargar directamente

Descarga el archivo `index.html` y ábrelo en tu navegador.

### Uso

1. **Abre `index.html`** en cualquier navegador moderno (Chrome, Firefox, Safari, Edge)
2. **Ajusta el zoom del teléfono** con el primer slider si deseas ver el icono más de cerca
3. **Sube tu logo** haciendo clic en el área de subida o arrastrando el archivo
4. **Ajusta la transformación** usando los sliders:
   - Escala para hacer zoom in/out
   - Rotación para girar el logo
   - Posición X/Y para centrar perfectamente
5. **Usa "Fit to Fill"** para que el logo cubra todo el icono automáticamente
6. **Cambia el fondo** de la pantalla seleccionando uno de los 6 predefinidos o subiendo uno personalizado
7. **Edita el nombre** del icono en el campo de texto

## 🎯 Casos de Uso

- **Diseñadores de apps:** Previsualiza tu logo antes de exportar los assets finales
- **Equipos de branding:** Presenta opciones de logotipos en contexto real
- **Desarrolladores:** Verifica que tu icono se vea bien en el home screen
- **Agencias:** Muestra mockups interactivos a los clientes
- **Freelancers:** Añade valor a tus entregas con previsualizaciones profesionales

## 🧪 Características Técnicas

### Detalles de Implementación

- **Arquitectura:** Todo en un único archivo HTML para portabilidad máxima
- **Máscara Squircle:** Implementada con SVG clip-path para precisión exacta
- **Transformaciones:** CSS transforms en tiempo real sin re-renderizado
- **FileReader API:** Lectura de archivos local sin necesidad de servidor
- **Responsive:** Media queries para adaptarse a pantallas pequeñas
- **Performance:** Sin frameworks pesados, JavaScript Vanilla optimizado

### Compatibilidad

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+

## 📂 Estructura del Proyecto

```
IOS-LOGO-EMULATOR/
│
├── index.html          # Aplicación completa (HTML + CSS + JS)
└── README.md           # Este archivo
```

## 🔮 Roadmap / Futuras Mejoras

- [ ] Exportar como imagen PNG del resultado final
- [ ] Múltiples iconos de prueba en la grilla
- [ ] Más tamaños de iPhone (Mini, Pro Max)
- [ ] Modo claro/oscuro del fondo del iPhone
- [ ] Efectos de parallax en los iconos
- [ ] Presets de transformación guardados
- [ ] PWA (Progressive Web App) para uso offline

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Si tienes ideas para mejorar el simulador:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/NuevaCaracteristica`)
3. Commit tus cambios (`git commit -m 'Add: Nueva característica'`)
4. Push a la rama (`git push origin feature/NuevaCaracteristica`)
5. Abre un Pull Request

## 📝 Licencia

Este proyecto es de código abierto y está disponible bajo la licencia MIT.

## 👤 Autor

**Amalio Gómez López**

- GitHub: [@amaliogomezlopez](https://github.com/amaliogomezlopez)

## 🙏 Agradecimientos

- Inspirado en el sistema de diseño de Apple iOS
- FontAwesome por los iconos de la interfaz
- La comunidad de desarrolladores por su constante inspiración

## 📞 Contacto

Si tienes preguntas, sugerencias o quieres reportar un bug, abre un [Issue](https://github.com/amaliogomezlopez/IOS-LOGO-EMULATOR/issues) en el repositorio.

---

⭐ Si este proyecto te resultó útil, no olvides darle una estrella en GitHub!

**Hecho con ❤️ para la comunidad de diseñadores y desarrolladores**

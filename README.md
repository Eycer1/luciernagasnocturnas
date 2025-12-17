# 🌟 Luciérnagas Nocturnas - Sitio Web Oficial

![Luciérnagas Banner](./assets/logo-sin-bg.png)

## 📖 Sobre el Proyecto

**Luciérnagas Nocturnas** es una organización humanitaria dedicada a llevar esperanza, apoyo y recursos a niños en situación vulnerable en Venezuela. Este repositorio contiene el código del sitio web oficial de la organización, diseñado para informar sobre nuestras campañas y facilitar la participación de la comunidad.

### 🎯 Visión
Convertirnos en el puente indiscutible entre quienes desean ayudar y quienes necesitan ayuda, creando un ecosistema de solidaridad transparente y eficaz.

### 🚀 Misión
Ejecutar campañas de alto impacto que provean no solo bienes materiales (ropa, alimentos), sino también soporte emocional (juguetes, compañía) a niños en situación vulnerable.

---

## ✨ Características del Sitio Web

- **🎨 Diseño Moderno y Responsivo**: Interfaz elegante con TailwindCSS que se adapta a todos los dispositivos
- **⏱️ Contador en Tiempo Real**: Cuenta regresiva dinámica hasta el próximo evento
- **💳 Sistema de Donaciones**: Información clara sobre cómo apoyar con datos bancarios copiables
- **🎭 Animaciones Suaves**: Experiencia visual atractiva con AOS (Animate On Scroll)
- **📱 Optimizado para Móviles**: Menú hamburguesa y diseño mobile-first
- **♿ Accesible**: Navegación clara y estructura semántica

---

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica del sitio
- **CSS3**: Estilos personalizados y efectos visuales
- **JavaScript (Vanilla)**: Interactividad y funcionalidades dinámicas
- **[TailwindCSS](https://tailwindcss.com/)**: Framework CSS utility-first (v3.x via CDN)
- **[AOS Library](https://michalsnik.github.io/aos/)**: Animaciones al hacer scroll
- **[Font Awesome](https://fontawesome.com/)**: Iconografía (v6.4.0)
- **Google Fonts**: Tipografías Merriweather y Plus Jakarta Sans

---

## 📂 Estructura del Proyecto

```
luciernagas-web/
│
├── index.html          # Página principal
├── README.md           # Documentación del proyecto
│
└── assets/
    ├── logo-sin-bg.png # Logo de la organización
    └── favicon.ico     # Icono del sitio
```

---

## 🚀 Instalación y Uso

### Prerrequisitos

- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Conexión a internet (para cargar librerías desde CDN)

### Opción 1: Visualización Local

1. **Clona el repositorio**:
   ```bash
   git clone https://github.com/tu-usuario/luciernagas-web.git
   cd luciernagas-web
   ```

2. **Abre el archivo**:
   - Haz doble clic en `index.html`, o
   - Usa un servidor local como Live Server en VS Code

### Opción 2: Servidor Local (Recomendado)

```bash
# Con Python 3
python -m http.server 8000

# Con Node.js (usando npx)
npx http-server -p 8000

# Con PHP
php -S localhost:8000
```

Luego abre tu navegador en `http://localhost:8000`

---

## 🎨 Personalización

### Colores del Tema

El sitio utiliza una paleta de colores personalizada definida en TailwindCSS:

```javascript
colors: {
  'night': '#0F253E',        // Azul oscuro principal
  'night-light': '#1B3B5F',  // Azul oscuro secundario
  'firefly': '#FDCB58',      // Amarillo/dorado principal
  'firefly-light': '#FFE082', // Amarillo claro
}
```

### Modificar el Evento Principal

Edita las siguientes líneas en `index.html`:

```javascript
// Línea ~437: Cambiar la fecha del countdown
const countDownDate = new Date("Dec 27, 2025 10:00:00").getTime();
```

```html
<!-- Líneas ~223-230: Actualizar detalles del evento -->
<h2>Hospital Ana Francisca Pérez de León</h2>
<span>27 de Diciembre, 2025</span>
```

### Actualizar Datos Bancarios

Modifica las secciones de Pago Móvil y Transferencia en la sección `#apoyar` (líneas ~308-340).

---

## 📱 Secciones del Sitio

| Sección | ID | Descripción |
|---------|----|----- |
| **Hero** | `#inicio` | Encabezado principal con llamado a la acción |
| **Visión y Misión** | `#vision` | Información sobre los objetivos de la organización |
| **Proyecto Actual** | `#proyecto` | Detalles del próximo evento con countdown |
| **Cómo Apoyar** | `#apoyar` | Opciones de donación y voluntariado |
| **Footer** | - | Contacto y redes sociales |

---

## 🌐 Redes Sociales y Contacto

- **Instagram**: [@orgluciernagas.ve](https://www.instagram.com/orgluciernagas.ve/)
- **WhatsApp**: [+58 416-2000247](https://wa.me/584162000247)
- **Email**: luciernagasnocturnas.ve@gmail.com

---

## 🤝 Cómo Contribuir

Si deseas mejorar este sitio web, sigue estos pasos:

1. Haz un fork del repositorio
2. Crea una rama para tu feature (`git checkout -b feature/nueva-funcionalidad`)
3. Realiza tus cambios y haz commit (`git commit -m 'Añadir nueva funcionalidad'`)
4. Sube tus cambios (`git push origin feature/nueva-funcionalidad`)
5. Abre un Pull Request

### Ideas de Mejoras

- [ ] Agregar galería de fotos de eventos pasados
- [ ] Sistema de blog o noticias
- [ ] Dashboard de impacto con estadísticas
- [ ] Integración con API de pagos
- [ ] Modo oscuro/claro
- [ ] Múltiples idiomas (i18n)

---

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - consulta el archivo `LICENSE` para más detalles.

---

## 👥 Equipo

Desarrollado con ❤️ por el equipo de **Luciérnagas Nocturnas**

---

## 🙏 Agradecimientos

- A todos los voluntarios que hacen posible nuestra misión
- A las personas que confían en nuestra labor y donan
- A la comunidad open-source por las herramientas utilizadas

---

<div align="center">

### 💛 ¡Juntos iluminamos vidas! 💛

**[Ver Sitio Web](https://luciernagas.org)** • **[Reportar un Bug](https://github.com/tu-usuario/luciernagas-web/issues)** • **[Solicitar Feature](https://github.com/tu-usuario/luciernagas-web/issues)**

</div>

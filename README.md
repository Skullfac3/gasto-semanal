# gasto-semanal
# 💰 Gestor de Gastos Semanal

![Version](https://img.shields.io/badge/version-2.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

Una aplicación web moderna y elegante para gestionar tus gastos semanales de forma intuitiva. Controla tu presupuesto, registra tus gastos y mantén tus finanzas bajo control con una interfaz visualmente atractiva.

## 🌟 Demo

![Gestor de Gastos](https://via.placeholder.com/800x400/667eea/ffffff?text=Gestor+de+Gastos+Semanal)

## ✨ Características

- ✅ **Gestión de Presupuesto**: Define tu presupuesto semanal de forma sencilla
- 💸 **Registro de Gastos**: Añade gastos con descripción y cantidad
- 📊 **Visualización en Tiempo Real**: Observa tu presupuesto disponible actualizado
- 🎨 **Diseño Moderno**: Interfaz con gradientes, glassmorphism y animaciones suaves
- 🔔 **Alertas Inteligentes**: Notificaciones cuando gastas el 50%, 75% o 100% del presupuesto
- 🗑️ **Eliminación Segura**: Confirmación antes de borrar gastos
- 📱 **Responsive Design**: Perfectamente adaptado a móviles, tablets y desktop
- ⚡ **Validaciones**: Control de datos para evitar errores
- 🎯 **Límite de Gasto**: No permite gastar más del presupuesto disponible
- 🔄 **Actualización Dinámica**: El botón se habilita automáticamente al eliminar gastos
- 🎨 **Iconos Dinámicos**: Cada gasto tiene su propio icono visual
- ↑ **Botón Flotante**: Scroll suave para volver al inicio

## 🚀 Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **CSS3**: Estilos modernos con variables CSS, gradientes y animaciones
- **JavaScript (ES6+)**: Lógica de la aplicación con clases y métodos modernos
- **Bootstrap 5**: Framework CSS para responsividad
- **Font Awesome 6**: Iconos vectoriales
- **Google Fonts (Inter)**: Tipografía moderna

## 📋 Requisitos Previos

No necesitas instalar nada. Solo necesitas:
- Un navegador web moderno (Chrome, Firefox, Safari, Edge)
- Un editor de código (VS Code, Sublime Text, etc.)

## 📦 Instalación

### Opción 1: Descarga Directa

1. Descarga el repositorio como ZIP
2. Extrae los archivos
3. Abre `index.html` en tu navegador

### Opción 2: Clonar el Repositorio

```bash
# Clona este repositorio
git clone https://github.com/tu-usuario/gestor-gastos-semanal.git

# Entra al directorio
cd gestor-gastos-semanal

# Abre el archivo index.html en tu navegador
```

## 📁 Estructura del Proyecto

```
gestor-gastos-semanal/
│
├── index.html          # Página principal
├── css/
│   └── custom.css      # Estilos personalizados
├── js/
│   └── app.js          # Lógica de la aplicación
├── README.md           # Este archivo
└── LICENSE             # Licencia del proyecto
```

## 💻 Uso

1. **Establecer Presupuesto**: Al cargar la página, ingresa tu presupuesto semanal
2. **Añadir Gastos**: 
   - Escribe la descripción del gasto
   - Ingresa la cantidad
   - Haz clic en "Agregar Gasto"
3. **Visualizar Gastos**: Todos tus gastos aparecerán en el historial
4. **Eliminar Gastos**: Haz clic en el botón de eliminar (🗑️) junto a cada gasto
5. **Monitorear Presupuesto**: 
   - Verde: Más del 50% disponible
   - Amarillo: Entre 25% y 50% disponible
   - Rojo: Menos del 25% disponible

## 🎨 Características de Diseño

### Gradientes Personalizados
- **Primario**: Púrpura a violeta (#667eea → #764ba2)
- **Éxito**: Azul cyan (#4facfe → #00f2fe)
- **Advertencia**: Amarillo a naranja (#f6d365 → #fda085)
- **Peligro**: Rosa a amarillo (#fa709a → #fee140)

### Animaciones
- `fadeInDown`: Animación de entrada del título
- `fadeInUp`: Animación de entrada del contenido principal
- `slideInLeft`: Animación de entrada de gastos
- `pulse`: Animación continua del presupuesto
- `shake`: Animación de alerta

## 🔧 Personalización

### Cambiar Colores

Edita las variables CSS en `css/custom.css`:

```css
:root {
  --primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  --secondary-gradient: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
  /* Modifica según tus preferencias */
}
```

### Modificar Validaciones

Edita las funciones en `js/app.js`:

```javascript
// Cambiar porcentajes de alerta
if ((presupuesto / 4) > restante) {
    // Menos del 25%
}
```

## 🐛 Solución de Problemas

### El presupuesto no se guarda
- Este proyecto no usa localStorage. El presupuesto se reinicia al recargar la página
- Para persistencia, considera implementar localStorage o una base de datos

### Los estilos no se cargan
- Verifica que la estructura de carpetas sea correcta
- Asegúrate de que `css/custom.css` exista
- Comprueba la consola del navegador por errores

### Las animaciones no funcionan
- Verifica que estás usando un navegador moderno
- Algunos navegadores antiguos no soportan todas las propiedades CSS3

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Para contribuir:

1. Haz un Fork del proyecto
2. Crea una rama para tu feature (`git checkout -b feature/NuevaCaracteristica`)
3. Commit tus cambios (`git commit -m 'Añade nueva característica'`)
4. Push a la rama (`git push origin feature/NuevaCaracteristica`)
5. Abre un Pull Request

## 📝 Roadmap

- [ ] Implementar localStorage para persistencia de datos
- [ ] Añadir categorías de gastos
- [ ] Gráficos de gastos con Chart.js
- [ ] Exportar datos a CSV/PDF
- [ ] Modo oscuro
- [ ] Múltiples presupuestos (semanal, mensual, anual)
- [ ] PWA (Progressive Web App)
- [ ] Autenticación de usuarios


## 👨‍💻 Autor

**Erick Baltazar**
- GitHub: [@tu-usuario]((https://github.com/Skullfac3))
- LinkedIn: (https://www.linkedin.com/in/erickbguzman/)
- Email: herichc32@gmail.com

## 🙏 Agradecimientos

Juan Pablo de la torre por los cursos impartidos. 

## 📸 Capturas de Pantalla

### Vista Desktop
![Desktop View](https://via.placeholder.com/800x400/667eea/ffffff?text=Vista+Desktop)

### Vista Mobile
![Mobile View](https://via.placeholder.com/400x600/667eea/ffffff?text=Vista+Mobile)

### Alertas
![Alertas](https://via.placeholder.com/800x200/667eea/ffffff?text=Sistema+de+Alertas)

---

⭐️ Si este proyecto te ha sido útil, ¡no olvides darle una estrella!

**Hecho con ❤️ y JavaScript**

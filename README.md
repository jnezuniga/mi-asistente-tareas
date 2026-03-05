# 📝 Mi Asistente de Tareas v3.0

Aplicación web progresiva para organizar tus tareas diarias con fechas de vencimiento, categorías y prioridades.

![Versión](https://img.shields.io/badge/versión-3.0-blue)
![Estado](https://img.shields.io/badge/estado-activo-success)
![Licencia](https://img.shields.io/badge/licencia-MIT-green)

---

## 🌟 Características Principales

### ✨ Gestión de Tareas
- ✅ **Crear tareas** - Añade tareas con descripción completa
- ✏️ **Editar tareas** - Modifica cualquier aspecto de tus tareas
- ✓ **Marcar completadas** - Seguimiento de progreso visual
- 🗑️ **Eliminar tareas** - Individual o por lote (completadas)

### 📅 Sistema de Fechas
- **Fechas opcionales** - Añade fecha de vencimiento si lo necesitas
- **Indicadores visuales** - Códigos de color según urgencia
- **Notificaciones** - Alerta automática de tareas vencidas
- **Filtros de fecha** - Ver tareas vencidas o del día

### 🏷️ Organización
- **4 Categorías** - Trabajo, Personal, Urgente, Otros
- **3 Niveles de prioridad** - Alta, Media, Baja
- **Filtros inteligentes** - Por categoría o estado de fecha
- **Ordenamiento automático** - Por prioridad → fecha → creación

### 📊 Panel de Control
- **Estadísticas en tiempo real** - Total, pendientes, completadas, vencidas
- **Resaltado de urgencias** - Las tareas vencidas destacan visualmente
- **Vista personalizable** - Filtra lo que necesitas ver

### 💾 Persistencia y Rendimiento
- **Guardado automático** - localStorage del navegador
- **Sin servidor requerido** - Funciona 100% offline
- **Migración automática** - Actualiza versiones antiguas sin perder datos
- **PWA Ready** - Instala como app nativa

---

## 🚀 Comenzar

### Acceso Directo
Visita: **[Pon aquí tu URL de GitHub Pages]**

Por ejemplo: `https://tu-usuario.github.io/mi-asistente-tareas/`

### Instalación como App (PWA)

**Android:**
1. Abre la app en Chrome
2. Menú (⋮) → "Añadir a pantalla de inicio"
3. Aparecerá con el icono 📝

**iOS:**
1. Abre la app en Safari
2. Botón Compartir (□↑) → "Añadir a pantalla de inicio"
3. Confirma y listo

---

## 📖 Cómo Usar

### Crear una Tarea
1. Escribe en el campo "¿Qué necesitas hacer?"
2. Selecciona categoría (🏢 Trabajo, 👤 Personal, etc.)
3. Elige prioridad (🔴 Alta, 🟡 Media, 🟢 Baja)
4. **(Opcional)** Añade fecha de vencimiento
5. Click en "Añadir Tarea"

### Editar una Tarea
- Click en el texto de la tarea
- O click en el botón ✏️
- Modifica lo que necesites
- Guarda los cambios

### Organizar Tareas
- **Filtros rápidos**: Click en los botones de categoría
- **Ver vencidas**: Click en "🔴 Vencidas"
- **Ver de hoy**: Click en "📅 Hoy"
- Las tareas se ordenan automáticamente

---

## 🎨 Sistema de Categorías

| Categoría | Icono | Color | Uso Sugerido |
|-----------|-------|-------|--------------|
| 🏢 **Trabajo** | Morado | `#667eea` | Tareas laborales y profesionales |
| 👤 **Personal** | Rosa | `#ff6b9d` | Vida personal, hobbies, salud |
| ⚡ **Urgente** | Rojo | `#ff4757` | Requieren atención inmediata |
| 📌 **Otros** | Gris | `#95a5a6` | Todo lo demás |

---

## ⭐ Sistema de Prioridades

| Nivel | Indicador | Color | Cuándo Usar |
|-------|-----------|-------|-------------|
| 🔴 **Alta** | Barra roja | `#ff4757` | Deadlines cercanos, emergencias |
| 🟡 **Media** | Barra naranja | `#ffa502` | Importante pero planificable |
| 🟢 **Baja** | Barra verde | `#2ed573` | Puede esperar, ideas futuras |

---

## 📅 Sistema de Fechas

### Indicadores Visuales

| Estado | Badge | Significado |
|--------|-------|-------------|
| 🔴 **Vencida** | "Venció hace X días" | Pasó la fecha límite |
| ⚡ **Hoy** | "Vence hoy" | Se cumple hoy |
| ⚠️ **Mañana** | "Vence mañana" | Se cumple mañana |
| 📅 **Futura** | "En X días" | Aún falta tiempo |

### Ordenamiento Automático
Las tareas se ordenan por:
1. **Prioridad** (Alta primero)
2. **Fecha de vencimiento** (Más cercanas primero)
3. **Fecha de creación** (Más recientes primero)

*Nota: Las tareas sin fecha aparecen al final de su grupo de prioridad*

### Notificaciones
Al cargar la app, si tienes tareas vencidas verás:
```
⚠️ Tareas Vencidas
Tienes X tareas vencidas que requieren atención
```

---

## 💻 Tecnologías Utilizadas

- **HTML5** - Estructura semántica
- **CSS3** - Estilos modernos con variables CSS y animaciones
- **JavaScript (Vanilla ES6+)** - Lógica de la aplicación
- **localStorage API** - Persistencia de datos local
- **PWA** - Progressive Web App con manifest.json
- **Responsive Design** - Adaptable a todos los dispositivos

---

## 📱 Diseño Responsive

La aplicación se adapta perfectamente a:
- 📱 **Móviles** - Interfaz optimizada para touch
- 📱 **Tablets** - Layout de columnas ajustable
- 💻 **Escritorio** - Uso completo del espacio disponible

---

## 🔄 Historial de Versiones

### v3.0 (Actual - Marzo 2026)
- ✨ **Nuevo:** Sistema de fechas de vencimiento
- ✨ **Nuevo:** Notificación de tareas vencidas
- ✨ **Nuevo:** Indicadores visuales por estado de fecha
- ✨ **Nuevo:** Filtros "Vencidas" y "Hoy"
- ✨ **Nuevo:** Estadística de tareas vencidas
- 🔧 **Mejorado:** Ordenamiento inteligente (prioridad → fecha → creación)
- 🔧 **Mejorado:** Migración automática desde v2.x

### v2.0 (Febrero 2026)
- ✨ Editar tareas con modal
- ✨ Sistema de categorías (4 tipos)
- ✨ Sistema de prioridades (3 niveles)
- ✨ Filtros por categoría
- ✨ Indicadores visuales de prioridad

### v1.5 (Febrero 2026)
- Optimización para móviles
- Iconos personalizados
- Feedback táctil (vibración)
- Manifest.json para PWA

### v1.0 (Enero 2026)
- Versión inicial
- Crear, completar y eliminar tareas
- Estadísticas básicas
- localStorage

---

## 🛠️ Estructura del Proyecto

```
mi-asistente-tareas/
├── index.html          # Aplicación completa (HTML + CSS + JS inline)
├── manifest.json       # Configuración PWA
├── README.md          # Este archivo
└── GUIA_V3.md         # Guía técnica detallada (opcional)
```

---

## 📚 Conceptos de Programación

Este proyecto es ideal para aprender:

### JavaScript
- Manipulación del DOM
- Event Listeners y delegación de eventos
- localStorage API para persistencia
- Manejo de fechas con Date objects
- Algoritmos de ordenamiento personalizados
- Template literals y interpolación
- Arrow functions y métodos de array (map, filter, find, sort)
- Spread operator para inmutabilidad

### CSS
- Variables CSS (custom properties)
- Flexbox y Grid Layout
- Animaciones y transiciones
- Media queries para responsive
- Pseudo-clases y pseudo-elementos

### UX/UI
- Modales y overlays
- Notificaciones en la interfaz
- Feedback visual y táctil
- Diseño mobile-first
- Micro-interacciones

---

## 🔮 Roadmap - Próximas Funcionalidades

### Nivel 3 (En desarrollo)
- [ ] 🔍 Búsqueda por texto
- [ ] 📊 Ordenar manualmente (drag & drop)
- [ ] 📋 Sistema de subtareas

### Nivel 4 (Planificado)
- [ ] 🤖 Integración con IA (Claude API)
- [ ] 💡 Sugerencias inteligentes de organización
- [ ] 🎯 Análisis de productividad
- [ ] ✨ Generación automática de subtareas

### Futuro
- [ ] 🔔 Recordatorios con notificaciones web
- [ ] 📤 Exportar a PDF/Excel
- [ ] 🎨 Temas personalizables
- [ ] 🌙 Modo oscuro
- [ ] ☁️ Sincronización en la nube
- [ ] 👥 Colaboración en equipo

---

## 🐛 Reportar Problemas

Si encuentras algún bug, por favor incluye:
1. **Descripción** - Qué estabas haciendo
2. **Navegador y dispositivo** - Ej: Chrome en Android 12
3. **Comportamiento esperado** - Qué esperabas que pasara
4. **Comportamiento actual** - Qué pasó realmente
5. **Pasos para reproducir** - Cómo hacer que ocurra de nuevo

---

## 💡 Consejos de Uso

### Para Máxima Productividad
1. **Usa fechas estratégicamente** - No todo necesita fecha límite
2. **Prioriza sabiamente** - No todo puede ser urgente
3. **Revisa diariamente** - Check de 5 minutos cada mañana
4. **Categoriza consistentemente** - Ayuda a identificar patrones
5. **Limpia regularmente** - Borra tareas completadas cada semana

### Casos de Uso Reales
- **Estudiante**: Tareas por materia, exámenes con fecha
- **Freelancer**: Proyectos por cliente, deadlines importantes
- **Hogar**: Compras, reparaciones, citas médicas
- **Equipo**: Tareas asignadas, seguimiento de proyectos

---

## 🤝 Contribuciones

Este es un proyecto educativo de código abierto. Las sugerencias y mejoras son bienvenidas.

---

## 📄 Licencia

MIT License - Libre para uso personal y educativo.

---

## 👨‍💻 Autor

Desarrollado como proyecto de aprendizaje progresivo en desarrollo web frontend.

**Stack de aprendizaje:**
- HTML5 semántico
- CSS3 moderno
- JavaScript ES6+ (Vanilla, sin frameworks)
- APIs del navegador (localStorage, Date, etc.)
- Diseño responsive y PWA

---

## 🙏 Agradecimientos

Creado con la ayuda de **Claude** (Anthropic) como parte de un proceso de aprendizaje estructurado en desarrollo web, desde conceptos básicos hasta funcionalidades avanzadas.

### Metodología de Aprendizaje
Este proyecto siguió un enfoque incremental:
- **v1.0** - Fundamentos (CRUD básico, localStorage)
- **v2.0** - Estructuras de datos complejas (objetos, filtrado)
- **v3.0** - Algoritmos avanzados (ordenamiento, fechas)
- **v4.0** - Integración de APIs (Próximamente)

---

## 📞 Contacto

Si este proyecto te resultó útil o tienes preguntas sobre el código:
- ⭐ Dale una estrella al repositorio
- 🐛 Reporta bugs en Issues
- 💬 Comparte tus mejoras

---

## 🎯 Meta del Proyecto

Demostrar que es posible crear aplicaciones web profesionales y funcionales usando únicamente tecnologías fundamentales del navegador, sin dependencias externas ni frameworks complejos.

**Conceptos clave demostrados:**
- Separación de concerns (HTML/CSS/JS)
- Programación funcional y declarativa
- Gestión de estado local
- UX/UI moderno sin librerías
- Progressive Enhancement

---

**⭐ Si te gusta este proyecto, dale una estrella en GitHub!**

---

_Última actualización: Marzo 2026 - Versión 3.0_
_Próxima actualización: Búsqueda y subtareas (v3.1)_

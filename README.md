# MyMediControl

**MyMediControl** es una aplicación móvil para Android diseñada para ayudar a los usuarios a gestionar y hacer seguimiento de su salud personal, con un enfoque especial en el control de medicamentos y mediciones de signos vitales.

---

## 📋 Características Principales

### 🩺 Control de Medicamentos
- **Registro de dosis**: Permite a los usuarios registrar cuándo han tomado sus medicamentos.
- **Seguimiento de cumplimiento**: Clasifica las dosis como "Tomado", "Omitido" o "Saltado".
- **Historial de medicación**: Visualización de todas las dosis con fechas y estados.

### 📊 Monitoreo de Signos Vitales
- **Múltiples parámetros**: Registra mediciones de:
  - Glucosa en sangre (mg/dL)
  - Presión arterial (mmHg)
  - Peso (kg)
- **Alertas visuales** (código de colores):
  - 🟢 Verde: Valores normales
  - 🟡 Amarillo: Valores de alerta
  - 🔴 Rojo: Valores peligrosos

### 📱 Interfaz Intuitiva
- **Sistema de pestañas**: Navegación sencilla entre historiales.
- **Visualización organizada**: Historial ordenado cronológicamente con la información más reciente primero.
- **Indicadores visuales**: Iconos y códigos de color para facilitar la interpretación.

### ➕ Funcionalidades Adicionales
- **Exportación de datos**: Capacidad para exportar el historial.
- **Notas personalizadas**: Permite agregar comentarios a las mediciones.
- **Interfaz adaptable**: Muestra mensajes apropiados cuando no hay datos disponibles.

---

## 📷 Capturas de Pantalla

![Pantalla principal](assets/screenshot1.png)
![Historial de medicación](assets/screenshot2.png)

---

## ⚙️ Requisitos

- Android 5.0 (Lollipop) o superior
- Permisos de almacenamiento (para la función de exportación)

---

## 🛠️ Instalación

1. Descarga el APK desde la sección de [releases](https://github.com/tu-username/mymedicontrol/releases)
2. Habilita la instalación de aplicaciones de orígenes desconocidos en tu dispositivo.
3. Instala la aplicación.
4. ¡Comienza a gestionar tu salud!

---

## 🧪 Tecnologías Utilizadas

- Kotlin  
- SQLite  
- RecyclerView  
- CardView  
- Material Design

---

## 🧱 Estructura del Proyecto

El proyecto sigue una arquitectura simple basada en actividades y adaptadores:

- `HistoryActivity`: Muestra el historial de medicamentos y mediciones
- `HistoryAdapter`: Se encarga de la representación visual de los elementos del historial
- `HistoryItem`: Modelo de datos para los elementos del historial
- `HistoryStatus`: Enumeración para los diferentes estados posibles

---

## 🔮 Roadmap

- [ ] Añadir notificaciones para recordatorios de medicación
- [ ] Implementar gráficos para visualizar tendencias en mediciones
- [ ] Sincronización con la nube
- [ ] Versión para iOS

---

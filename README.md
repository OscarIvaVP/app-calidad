# Control Estadístico de Calidad - Aplicativo Interactivo

Aplicación web interactiva para el aprendizaje y práctica del Control Estadístico de Procesos (SPC - Statistical Process Control).

## 🚀 Acceso a la Aplicación

**Demo en vivo:** [https://oscarivavp.github.io/app-calidad/](https://oscarivavp.github.io/app-calidad/)

## 📋 Descripción

Esta es una herramienta educativa integral diseñada para estudiantes, profesionales e ingenieros que desean aprender y aplicar técnicas de Control Estadístico de Calidad. La aplicación proporciona un entorno interactivo completo con teoría, cálculos automatizados, visualizaciones gráficas y ejercicios prácticos.

## ✨ Características Principales

### 1. **Introducción al SPC**
- Conceptos fundamentales del Control Estadístico de Procesos
- Aplicaciones en la industria
- Mapa de contenidos completo
- Guía de inicio para nuevos usuarios

### 2. **Gráficos de Control**
Implementación completa de los principales gráficos de control estadístico:

#### 📊 Gráficos para Variables (Datos Continuos)
- **Gráfico X̄ - R**: Control de media y rango
- **Gráfico X̄ - S**: Control de media y desviación estándar
- **Gráfico I-MR**: Control de valores individuales y rango móvil

#### 📋 Gráficos para Atributos (Datos Discretos)
- **Gráfico p**: Proporción de defectuosos
- **Gráfico np**: Número de defectuosos
- **Gráfico c**: Número de defectos
- **Gráfico u**: Defectos por unidad

Cada gráfico incluye:
- Calculadora interactiva paso a paso
- Generación automática de gráficos con Chart.js y Plotly
- Cálculo de límites de control (UCL, CL, LCL)
- Interpretación de resultados
- Detección de patrones fuera de control

### 3. **Capacidad de Proceso**
Análisis completo de la capacidad del proceso con:

#### 📏 Índices de Capacidad Potencial
- **Cp**: Capacidad potencial del proceso
- **Cpm**: Capacidad del proceso con respecto al objetivo

#### 🎯 Índices de Capacidad Real
- **Cpk**: Capacidad real del proceso
- **Ppk**: Performance del proceso

Incluye:
- Calculadoras interactivas
- Visualización gráfica de la distribución vs especificaciones
- Tabla de referencia de interpretación de índices
- Comparación Cp vs Cpk

### 4. **Las 7 Herramientas Básicas de Calidad**
Implementación de las herramientas fundamentales del control de calidad:

- **Diagrama de Pareto**: Análisis de frecuencias y priorización
- **Diagrama de Ishikawa (Espina de Pescado)**: Análisis de causa-efecto
- **Histograma**: Distribución de frecuencias
- **Diagrama de Dispersión**: Análisis de correlación entre variables

Cada herramienta incluye:
- Interfaz interactiva para entrada de datos
- Generación automática de diagramas
- Cálculos estadísticos
- Interpretación de resultados

### 5. **Sistema de Ejercicios y Evaluación**
- **Quiz Rápido**: 10 preguntas de práctica
- **Modo Examen**: 30 preguntas con límite de tiempo
- Sistema de logros y puntuación
- Retroalimentación inmediata
- Seguimiento de progreso

### 6. **Simulador de Datos SPC**
Generador de datos para análisis:
- Creación de datos sintéticos para gráficos de control
- Diferentes tamaños de muestra configurables
- Generación automática de análisis
- Exportación de resultados

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura de la aplicación
- **CSS3**: Diseño responsivo con variables CSS y gradientes
- **JavaScript Vanilla**: Lógica de la aplicación
- **Chart.js**: Visualización de gráficos estadísticos
- **Plotly.js**: Gráficos interactivos avanzados
- **Math.js**: Cálculos matemáticos y estadísticos

## 📦 Instalación y Uso

### Uso Directo (Recomendado)
Accede directamente a la aplicación en: [https://oscarivavp.github.io/app-calidad/](https://oscarivavp.github.io/app-calidad/)

### Instalación Local

1. Clona el repositorio:
```bash
git clone https://github.com/oscarivavp/app-calidad.git
```

2. Navega al directorio:
```bash
cd app-calidad
```

3. Abre el archivo `index.html` en tu navegador web preferido:
```bash
# En Windows
start index.html

# En macOS
open index.html

# En Linux
xdg-open index.html
```

No se requiere instalación de dependencias ya que todas las librerías se cargan desde CDN.

## 🔐 Sistema de Autenticación

La aplicación incluye un sistema de autenticación básico para acceso controlado. El período de prueba es de 10 días desde el primer acceso.

## 🎨 Características de la Interfaz

- **Diseño Moderno**: Interfaz oscura (dark mode) con gradientes profesionales
- **Navegación por Pestañas**: Organización clara del contenido
- **Responsivo**: Adaptable a diferentes tamaños de pantalla
- **Animaciones Suaves**: Transiciones y efectos visuales
- **Gráficos Interactivos**: Visualizaciones dinámicas y profesionales
- **Calculadoras Paso a Paso**: Proceso de cálculo transparente

## 📊 Casos de Uso

Esta aplicación es ideal para:

- **Estudiantes**: Aprendizaje de conceptos de control estadístico de calidad
- **Ingenieros de Calidad**: Herramienta rápida para análisis de procesos
- **Profesionales**: Capacitación en técnicas SPC
- **Docentes**: Material educativo interactivo para clases
- **Empresas**: Análisis de capacidad de proceso y control de calidad

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Si deseas mejorar la aplicación:

1. Haz un fork del proyecto
2. Crea una rama para tu característica (`git checkout -b feature/nueva-caracteristica`)
3. Realiza tus cambios y haz commit (`git commit -m 'Agrega nueva característica'`)
4. Sube los cambios (`git push origin feature/nueva-caracteristica`)
5. Abre un Pull Request

## 📝 Licencia

Este proyecto es de código abierto y está disponible bajo una licencia educativa. Incluye un período de prueba de 10 días para uso completo.

## 📧 Contacto

Para soporte, sugerencias o consultas sobre licencias completas, contacta a través de los issues del repositorio.

## 🌟 Agradecimientos

Desarrollado como herramienta educativa para facilitar el aprendizaje del Control Estadístico de Calidad y mejorar la comprensión de técnicas SPC en entornos industriales y académicos.

---

**Nota**: Esta aplicación utiliza almacenamiento local del navegador para guardar el progreso y las preferencias del usuario.

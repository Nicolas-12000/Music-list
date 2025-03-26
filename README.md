# Music-list

![Demo Screenshot](https://via.placeholder.com/800x400.png?text=Papito+Music+Demo)  
*Una aplicación de música híbrida (web + escritorio) con experiencias visuales inmersivas*

## 🚀 Características Principales
- **Reproducción musical** con lista de reproducción interactiva
- **Visualizaciones 3D** usando Three.js
- **Navegación por índice** de canciones
- Interfaz moderna con:
  - Sistema de búsqueda
  - Sección de preguntas frecuentes
  - Diseño responsive
- **Modo escritorio** mediante Electron

## 🛠 Tecnologías Utilizadas
- **Frontend**:  
  ![Vue.js](https://img.shields.io/badge/Vue.js-3.2.13-4FC08D?logo=vuedotjs)  
  ![TypeScript](https://img.shields.io/badge/TypeScript-4.5.5-3178C6?logo=typescript)
- **Visualización**:  
  ![Three.js](https://img.shields.io/badge/Three.js-0.169.0-000000?logo=three.js)
- **Desktop**:  
  ![Electron](https://img.shields.io/badge/Electron-33.0.1-47848F?logo=electron)

## 📦 Instalación

```bash
# Clonar repositorio
git clone 
cd t0m4s1n-papitomusic

# Instalar dependencias
npm install

# Ejecutar en desarrollo
npm run serve

# Ejecutar versión desktop (en otra terminal)
electron .
```

## 🎨 Estructura de Proyecto

```bash
t0m4s1n-papitomusic/
├── public/            # Assets estáticos
├── src/
│   ├── assets/        # Recursos multimedia
│   ├── components/    # Componentes Vue
│   ├── router/        # Configuración de rutas
│   └── views/         # Vistas principales
└── electron/          # Configuración de Electron
```

## 🤝 Cómo Contribuir
1. Haz fork del proyecto
2. Crea tu rama (`git checkout -b feature/nueva-funcionalidad`)
3. Commit cambios (`git commit -m 'Agrega nueva funcionalidad'`)
4. Push a la rama (`git push origin feature/nueva-funcionalidad`)
5. Abre un Pull Request

## 📄 Licencia
MIT

### Nota para desarrolladores:
Requiere Node.js v16+ y npm v8+ para funcionamiento óptimo.


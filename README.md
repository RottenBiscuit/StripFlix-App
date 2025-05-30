# 🎬 AppStripFlix - Plataforma de Visualización de Series y Películas

**AppStripFlix** es una aplicación híbrida construida con Angular e Ionic, orientada a permitir a los usuarios **visualizar información sobre series y películas**. Está optimizada tanto para navegador como para dispositivos móviles mediante Capacitor, lo que permite su despliegue en Android, iOS y web.

---

## 🌟 Funcionalidad Principal

- 📄 Visualizar catálogos de series y películas
- 🧭 Navegación entre distintas pantallas mediante rutas
- 📱 Interfaz móvil intuitiva gracias a Ionic
- 🔗 Preparada para consumir datos desde un backend

> La funcionalidad está enfocada en la visualización de datos.

---

## ⚙️ Tecnologías Usadas

- **Angular**: Estructura base de la aplicación
- **Ionic Framework**: UI y componentes móviles responsivos
- **Capacitor**: Integración y empaquetado para Android/iOS
- **TypeScript**: Lógica de programación
- **SCSS/CSS**: Personalización de estilos

---

## 📁 Estructura del Proyecto

- `src/app/`: Componentes y vistas principales
- `app.component.html`: Navegación central mediante `<ion-router-outlet>`
- `capacitor.config.ts`: Configuración multiplataforma
- `angular.json`: Configuración general del proyecto
- `package.json`: Dependencias y metainformación

---

## 🚀 Instalación y Ejecución

### Requisitos

- Node.js (LTS)
- Angular CLI
- Ionic CLI:
  ```bash
  npm install -g @ionic/cli
  ```

### Pasos

1. Clona el repositorio:
   ```bash
   git clone <url-del-repo>
   cd AppStripFlix/AppStripFlix
   ```

2. Instala las dependencias:
   ```bash
   npm install
   ```

3. Inicia la app en navegador:
   ```bash
   ionic serve
   ```

---

## 📱 Ejecución en Dispositivos Móviles

1. Añadir plataforma:
   ```bash
   npx cap add android
   ```

2. Sincronizar:
   ```bash
   npx cap sync
   ```

3. Abrir en Android Studio:
   ```bash
   npx cap open android
   ```

---

## 🔍 Navegación

El componente principal usa:

```html
<ion-router-outlet></ion-router-outlet>
```

Esto permite una navegación fluida entre páginas, controlada mediante el sistema de rutas de Angular + Ionic.

---

## 👩‍💻 Autora

**Sofía Millán**

Proyecto desarrollado con fines educativos y de aprendizaje en frameworks híbridos modernos.

---

## 📄 Licencia

Uso libre para proyectos personales o educativos. Para otros usos, contactar con la autora.


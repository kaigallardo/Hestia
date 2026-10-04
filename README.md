# Hestia 🏠

**Hestia** es una aplicación móvil nativa para Android desarrollada con React Native y Expo, creada para resolver el caos de la organización en hogares compartidos. Centraliza el inventario, la lista de la compra, las recetas y las tareas en una sola plataforma con sincronización en tiempo real.

## 🚀 Características Principales

Hestia ofrece un ecosistema completo para la convivencia, con funciones diseñadas para automatizar y simplificar las tareas del hogar:

- 🏘️ **Gestión Multi-Casa:** Un usuario puede pertenecer a varias casas. Cada hogar tiene su propio espacio aislado con miembros, inventario y listas independientes.
- 📦 **Inventario en Tiempo Real:** Añade productos con ubicación (Nevera, Despensa) y umbral de aviso. Alertas visuales automáticas cuando el stock es bajo.
- 🛒 **Lista de la Compra Inteligente:** Se genera automáticamente con productos bajo el umbral. Permite añadir ítems manuales y actualiza el inventario al confirmar la compra.
- 🍳 **Cocinado con Descuento:** Al cocinar una receta, verifica los ingredientes y los descuenta automáticamente. Incluye "Modo Externo" para no alterar tu inventario.
- 👤 **Perfil y Ajustes:** Edición de nombre de usuario en tiempo real y preferencias de ubicación por defecto para una experiencia personalizada.

## 🛠️ Stack Tecnológico

- **Framework:** React Native · Expo SDK
- **Navegación:** Expo Router (File-based routing)
- **Estado Global:** React Context API · Async Storage
- **Backend y Base de Datos:** Firebase Auth · Cloud Firestore
- **Lenguaje:** JavaScript (ES6+)

## 🚀 Cómo empezar (Desarrollo local)

Sigue estos pasos para levantar el entorno de desarrollo de Hestia en tu máquina:

1. **Clona el repositorio e instala las dependencias:**
   ```bash
   git clone https://github.com/kaigallardo/Hestia.git
   cd Hestia
   npm install
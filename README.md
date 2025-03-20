# 🚀 Proyecto Básico con Node.js y TypeScript

Este es un proyecto básico con **Node.js** y **TypeScript** que usa `ts-node-dev` para recargar automáticamente los cambios.

## 📌 Requisitos

Antes de comenzar, asegúrate de tener instalado:

- [Node.js](https://nodejs.org/) (versión 16 o superior)
- npm (viene con Node.js)

## 📥 Instalación

1. Clona este repositorio:

   ```sh
   git clone https://github.com/yaelmo21/basic-ts-proyect.git
   cd basic-ts-proyect
   ```

2. Instala las dependencias:
   ```sh
   npm install
   ```

## 🚀 Scripts disponibles

### 🔹 Modo Desarrollo (Recarga automática)

```sh
npm run dev
```

Este comando inicia el servidor con `ts-node-dev`, que recarga los cambios automáticamente.

### 🔹 Compilar TypeScript

```sh
npm run build
```

Compila el código TypeScript en JavaScript y lo coloca en la carpeta `dist/`.

### 🔹 Ejecutar la versión compilada

```sh
npm start
```

Este comando ejecuta el archivo index.ts desde la carpeta `dist/` con Node.js.

## 📂 Estructura del Proyecto

```
basic-ts-proyect/
│── src/
│   ├── index.ts       # Código principal
│── dist/              # Código compilado (generado tras `npm run build`)
│── package.json
│── tsconfig.json      # Configuración de TypeScript
│── README.md
```

## 🛠 Tecnologías utilizadas

- **Node.js** - Entorno de ejecución de JavaScript
- **TypeScript** - Tipado estático para JavaScript
- **ts-node-dev** - Recarga automática de TypeScript

## 📌 Notas

Si ves errores relacionados con permisos al ejecutar scripts en Mac/Linux, prueba:

```sh
chmod +x node_modules/.bin/ts-node-dev
```

¡Listo! Ahora puedes empezar a desarrollar con TypeScript y recarga automática. 🚀🔥

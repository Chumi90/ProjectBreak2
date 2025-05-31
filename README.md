#TIENDA DE ROPA#
## Introducción
El proyecto contará con 

## Descripción de la extructura de carpetas (arbol de trabajo)
├── config
│   ├── db.js
├── controllers
│   ├── productController.js
│   └── authController.js (BONUS)
├── models
│   └── Product.js
├── routes
│   └── productRoutes.js
│   └── authRoutes.js (BONUS)
├── middlewares (BONUS)
│   └── authMiddleware.js
├── helpers
│   └── template.js
│   └── getNavBar.js
│   └── baseHtml.js
└── index.js
|
├── test (BONUS)
│   └── productController.test.js
├── .env
└── package.json

## Implementación de tecnologías a utilizar
En este proyecto se utilizarán las siguientes tecnologías:
- Para el Backend:
    - Node.js
    - Express
    - Mogoose
    - dotenv

- Para el Frontend:
    - HMTL
    - CSS

- Base de datos
    - Mongo bd Atlass
    - Cloudinary, para almacenamiento de imágenes

# Configuración del servicio
Para poder comenzar con el proyecto sedeberán instalar las siguientes dependencias:
- npm i express mongoose dotenv -E

# Ignorar archivos de carga
Crear un archivo .env para ignorar los siguientes archivos:
- node_modules
- .env
- package-lock.json
- package.json
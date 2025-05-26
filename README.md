# 🧱 Estructura Profesional Moderna (Express + MVC + Clean Architecture)

Proyecto con Express.js, organizado siguiendo el patrón **MVC** + separaciones de lógica por responsabilidad. Está pensada para **escalar**, **testear**, y **mantener** fácilmente.

```
📁 myapp/
├── 📁 src/
│   ├── 📁 config/              ← Configuraciones generales (DB, variables, etc.)
│   │   └── 📄 index.js
│   ├── 📁 controllers/         ← Controladores: lógica de control de rutas
│   │   └── 📄 user.controller.js
│   ├── 📁 models/              ← Modelos (ej. con Mongoose, Sequelize o clases simples)
│   │   └── 📄 user.model.js
│   ├── 📁 routes/              ← Definición de rutas y vinculación con controladores
│   │   └── 📄 user.routes.js
│   ├── 📁 services/            ← Lógica de negocio: validaciones, reglas, etc.
│   │   └── 📄 user.service.js
│   ├── 📁 middlewares/         ← Middlewares personalizados (auth, logger, etc.)
│   │   └── 📄 auth.middleware.js
│   ├── 📁 utils/               ← Funciones auxiliares (helpers, logger, etc.)
│   │   └── 📄 logger.js
│   ├── 📁 views/               ← Vistas EJS, Pug, Handlebars, etc.
│   │   ├── 📄 index.ejs
│   │   └── 📄 layout.ejs
│   └── 📄 app.js               ← Configura Express, middlewares y rutas
├── 📁 public/                  ← Archivos estáticos (CSS, JS del cliente, imgs)
│   ├── 📁 assets/    
│   ├── 📁 images/
│   ├── 📁 javascripts/      
│   └── 📁 stylesheets/
│       └── 📄 style.css
├── 📄 server.js                ← Punto de entrada principal del servidor
├── 📄 .env                     ← Variables de entorno
├── 📄 .gitignore
├── 📄 package.json
└── 📄 README.md
```
---

### 🎯 Ventajas de esta estructura

✅ Escalable: podés agregar fácilmente nuevas funcionalidades.

✅ Separación de responsabilidades: cada capa tiene su función.

✅ Legible y mantenible.

✅ Ideal para testing automatizado.

✅ Facilita la integración de bases de datos, autenticación, logging, etc.

---

Levantar servidor con comando en consola : >_ 
```  npm run dev ``` 
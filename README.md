.env.example:
PORT=4000
MONGO_URI==mongodb+srv://jcamacho27_db_user:papiro@cluster0.7jje6ty.mongodb.net/harmoniq_db?retryWrites=true&w=majority


# 🎵 HarmoniQ  

Proyecto Universitario - Aplicación musical  

HarmoniQ es una aplicación que busca conectar a artistas, productores y amantes de la música en un mismo ecosistema digital. Su objetivo es facilitar la creación colaborativa de música, el descubrimiento de nuevos talentos y la gestión de proyectos musicales desde una misma plataforma.  

---

## 🚀 Descripción General  

HarmoniQ combina herramientas sociales con funcionalidades de colaboración musical. A través de esta aplicación, los usuarios pueden:  

- Crear y gestionar proyectos musicales.  
- Subir y compartir pistas de audio.  
- Conectarse con otros artistas, bandas o productores.  
- Comentar, reaccionar y colaborar en tiempo real.  
- Organizar sus ideas musicales de forma eficiente.  

---

## 🧩 Tecnologías Utilizadas  

- **Node.js** – Entorno de ejecución para el backend.  
- **Express.js** – Framework minimalista para crear la API REST.  
- **TypeScript** – Lenguaje tipado que mejora la calidad y mantenibilidad del código.  
- **Postman** – Herramienta para pruebas de endpoints y documentación de la API.  
- **Git & GitHub** – Control de versiones y repositorio del proyecto.  

---

## 📂 Estructura del Proyecto  

harmoniq-api/
│
├── src/
│ ├── config/ # Configuración general (Firebase, entorno, etc.)
│ ├── controllers/ # Controladores que manejan la lógica de negocio
│ ├── models/ # Modelos y tipos de datos
│ ├── routes/ # Definición de rutas de la API
│ ├── middlewares/ # Middlewares de validación y seguridad
│ └── server.ts # Punto de entrada principal del servidor
│
├── .gitignore
├── package.json
├── tsconfig.json
└── README.md


---

## 🧠 Funcionalidades Principales (Endpoints)  

| Método | Endpoint | Descripción |
|--------|-----------|-------------|
| **POST** | `/projects` | Crear un nuevo proyecto musical |
| **GET** | `/projects` | Listar todos los proyectos |
| **GET** | `/projects/:id` | Obtener un proyecto por ID |
| **PUT** | `/projects/:id` | Actualizar un proyecto |
| **DELETE** | `/projects/:id` | Eliminar un proyecto |
| **POST** | `/users` | Crear un nuevo usuario |
| **GET** | `/users` | Listar todos los usuarios |
| **POST** | `/auth/login` | Iniciar sesión |
| **POST** | `/auth/register` | Registrar usuario |

*(Consulta el documento de Inventario de Endpoints para la lista completa y ejemplos detallados.)*

---

## ⚙️ Instalación y Ejecución  

### 1️⃣ Clonar el repositorio  
```bash
git clone https://github.com/tuusuario/harmoniq-api.git  
cd harmoniq-api


## 📦 Instalación
```bash
npm install
npm run dev


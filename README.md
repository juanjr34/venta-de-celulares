# 📱 Proyecto: Plataforma de Venta de Celulares

## 🧾 Descripción
Este proyecto consiste en el desarrollo de una plataforma web para la venta de celulares, realizado por **Hugo Sánchez** y **Juan José** como parte del segundo parcial de la materia Desarrollo Web Integral.

---

## 📅 Planeación de Actividades

| Semana | Actividad                          | Descripción                                                |
|--------|------------------------------------|------------------------------------------------------------|
| 1      | Planeación y elección de tecnologías | Definición de tareas y stack tecnológico                   |
| 2      | Crear repositorio y estructura base | Inicializar repositorio y carpetas                         |
| 2      | Diseño de base de datos             | Modelado de colecciones MongoDB                            |
| 3      | Desarrollo del frontend             | Maquetación de la interfaz                                 |
| 3      | Backend con API REST                | Programación de rutas y lógica del servidor                |
| 4      | Conexión BD + Pruebas               | Integración de MongoDB y pruebas de endpoints              |
| 5      | Integración Front + Back            | Comunicación Front-Back vía fetch o axios                  |
| 6      | Despliegue                          | Vercel (frontend) y Render (backend)                       |
| 7      | Documentación y presentación final  | Elaboración del README, demo y presentación del proyecto   |

---

## ⚙️ Tecnologías Utilizadas

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js + Express.js
- **Base de Datos:** MongoDB (NoSQL)
- **Repositorio:** GitHub
- **Despliegue:** Vercel (Front) / Render (Back)

---

## 🧩 Estructura del Proyecto

```
/frontend
    index.html
    style.css
    script.js

/backend
    server.js
    routes/
    controllers/
    models/

README.md
```

---

## 📦 Estructura de Base de Datos

**Colección: usuarios**
```json
{
  "nombre": "Hugo Sánchez",
  "rol": "Admin",
  "email": "hugo@celulares.com"
}
{
  "nombre": "Juan José",
  "rol": "Vendedor",
  "email": "juan@celulares.com"
}
```

**Colección: productos**
```json
{
  "nombre": "Samsung Galaxy A54",
  "descripcion": "128GB, 5G",
  "precio": 6200,
  "stock": 10
}
```

**Colección: ventas**
```json
{
  "productoId": "ObjectId",
  "usuarioId": "ObjectId",
  "fecha": "2025-07-09",
  "cantidad": 1,
  "total": 6200
}
```

---

## ✅ Lista de Actividades Priorizadas

| Tarea                                | Prioridad | Responsable    | Estado     |
|-------------------------------------|-----------|----------------|------------|
| Crear repositorio y carpetas        | Alta      | Hugo Sánchez   | Completado |
| Diseñar la base de datos            | Alta      | Juan José      | En proceso |
| Maquetar interfaz (HTML/CSS)        | Alta      | Hugo Sánchez   | Pendiente  |
| Programar API con Node/Express      | Alta      | Juan José      | Pendiente  |
| Implementar operaciones CRUD        | Media     | Juan José      | Pendiente  |
| Conectar Frontend y Backend         | Media     | Ambos          | Pendiente  |
| Crear página de ventas              | Media     | Hugo Sánchez   | Pendiente  |
| Pruebas generales                   | Media     | Ambos          | Pendiente  |
| Despliegue final (Render/Vercel)    | Baja      | Ambos          | Pendiente  |
| Documentación y README              | Baja      | Hugo Sánchez   | Pendiente  |

---

## 📌 Créditos
**Desarrollado por:**  
- Hugo Sánchez  
- Juan José  

Materia: Desarrollo Web Integral – Segundo Parcial  
Docente: [Nombre del profesor/a]
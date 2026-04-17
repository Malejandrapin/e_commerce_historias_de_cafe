# ☕ Historias de Café

Plataforma de e-commerce que conecta directamente a familias caficultoras colombianas con consumidores finales, eliminando intermediarios y visibilizando la historia detrás de cada taza.

## 👥 Equipo de desarrollo

| Nombre |
|--------|
| Andrés Oswaldo Díaz Figueroa |
| Marcia Baquero Ruiz |
| Didier Alexis Cuan Najas |
| Maira Alejandra Pinilla Pinilla |
| Zully Tamayo Martínez |

---

## 📌 Descripción del proyecto

El proyecto surge de una realidad observada en Filandia, Quindío, donde una familia caficultora produce café de alta calidad pero depende de intermediarios para su comercialización, lo que limita sus ingresos y el reconocimiento de su trabajo.

**Historias de Café** busca resolver esta desconexión entre productores y consumidores mediante una plataforma digital con trazabilidad completa, contenido audiovisual tipo storytelling y comercio justo.

## 💼 Modelo de negocio

La plataforma actúa como intermediario digital que facilita la exhibición, promoción y venta de café de origen, incorporando contenido audiovisual (fotos y videos cortos) que comunican la historia del productor.

## 🛠️ Tecnologías utilizadas

| Frontend | Backend | Base de datos | Control de versiones |
|----------|---------|---------------|----------------------|
| HTML5 | Java | MySQL | Git |
| CSS3 | Spring Boot | | GitHub |
| Bootstrap 4 | Postman | | |
| JavaScript (ES6) | | | |

---

## 🗂️ Estructura del proyecto (Mapa de navegación)

### Usuario comprador
- **Inicio** — Carrusel de fincas, productos destacados, historias de caficultores, testimonios.
- **Catálogo de productos** — Cards con imagen, nombre, origen y precio. Filtros por región, tipo, precio. Al hacer clic en la imagen se reproduce un video storytelling del caficultor.
- **Detalle del producto** — Imágenes, video, descripción, origen, trazabilidad (QR), reseñas y botón "Agregar al carrito".
- **Carrito de compras** — Lista editable, resumen de precios, persistencia en `localStorage`.
- **Checkout y pago** — Formulario de compra, métodos de pago (PSE, Nequi, tarjetas).
- **Autenticación** — Login / Registro, OAuth (Google, Facebook), recuperación de contraseña.
- **Perfil de usuario** — Historial de pedidos, datos personales, direcciones y métodos de pago.
- **Secciones informativas** — Acerca de nosotros, Nuestra historia, Blog, Contacto.

### Administrador
- **Dashboard** — CRUD de productos, usuarios y órdenes. Configuración de productos destacados.
- **Seguridad** — Spring Security con roles `ADMIN` y `USUARIO`, protección de endpoints, autenticación JWT.

---

## 🧪 Plan de pruebas

| Fase | Tipo de prueba | Descripción |
|------|---------------|-------------|
| Frontend | Responsive Design | Verificación de adaptación a distintas resoluciones |
| Frontend | Botones funcionales | Los botones ejecutan correctamente su acción |
| Frontend | Enlaces válidos | Todos los enlaces apuntan a destinos correctos |
| Frontend | Datos válidos | Validación sintáctica y semántica de entradas del usuario |
| Frontend | Compatibilidad con navegadores | Comportamiento consistente en distintos navegadores |
| Base de datos | Operaciones CRUD | Inserción, edición, búsqueda y borrado de datos |
| Base de datos | Procedimientos / Triggers | Verificación de funciones almacenadas |
| Base de datos | Dependencias entre tablas | Normalización y respeto de reglas de negocio |
| Backend | Funciones y métodos | Parámetros de entrada/salida y lógica de cada función |
| Backend | Manejo de excepciones | Comportamiento ante valores inesperados del usuario |
| Conexiones | Frontend – Backend | Acceso correcto a endpoints y renderizado de datos |
| Conexiones | Backend – Base de datos | Comunicación correcta respetando el flujo de datos |
| Conexiones | Deploy | Funcionamiento en hosting y distintos navegadores |

## 🚀 Lanzamiento

> **Fecha de despliegue:** 02 de junio de 2026


## 📁 Herramientas del proyecto

| Propósito | Herramienta |
|-----------|-------------|
| Control de versiones | GitHub |
| Gestión de tareas | Trello |
| Diseño de interfaces | Figma |
| Comunicación | Microsoft Teams |
| Prueba de APIs | Postman |


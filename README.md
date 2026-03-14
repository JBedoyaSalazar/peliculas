# 🎬 Movie Explorer

![React](https://img.shields.io/badge/React-19-61DAFB?logo=react\&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-Build%20Tool-646CFF?logo=vite\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript\&logoColor=black)
![TMDB API](https://img.shields.io/badge/API-TMDB-01B4E4)
![Frontend](https://img.shields.io/badge/Type-Frontend-green)
![License](https://img.shields.io/badge/License-MIT-blue)

Aplicación web desarrollada con **React** que consume la **API de The Movie Database (TMDB)** para mostrar información de películas recientes.
La aplicación permite explorar lanzamientos recientes, visualizar detalles de cada película y navegar entre ellas mediante una interfaz dinámica.

Este proyecto corresponde únicamente al **frontend** y se conecta directamente con la API pública de TMDB.

---

# 🚀 Características

* Consulta de **películas recientes**
* Visualización de:

  * Poster de la película
  * Título
  * Género
  * Descripción
* Navegación a **vista de detalles**
* Interfaz construida con **componentes reutilizables**
* Consumo de API usando **Fetch**
* Routing dinámico con **React Router**

---

# 🛠️ Tecnologías utilizadas

* **React**
* **Vite**
* **React Router DOM**
* **JavaScript (ES6+)**
* **CSS**
* **Fetch API**
* **TMDB API**

---

# 📂 Estructura del proyecto

```
src
│
├── components
│   ├── MovieCard.jsx
│   ├── MovieCard.css
│
├── pages
│   ├── MovieDetails.jsx
│
├── utils
│   ├── getMovieImg.js
│
├── data
│   ├── httpClient.js
│
├── App.jsx
└── main.jsx
```

---

# ⚙️ Instalación y ejecución

### 1️⃣ Clonar el repositorio

```
git clone https://github.com/tu-usuario/tu-repositorio.git
```

### 2️⃣ Entrar al proyecto

```
cd tu-repositorio
```

### 3️⃣ Instalar dependencias

```
npm install
```

### 4️⃣ Ejecutar el servidor de desarrollo

```
npm run dev
```

La aplicación se ejecutará normalmente en:

```
http://localhost:5173
```

---

# 🔑 Configuración de la API

Este proyecto utiliza **The Movie Database API (TMDB)**.

Para utilizar la API necesitas generar una API Key:

1. Crear una cuenta en
   https://www.themoviedb.org

2. Generar una API Key en
   https://www.themoviedb.org/settings/api

3. Configurar la clave dentro del archivo:

```
src/data/httpClient.js
```

Ejemplo:

```javascript
const API = "https://api.themoviedb.org/3"
const API_KEY = "TU_API_KEY"
```

---

# 📸 Funcionalidades principales

### Listado de películas

La aplicación obtiene las películas recientes desde la API y las muestra en una galería.

### Vista de detalles

Al seleccionar una película se accede a una página donde se muestran:

* Poster
* Título
* Descripción
* Información general

---

# ⚠️ Limitaciones actuales

Este proyecto actualmente:

* Solo incluye **frontend**
* Consume la API directamente desde el cliente
* No posee sistema de **cache**
* No incluye **backend proxy**

---

# 🔮 Mejoras futuras

Posibles mejoras para el proyecto:

* Implementar **backend con Node.js o Express**
* Agregar **búsqueda de películas**
* Filtros por **género**
* Paginación de resultados
* Sistema de **favoritos**
* Lazy loading de imágenes
* Skeleton loading para mejorar UX

---

# 📄 Licencia

Este proyecto se distribuye bajo licencia **MIT**.

# Link

[https://app.netlify.com/projects/moviespeliculas/overview](https://moviespeliculas.netlify.app/)

---

# 👨‍💻 Autor

Proyecto desarrollado como práctica de **React y consumo de APIs REST**.

# 🎣 Pesca Salada y Más

¡Bienvenido a **Pesca Salada y Más**, la bitácora digital definitiva dedicada a la pasión de la pesca en la isla de **La Palma (Canarias) 🌋**. 

Este proyecto ha evolucionado de una web estática a una **aplicación web dinámica y moderna**, permitiendo gestionar en tiempo real un arsenal de pesca y un registro geolocalizado de capturas con imágenes reales directamente desde el pesquero.

---

## 🌐 Características Principales

* **🎒 El Arsenal:** Catálogo inteligente en la página principal (`index.html`) que muestra cañas, carretes y aparejos organizados por pestañas, utilizando un sistema de "semáforo" para indicar si el equipo está listo, en mantenimiento o en boxes.
* **🏆 El Pescómetro:** Galería automatizada en `capturas.html` que ordena cronológicamente las jornadas de pesca y calcula de forma matemática el podio con los mayores récords de peso históricos.
* **🗺️ Mapa Interactivo de La Palma:** Un mapa visual personalizado sobre la geografía real de la Isla Bonita. Al tocar los pines interactivos, la web filtra las capturas de la zona y ofrece un enlace directo a **Google Maps** para llegar al spot.
* **🔐 Panel de Administración Privado (`admin.html`):** Formulario optimizado para móviles que permite registrar material o subir fotos de peces directamente desde el muelle, automatizando todo el proceso de actualización.

---

## 🛠️ Arquitectura Tecnológica

A diferencia de las webs tradicionales pesadas, este sitio utiliza una infraestructura ligera de última generación:

* **Frontend:** HTML5, CSS3 (con diseño personalizado en *Modo Oscuro Marino*) y JavaScript puro (Vanilla JS).
* **Hosting:** Servidor estático gratuito mediante **GitHub Pages**.
* **Base de Datos (BaaS):** Conexión en tiempo real con **Supabase** (PostgreSQL) para la gestión de datos.
* **Almacenamiento de Medios:** **Supabase Storage** público para el alojamiento e indexación de las fotos de las capturas.

---

## 📍 Pesqueros Registrados

Actualmente la aplicación monitoriza e indexa capturas en cinco puntos estratégicos de la costa palmera:
1.  🌋 Muelle de Tazacorte
2.  🧂 Las Salinas (Fuencaliente)
3.  🏢 Los Prismas (Frente al Cabildo de SC)
4.  ⚓ Puerto de Santa Cruz de La Palma
5.  🌊 Puerto Paja (Puntallana)

---

## 👤 Autor

Desarrollado con pasión por **ElDragonLoco**. 
*¡Por un mar canario limpio y una pesca responsable!* 🌊

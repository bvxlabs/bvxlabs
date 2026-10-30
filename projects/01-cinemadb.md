# CinemaDB (CineMás TV) - Ecosistema de Streaming Multiplataforma

<div align="center">

<img src="../assets/bvx_lab_banner.png" alt="BVX LAB Official Banner" width="100%" />

<br/><br/>

<img src="../assets/projects/01-CinemaDB-Ecosistema-Completo/film-icon.png" alt="CinemaDB Film Icon" width="120" />

# CinemaDB (CineMás TV)
### Plataforma de Streaming 4K Multiplataforma sin Costo
**🌐 [cinemadb.club](https://cinemadb.club)**

[![Sitio Oficial](https://img.shields.io/badge/Web_Oficial-cinemadb.club-06B6D4?style=for-the-badge&logo=google-chrome&logoColor=white)](https://cinemadb.club)
[![Facebook](https://img.shields.io/badge/Facebook-Bvxlab-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://www.facebook.com/people/Bvxlab/61595392246829/) [![Instagram](https://img.shields.io/badge/Instagram-@bvxlaps-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/bvxlaps/)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-+1_(829)_654--8277-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/18296548277)

<br/><br/>

![CinemaDB Nueva Versión Hero](../assets/projects/01-CinemaDB-Ecosistema-Completo/cinemadb_hero_latest.jpeg)

</div>

---

## 📌 Ficha Técnica del Proyecto

| Parámetro | Detalle Oficial |
| :--- | :--- |
| **Proyecto** | **CinemaDB / CineMás TV** |
| **Categoría** | Software, Streaming de Video & Ecosistema Multiplataforma |
| **Tiempo de Desarrollo** | ⏱️ **Casi 1 año (~12 meses de ingeniería integral multiplataforma)** |
| **URL Oficial en Producción** | 🌐 [https://cinemadb.club](https://cinemadb.club) |
| **Plataformas Soportadas** | Smart TV (Android TV/FireStick con control D-Pad), Windows (.exe x64), Android (APK Nativo), Web PWA |
| **Empresa Desarrolladora** | **BVX LAB** · Punta Cana, República Dominicana |
| **Arquitecto Principal** | Víctor de Jesús (*Líder SK / Wwb-Daniel*) |

---

## 🚀 Resumen Ejecutivo & Capacidades

**CinemaDB** es una solución integral de distribución y consumo de contenido bajo demanda (VOD) y televisión en directo (Live TV) de escala masiva. Desarrollada desde sus cimientos en **Flutter Native** para ofrecer soporte nativo a múltiples ecosistemas con una única base de código optimizada:

- **Smart TV Living Room OS:** Interfaz adaptada 100% para navegación con **control remoto por cruceta (D-Pad)**, con selección visual de botones, foco dinámico y transiciones suaves a 60 FPS.
- **Windows Desktop Nativo (.exe):** Versión x64 compilada para computadoras de escritorio, con aceleración por hardware DirectX/Vulkan y reproductor flotante PIP.
- **Android APK Nativo:** Experiencia móvil optimizada con soporte gestual para brillo y volumen, descargas para reproducción sin conexión y caché inteligente.
- **Universal Web Platform:** Aplicación web ultra liviana con renderizado reactivo y carga en menos de 1 segundo.

---

## 📊 Métricas & Desempeño en Producción

| Indicador | Registro de Producción |
| :--- | :--- |
| **Dispositivos Online Activos** | `+3,425 Dispositivos Conectados en Tiempo Real` |
| **Descargas Verificadas de APK** | `+2,936 Descargas Directas` |
| **Catálogo Multimedia Indexado** | `+8,100 Episodios, Películas y Documentales` |
| **Resolución & Bitrate** | `HLS Adaptativo hasta 4K 60fps (1080p, 720p, 480p)` |
| **Tiempo de Arranque del Stream** | `< 300 ms de buffering inicial` |

---

## 📐 Diagrama de Arquitectura del Ecosistema

```mermaid
flowchart TD
    subgraph CLIENTS["Dispositivos & Clientes Nativos"]
        TV["Smart TV (Android TV / FireStick D-Pad)"]
        WIN["Windows Desktop (.exe x64)"]
        AND["Android Phone / Tablet (APK Nativo)"]
        WEB["Universal Web App (PWA)"]
    end

    subgraph BACKEND_SERVICES["Servicios Cloud & Streaming"]
        AUTH["Supabase Cloud Auth & Telemetría"]
        DB[("PostgreSQL Realtime Database")]
        CACHE["Caché de Metadatos & Búsqueda"]
        CDN["Red de Distribución de Video HLS 4K"]
    end

    TV -->|Navegación D-Pad & Auth| AUTH
    WIN -->|DirectX Playback & Sync| AUTH
    AND -->|Mobile Gestures & Sync| AUTH
    WEB -->|Universal Streaming| AUTH

    AUTH --> DB
    AUTH --> CACHE

    TV & WIN & AND & WEB -->|Streaming Adaptativo 4K| CDN
```

---

## 📱 Evidencias Visuales: Versión Móvil Android (APK)

<div align="center">

### Interfaz Móvil Nativa (Android)

| Pantalla de Inicio | Explorador de Películas |
| :---: | :---: |
| ![Home](../assets/projects/01-CinemaDB-Ecosistema-Completo/App-Movil-Android/home.jpeg) | ![Películas](../assets/projects/01-CinemaDB-Ecosistema-Completo/App-Movil-Android/apartado%20de%20peliculas.jpeg) |

| Sección de Series | Sección de Anime |
| :---: | :---: |
| ![Series](../assets/projects/01-CinemaDB-Ecosistema-Completo/App-Movil-Android/apartado%20de%20series.jpeg) | ![Anime](../assets/projects/01-CinemaDB-Ecosistema-Completo/App-Movil-Android/apartado%20de%20animes.jpeg) |

| Detalle de Contenido & Reproducción | Capítulos y Temporadas |
| :---: | :---: |
| ![Detalle Película](../assets/projects/01-CinemaDB-Ecosistema-Completo/App-Movil-Android/detalles%20de%20peliculas.jpeg) | ![Capítulos Series](../assets/projects/01-CinemaDB-Ecosistema-Completo/App-Movil-Android/capitulos%20de%20las%20series.jpeg) |

| Buscador Predictivo | Sistema de Reseñas y Comentarios |
| :---: | :---: |
| ![Buscador](../assets/projects/01-CinemaDB-Ecosistema-Completo/App-Movil-Android/buscador%20de%20peliculas%20anime%20series%20etc...jpeg) | ![Comentarios](../assets/projects/01-CinemaDB-Ecosistema-Completo/App-Movil-Android/comentarios%20de%20la%20peliculas.jpeg) |

</div>

---

## 💻 Evidencias Visuales: Versión Web & Desktop Windows (.exe)

<div align="center">

### Interfaz de Escritorio & Panel Web

![Desktop Home](../assets/projects/01-CinemaDB-Ecosistema-Completo/Web-Desktop/desktop_home.png)
*Pantalla Principal de Escritorio con Carruseles Dinámicos y Contenido Destacado*

![Desktop Movies](../assets/projects/01-CinemaDB-Ecosistema-Completo/Web-Desktop/desktop_movies.png)
*Explorador de Películas con Filtrado por Géneros y Calificaciones*

![Desktop Series](../assets/projects/01-CinemaDB-Ecosistema-Completo/Web-Desktop/desktop_series.png)
*Catálogo de Series de Televisión con Ficha Técnica Expandida*

![Desktop Anime](../assets/projects/01-CinemaDB-Ecosistema-Completo/Web-Desktop/desktop_anime.png)
*Sección Especializada en Animación Japonesa con Sincronización de Emisiones*

![Desktop LiveTV](../assets/projects/01-CinemaDB-Ecosistema-Completo/Web-Desktop/desktop_livetv.png)
*Módulo de Televisión en Directo (Live TV) con Canales Internacionales en 1080p/60fps*

![Desktop Chat](../assets/projects/01-CinemaDB-Ecosistema-Completo/Web-Desktop/desktop_chat.png)
*Sala de Chat y Comunidad de Usuarios en Tiempo Real*

![Web Dashboard](../assets/projects/01-CinemaDB-Ecosistema-Completo/Web-Desktop/web_dashboard.png)
*Panel de Métricas y Administración de Contenido Web*

</div>

---

## 📺 Evidencias Visuales: Versión Smart TV (D-Pad Control Remoto)

<div align="center">

![Smart TV Promo](../assets/projects/01-CinemaDB-Ecosistema-Completo/promo_tv.png)
*Experiencia de Sala en Pantallas Grandes: Navegación Optimizada para Control Remoto por Cruceta D-Pad*

</div>

---

<div align="center">

<img src="../assets/bvx_waves.png" alt="BVX LAB" width="120" />

**BVX LAB** · *Create. Develop. Grow.*  
Punta Cana, República Dominicana · WhatsApp: [+1 (829) 654-8277](https://wa.me/18296548277) · Tel: [+1 (849) 261-6367](tel:18492616367)

</div>

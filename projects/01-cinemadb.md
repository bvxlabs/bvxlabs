# CinemaDB (CineMás TV) - Ecosistema de Streaming Multiplataforma

<div align="center">

![BVX LAB Banner](../assets/bvx_banner.gif)

### 🏢 Proyecto Desarrollado por **BVX LAB**
*Create. Develop. Grow. // Punta Cana, República Dominicana*

[![Instagram](https://img.shields.io/badge/Instagram-@bvxlaps-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/bvxlaps/) [![WhatsApp](https://img.shields.io/badge/WhatsApp-+1_(849)_261--6367-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/18492616367) [![Email](https://img.shields.io/badge/Email-bvxlaps@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bvxlaps@gmail.com)

</div>

---

## 📌 Ficha Técnica del Proyecto

| Concepto | Detalle |
| :--- | :--- |
| **Nombre del Proyecto** | **CinemaDB (CineMás TV) - Ecosistema de Streaming Multiplataforma** |
| **Categoría** | Streaming & Multiplataforma |
| **Tiempo de Desarrollo** | ⏱️ **6 semanas** |
| **Enlace / URL Oficial** | 🌐 [cinemadb.club](https://cinemadb.club) |
| **Empresa Desarrolladora** | [BVX LAB](https://github.com/bvxlabs) |
| **Contacto Directo** | WhatsApp: [+1 (849) 261-6367](https://wa.me/18492616367) |

### 🌐 Enlaces y Canales Oficiales
- **Instagram BVX:** [https://www.instagram.com/bvxlaps/](https://www.instagram.com/bvxlaps/)
- **WhatsApp Cotizaciones:** [https://wa.me/18492616367](https://wa.me/18492616367)
- **TikTok:** [https://www.tiktok.com/@lisersk](https://www.tiktok.com/@lisersk)
- **Acceso en Vivo:** [https://cinemadb.club](https://cinemadb.club)

---

## 📖 Resumen Ejecutivo & Alcance

Plataforma completa de streaming de contenido multimedia bajo demanda y canales en vivo (Live TV). Arquitectura nativa desarrollada en Flutter con soporte especializado para navegación remota D-Pad en Smart TVs, ejecutables para Windows PC (.exe), Android APK, Web PWA y backend reactivo con Supabase y PostgreSQL.

## 🛠️ Stack Tecnológico & Arquitectura

- 🔹 **Flutter Native**
- 🔹 **Smart TV D-Pad Engine**
- 🔹 **Windows .exe (Desktop)**
- 🔹 **PostgreSQL / Supabase Realtime**
- 🔹 **HLS 4K Video Player**
- 🔹 **Node.js / Express**
- 🔹 **REST API**

## 📊 Métricas & Resultados Clave

| Métrica | Valor |
| :--- | :--- |
| **Dispositivos Activos** | `+3,425 Online` |
| **Descargas APK** | `+2,936 Descargas` |
| **Catálogo Multimedia** | `+8,100 Episodios & Películas` |
| **Resolución Video** | `HLS Adaptativo hasta 4K 60fps` |

---

## 📐 Diagrama de Arquitectura & Flujo de Datos

```mermaid
graph TD
    User([Usuario Remoto / Multiplataforma]) --> Clients{Clientes Nativos}
    Clients -->|Control Remoto D-Pad| SmartTV[Android TV / FireStick OS]
    Clients -->|Nativo x64| Win[Windows Desktop .exe]
    Clients -->|APK Nativo| Mobile[Android Mobile / Tablet]
    Clients -->|PWA Universal| Web[Web App Universal]
    
    SmartTV & Win & Mobile & Web -->|Auth & Telemetría| Supa[(Supabase Realtime / PostgreSQL)]
    SmartTV & Win & Mobile & Web -->|Streaming HLS 4K| CDN[Content Delivery Network / HLS CDN]
    SmartTV & Win & Mobile & Web -->|Metadatos & Catálogo| APIServer[CinemaDB REST Engine API]
```

---

## 📸 Evidencias Visuales & Capturas del Proyecto

### 🖼️ 00_CinemaDB_Deadpool_Hero.png
![00_CinemaDB_Deadpool_Hero.png](../assets/projects/01-CinemaDB-Ecosistema-Completo/00_CinemaDB_Deadpool_Hero.png)

### 🖼️ promo_tv.png
![promo_tv.png](../assets/projects/01-CinemaDB-Ecosistema-Completo/promo_tv.png)

### 🖼️ desktop_home.png
![desktop_home.png](../assets/projects/01-CinemaDB-Ecosistema-Completo/desktop_home.png)

### 🖼️ desktop_movies.png
![desktop_movies.png](../assets/projects/01-CinemaDB-Ecosistema-Completo/desktop_movies.png)

### 🖼️ desktop_series.png
![desktop_series.png](../assets/projects/01-CinemaDB-Ecosistema-Completo/desktop_series.png)

### 🖼️ desktop_anime.png
![desktop_anime.png](../assets/projects/01-CinemaDB-Ecosistema-Completo/desktop_anime.png)

### 🖼️ desktop_livetv.png
![desktop_livetv.png](../assets/projects/01-CinemaDB-Ecosistema-Completo/desktop_livetv.png)

### 🖼️ desktop_chat.png
![desktop_chat.png](../assets/projects/01-CinemaDB-Ecosistema-Completo/desktop_chat.png)

---

<div align="center">

**¿Deseas implementar una solución similar para tu empresa?**  
[Contáctanos directamente vía WhatsApp](https://wa.me/18492616367?text=Hola%20BVX%20LAB,%20me%20interesa%20un%20proyecto%20como%20CinemaDB%20%2F%20CineM%C3%A1s%20TV)  

**BVX LAB** · *High-Performance Software, AI & Engineering*

</div>

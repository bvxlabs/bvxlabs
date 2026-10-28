# Bacano Roleplay - Portal Comunitario, Sincronización FiveM & OAuth2

<div align="center">

![BVX LAB Banner](../assets/bvx_banner.gif)

### 🏢 Proyecto Desarrollado por **BVX LAB**
*Create. Develop. Grow. // Punta Cana, República Dominicana*

[![Facebook](https://img.shields.io/badge/Facebook-Bvxlab-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://www.facebook.com/people/Bvxlab/61595392246829/) [![Instagram](https://img.shields.io/badge/Instagram-@bvxlaps-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/bvxlaps/) [![WhatsApp](https://img.shields.io/badge/WhatsApp-+1_(829)_654--8277-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/18296548277) [![Email](https://img.shields.io/badge/Email-bvxlaps@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bvxlaps@gmail.com)

</div>

---

## 📌 Ficha Técnica del Proyecto

| Concepto | Detalle |
| :--- | :--- |
| **Nombre del Proyecto** | **Bacano Roleplay - Portal Comunitario, Sincronización FiveM & OAuth2** |
| **Categoría** | Gaming & Comunidad Virtual |
| **Tiempo de Desarrollo** | ⏱️ **2 semanas** |
| **Enlace / URL Oficial** | 🔒 *Servidor Privado Gaming (Privado / Uso Empresarial)* |
| **Empresa Desarrolladora** | [BVX LAB](https://github.com/bvxlabs) |
| **Contacto Directo** | WhatsApp: [+1 (829) 654-8277](https://wa.me/18296548277) · Tel: [+1 (849) 261-6367](tel:18492616367) |

### 🌐 Enlaces y Canales Oficiales
- **Instagram BVX:** [https://www.instagram.com/bvxlaps/](https://www.instagram.com/bvxlaps/)
- **WhatsApp:** [https://wa.me/18296548277](https://wa.me/18296548277)

---

## 📖 Resumen Ejecutivo & Alcance

Plataforma oficial para comunidad de videojuego de rol GTA V FiveM. Sincronización directa con el servidor de juego, sistema de autenticación OAuth2 con Discord, visualizador de jugadores conectados en vivo, gestión de whitelist y reglas comunitarias.

## 🛠️ Stack Tecnológico & Arquitectura

- 🔹 **React**
- 🔹 **Node.js**
- 🔹 **Discord OAuth2 API**
- 🔹 **FiveM Server JSON API**
- 🔹 **Tailwind CSS**
- 🔹 **Vite**

## 📊 Métricas & Resultados Clave

| Métrica | Valor |
| :--- | :--- |
| **Sincronización** | `Polling dinámico de slots del servidor en vivo` |
| **Integración** | `Verificación de roles en Discord en tiempo real` |
| **Experiencia** | `Diseño temático Cyber/Gaming` |

---

## 📐 Diagrama de Arquitectura & Flujo de Datos

```mermaid
graph TD
    Player([Jugador]) --> Portal[Bacano RP Portal Web]
    Portal --> DiscordAuth[Discord OAuth2 Login]
    DiscordAuth --> RoleCheck[Verificación de Roles & Whitelist]
    
    Portal --> FiveMSync[FiveM Server API Client]
    FiveMSync -->|Consulta de Estado y Jugadores| LiveServer[(Servidor Dedicado FiveM)]
```

---

## 📸 Evidencias Visuales & Capturas del Proyecto

### 🖼️ 01_bacano_rp_servidor.png
![01_bacano_rp_servidor.png](../assets/projects/06-Bacano-Roleplay/01_bacano_rp_servidor.png)

---

<div align="center">

**¿Deseas implementar una solución similar para tu empresa?**  
[Contáctanos directamente vía WhatsApp](https://wa.me/18296548277?text=Hola%20BVX%20LAB,%20me%20interesa%20un%20proyecto%20como%20Bacano%20Roleplay%20FiveM%20Hub)  

**BVX LAB** · *High-Performance Software, AI & Engineering*

</div>

# Freska / Orderly Eats - Punto de Venta (POS) & Pedidos para Restaurantes

<div align="center">

![BVX LAB Banner](../assets/bvx_banner.gif)

### 🏢 Proyecto Desarrollado por **BVX LAB**
*Create. Develop. Grow. // Punta Cana, República Dominicana*

[![Facebook](https://img.shields.io/badge/Facebook-Bvxlab-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://www.facebook.com/people/Bvxlab/61595392246829/) [![Instagram](https://img.shields.io/badge/Instagram-@bvxlaps-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/bvxlaps/) [![WhatsApp](https://img.shields.io/badge/WhatsApp-+1_(849)_261--6367-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/18492616367) [![Email](https://img.shields.io/badge/Email-bvxlaps@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bvxlaps@gmail.com)

</div>

---

## 📌 Ficha Técnica del Proyecto

| Concepto | Detalle |
| :--- | :--- |
| **Nombre del Proyecto** | **Freska / Orderly Eats - Punto de Venta (POS) & Pedidos para Restaurantes** |
| **Categoría** | E-Commerce & GastroTech POS |
| **Tiempo de Desarrollo** | ⏱️ **3 semanas** |
| **Enlace / URL Oficial** | 🔒 *GastroTech Solution BVX (Privado / Uso Empresarial)* |
| **Empresa Desarrolladora** | [BVX LAB](https://github.com/bvxlabs) |
| **Contacto Directo** | WhatsApp: [+1 (849) 261-6367](https://wa.me/18492616367) |

### 🌐 Enlaces y Canales Oficiales
- **Instagram BVX:** [https://www.instagram.com/bvxlaps/](https://www.instagram.com/bvxlaps/)
- **WhatsApp Soluciones:** [https://wa.me/18492616367](https://wa.me/18492616367)

---

## 📖 Resumen Ejecutivo & Alcance

Sistema integral de menú digital interactivo, carrito de compras en tiempo real, gestión de estados de órdenes de cocina (preparación, listo, servido) y panel de administración para restaurantes y bares con control de inventario.

## 🛠️ Stack Tecnológico & Arquitectura

- 🔹 **React**
- 🔹 **TypeScript**
- 🔹 **Tailwind CSS**
- 🔹 **Zustand State Management**
- 🔹 **Supabase Realtime**
- 🔹 **Thermal Printing Engine**

## 📊 Métricas & Resultados Clave

| Métrica | Valor |
| :--- | :--- |
| **Actualización de Comandas** | `Instantáneo vía WebSockets (<50ms)` |
| **Optimización de Pedidos** | `Reducción de espera en un 35%` |
| **UX** | `Diseño táctil y optimizado para tablets de servicio` |

---

## 📐 Diagrama de Arquitectura & Flujo de Datos

```mermaid
graph TD
    Diner([Comensal / Cliente]) --> DigitalMenu[Menú Digital QR / Móvil]
    DigitalMenu --> Cart[Carrito & Personalización de Plato]
    Cart --> OrderPush[Envío de Pedido Instantáneo]
    
    OrderPush --> KitchenKDS[Pantalla de Cocina / KDS]
    KitchenKDS -->|Cambio de Estado| StatusTracker[Seguimiento en Vivo del Pedido]
    
    OrderPush --> AdminPOS[Panel Gerencial / POS & Inventario]
```

---

## 📸 Evidencias Visuales & Capturas del Proyecto

### 🖼️ 03-freska-home.png
![03-freska-home.png](../assets/projects/07-Orderly-Eats-Freska/03-freska-home.png)

### 🖼️ 03-freska-menu.png
![03-freska-menu.png](../assets/projects/07-Orderly-Eats-Freska/03-freska-menu.png)

### 🖼️ 03-freska-cart.png
![03-freska-cart.png](../assets/projects/07-Orderly-Eats-Freska/03-freska-cart.png)

### 🖼️ 03-freska-order-status.png
![03-freska-order-status.png](../assets/projects/07-Orderly-Eats-Freska/03-freska-order-status.png)

### 🖼️ 03-freska-admin.png
![03-freska-admin.png](../assets/projects/07-Orderly-Eats-Freska/03-freska-admin.png)

---

<div align="center">

**¿Deseas implementar una solución similar para tu empresa?**  
[Contáctanos directamente vía WhatsApp](https://wa.me/18492616367?text=Hola%20BVX%20LAB,%20me%20interesa%20un%20proyecto%20como%20Freska%20POS%20%26%20Restaurant%20Orders)  

**BVX LAB** · *High-Performance Software, AI & Engineering*

</div>

# Aduanify 🚚🛂

[![Estado del Proyecto](https://img.shields.io/badge/estado-En%20Desarrollo-brightgreen?style=for-the-badge)](https://github.com/USUARIO/aduanify)
[![Licencia](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)](https://github.com/USUARIO/aduanify/blob/main/LICENSE)
[![Versión](https://img.shields.io/badge/version-0.1.0--alpha-orange?style=for-the-badge)](https://github.com/USUARIO/aduanify)

**Visibilidad y predictibilidad en tiempo real para la logística transfronteriza en Tijuana.**

Aduanify es una plataforma SaaS B2B diseñada para resolver el principal punto de fricción de la industria en Tijuana, B.C.: la falta de visibilidad y predictibilidad en los cruces aduanales entre México y Estados Unidos.

---

## 🎯 El Lienzo de Aduanify (Lean Canvas)

Nuestro modelo de negocio se basa en la metodología Lean Startup, enfocada en resolver problemas reales y construir una solución sostenible.

### 1️⃣ Problema

El ecosistema logístico y de manufactura (maquila) en Tijuana sufre de:
* **Incertidumbre total** sobre los tiempos de espera y el estado de los envíos en la aduana.
* **Costos elevados** por demoras, multas y tiempos muertos de transporte.
* **Planificación ineficiente** de la producción y la cadena de suministro debido a ETAs (Tiempos Estimados de Arribo) poco fiables.
* **Herramientas existentes** que son demasiado costosas (nivel Enterprise) o inadecuadas para las necesidades específicas de las PyMEs locales.

### 2️⃣ Solución

Una plataforma SaaS simple, accesible y enfocada:
* **Dashboard centralizado** con seguimiento GPS en tiempo real de unidades.
* **Alertas automáticas** sobre el estado del cruce (enviado, en inspección, liberado).
* **Algoritmo de ETAs predictivos** basado en datos históricos y en vivo del cruce Tijuana-San Diego.
* **Reportes y analítica** para optimizar rutas y tiempos.

### 3️⃣ Métricas Clave

* **MRR** (Ingreso Mensual Recurrente)
* **Tasa de Abandono (Churn Rate)**
* **CAC** (Costo de Adquisición de Cliente)
* **LTV** (Valor de Vida del Cliente)

### 4️⃣ Propuesta Única de Valor (UVP)

> **Visibilidad y predictibilidad en tus cruces fronterizos.**
>
> Simplificamos la logística aduanal para las PyMEs de Tijuana, convirtiendo la incertidumbre en control y eficiencia operativa.

### 5️⃣ Ventaja Injusta

* **Hiper-enfoque local:** Nuestro algoritmo y plataforma están entrenados y diseñados *exclusivamente* para la dinámica del cruce Tijuana-San Diego.
* **Conocimiento del terreno:** Equipo fundador con experiencia directa y redes de contacto en el ecosistema logístico y aduanal de la región.
* **Agilidad:** Capacidad de adaptarnos rápidamente a las necesidades de las PyMEs, a diferencia de los grandes corporativos de software.

### 6️⃣ Canales

* Marketing digital enfocado (LinkedIn, Google Ads)
* Ventas directas y demos personalizadas
* Alianzas estratégicas con agentes aduanales y cámaras industriales (CANACINTRA, INDEX).

### 7️⃣ Segmentos de Clientes

* **PyMEs de Manufactura (Maquiladoras):** Gerentes de logística, producción y cadena de suministro.
* **Empresas de Transporte y Logística:** Dueños de flotillas y coordinadores de tráfico que sirven a la industria maquiladora.

### 8️⃣ Estructura de Costos

* **Costos Fijos:** Salarios (desarrollo, ventas, soporte), renta de oficina, licencias de software.
* **Costos Variables:** Infraestructura en la nube (AWS/GCP), costos de APIs (Google Maps), marketing y comisiones de venta.

### 9️⃣ Flujos de Ingresos (Modelo de Negocio)

Utilizamos un modelo de **Suscripción B2B por Niveles (Tiered SaaS)** para ofrecer flexibilidad y escalabilidad a nuestros clientes.

| Plan | Características Clave | Precio (MXN / mes) |
| :--- | :--- | :--- |
| **Esencial** | • Hasta 5 unidades <br> • Seguimiento GPS <br> • Historial de 30 días | **$3,500** |
| **Profesional** | • Hasta 20 unidades <br> • Todo en Esencial + <br> • Alertas de Aduanas <br> • ETAs Predictivos | **$8,000** |
| **Empresarial** | • Unidades ilimitadas <br> • Todo en Profesional + <br> • Integración API <br> • Soporte Dedicado | **Contacto** |

---

## 💻 Pila Tecnológica (Propuesta)

Este proyecto busca utilizar un stack moderno, escalable y eficiente para construir la mejor solución para nuestros clientes.

* **Frontend:** React (Vite) o SvelteKit
* **Estilos:** Tailwind CSS
* **Backend:** Node.js (Fastify) o Python (FastAPI)
* **Base de Datos:** PostgreSQL con extensión PostGIS (para geo-data) + Redis (para caché)
* **Infraestructura:** Despliegue en Google Cloud (GKE) o AWS (EKS)
* **APIs Externas:** Google Maps (para mapas y rutas), y APIs de Aduanas/Transporte a medida que se integren.

## 🚀 Hoja de Ruta (Roadmap)

* **Q4 2025:** Investigación de mercado y validación del modelo de negocio.
* **Q1 2026:** Desarrollo del MVP (Producto Mínimo Viable) y pruebas Alfa con socios clave.
* **Q2 2026:** Lanzamiento de la Beta cerrada e incorporación de los primeros clientes de pago.
* **Q3 2026:** Lanzamiento público en Tijuana. Inicio de campañas de marketing.

## 🤝 Cómo Contribuir

¡Estamos construyendo el futuro de la logística en Tijuana y buscamos talento! Si estás interesado en contribuir con el proyecto, ya sea como desarrollador, diseñador, o experto en la industria:

1.  Abre un **Issue** para discutir tu idea o el problema que encontraste.
2.  Haz un **Fork** de este repositorio.
3.  Crea una nueva rama (`git checkout -b feature/nueva-funcionalidad`).
4.  Haz tus cambios y haz **Commit** (`git commit -m 'Agrega nueva funcionalidad'`).
5.  Haz **Push** a tu rama (`git push origin feature/nueva-funcionalidad`).
6.  Abre un **Pull Request** para revisión.

También puedes contactarnos directamente a [**hola@aduanify.com**](mailto:hola@aduanify.com) (email de ejemplo).

## 📜 Licencia

Este proyecto está bajo la **Licencia MIT**. Puedes ver el archivo `LICENSE` (a ser creado) para más detalles.
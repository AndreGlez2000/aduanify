# Aduanify 🚚🛂

[![Estado del Proyecto](https://img.shields.io/badge/estado-En%20Desarrollo-brightgreen?style=for-the-badge)](https://github.com/USUARIO/aduanify)
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
* **Empresas de Transporte y Logística:** Dueños de flotillas y coordinadores de tráfico que sirven a la industria maquila.

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

## 🚀 Hoja de Ruta Detallada

Nuestra estrategia de lanzamiento está dividida en fases claras para asegurar la validación del producto y un crecimiento sostenible.

### **Fase 0: Validación y Fundación (Q4 2025)**
* **Validación de Problema:** Completar +50 entrevistas con Gerentes de Logística, Agentes Aduanales y dueños de transporte en Tijuana.
* **Validación de Solución:** Presentar prototipos de UI/UX (Figma) a clientes potenciales y obtener retroalimentación.
* **Constitución:** Creación legal de la empresa "Aduanify, S.A. de C.V.".
* **Arquitectura:** Definición de la arquitectura técnica detallada y selección de proveedores de nube.

### **Fase 1: Desarrollo del MVP (Q1 2026)**
* **Producto Mínimo Viable (MVP):** Desarrollo del *core* de la plataforma:
    * Módulo de alta/baja de unidades y operadores.
    * Dashboard principal con mapa de seguimiento GPS.
    * Sistema de cuentas de usuario y facturación.
* **Socios Alfa:** Asegurar convenios con 2-3 empresas locales ("Alpha Partners") para pruebas gratuitas.
* **Algoritmo v0.1:** Iniciar el desarrollo del algoritmo predictivo de ETAs, basado inicialmente en datos históricos.

### **Fase 2: Beta Cerrada y Primer Ingreso (Q2 2026)**
* **Lanzamiento Beta:** Implementación de Aduanify en las operaciones de los "Alpha Partners".
* **Iteración Rápida:** Ciclos de desarrollo semanales para corregir bugs y aplicar mejoras basadas en el feedback real.
* **Primeros Clientes:** Incorporar a los primeros 5-10 clientes de pago (Planes Esencial/Profesional) con un descuento "Beta Tester".
* **Algoritmo v0.2:** Refinar el algoritmo de ETAs con los primeros flujos de datos en tiempo real.
* **Marketing:** Construcción del *landing page* oficial y sistema de *onboarding* de clientes.

### **Fase 3: Lanzamiento Público y Crecimiento (Q3 2026)**
* **Lanzamiento Oficial:** Apertura pública de la plataforma para el mercado de Tijuana.
* **Adquisición:** Activación de campañas de marketing digital (LinkedIn, Google Ads) y un vendedor de campo.
* **Soporte:** Contratación del primer rol de Éxito del Cliente (Customer Success) para gestionar el *onboarding* y la retención.
* **Alianzas:** Formalizar alianzas con 2-3 agencias aduanales para co-marketing y referencias.

### **Fase 4: Escalamiento y Expansión de Producto (Q4 2026)**
* **Métricas Objetivo:** Alcanzar 30 clientes de pago activos.
* **Producto Empresarial:** Desarrollo del módulo de "Integración API" para clientes del plan Empresarial.
* **Nuevas Funcionalidades:** Iniciar desarrollo de analítica avanzada, reportes de desempeño de flotillas y optimización de rutas.
* **Expansión Geográfica:** Comenzar el análisis de mercados adyacentes (ej. Mexicali, Ensenada) para la expansión en 2027.

## 🤝 Cómo Contribuir

¡Estamos construyendo el futuro de la logística en Tijuana y buscamos talento! Si estás interesado en contribuir con el proyecto, ya sea como desarrollador, diseñador, o experto en la industria:

1.  Abre un **Issue** para discutir tu idea o el problema que encontraste.
2.  Haz un **Fork** de este repositorio.
3.  Crea una nueva rama (`git checkout -b feature/nueva-funcionalidad`).
4.  Haz tus cambios y haz **Commit** (`git commit -m 'Agrega nueva funcionalidad'`).
5.  Haz **Push** a tu rama (`git push origin feature/nueva-funcionalidad`).
6.  Abre un **Pull Request** para revisión.

También puedes contactarnos directamente a [**hola@aduanify.com**](mailto:hola@aduanify.com) (email de ejemplo).
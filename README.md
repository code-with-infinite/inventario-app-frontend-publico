# 📦 Plataforma de Gestión - Inventario App Frontend / Inventory App Frontend

[![Live Demo](https://img.shields.io/badge/Live_Demo-Ver_Aplicación_en_Vivo-success?style=for-the-badge&logo=render)](https://inventario-app-frontend-8yoi.onrender.com) 
[![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)]()
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)]()
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)]()

[🇪🇸 Español](#-español) · [🇬🇧 English](#-english)

---

## 🇪🇸 Español

Este proyecto es una aplicación web con una estructura desacoplada diseñada exclusivamente para el frontend de un software de inventario. Se consolida como una plataforma de gestión de tareas en tiempo real que ofrece una interfaz moderna, limpia y completamente optimizada.

🔗 **[Prueba la aplicación en vivo aquí](https://inventario-app-frontend-8yoi.onrender.com)**

### 💡 **Nota de Arquitectura Comercial:** El código fuente original de esta aplicación de inventario está resguardado en un repositorio privado por seguridad y confidencialidad. Para este portafolio público, configuré un script automatizado en el ciclo *Post-Build* para inyectar ofuscación matemática avanzada y protección *anti-tampering* en el producto empaquetado, demostrando de forma práctica cómo se despliega un software comercial en el mundo real protegiendo la propiedad intelectual sin afectar la experiencia de usuario.

### 🚀 Estado del Proyecto: 70% (Fase de Estabilización)

Actualmente, el sistema cuenta con la estructura base de componentes de inventario, sincronización de tareas en tiempo real y vistas asíncronas optimizadas. Se encuentra en desarrollo el 30% restante enfocado en módulos avanzados de analítica visual, reportes de stock históricos y filtros complejos de búsqueda.

### 🛠️ Tecnologías Utilizadas
* **Framework Principal:** Angular (TypeScript).
* **Estilos & Diseño:** Tailwind CSS / HTML5 (Interfaz moderna y diseño altamente responsivo).
* **Estado & Lógica:** JavaScript / TypeScript (ES6+) con manejo de flujos reactivos.
* **Entorno de Ejecución:** Node.js (Ecosistema de Angular CLI para compilación eficiente).

### 💡 Características Principales
* **Estructura Desacoplada:** Frontend totalmente independiente preparado para conectarse a cualquier API o Backend de manera transparente.
* **Gestión en Tiempo Real:** Interfaz dinámica orientada a tareas e inventarios que actualiza los estados de manera inmediata.
* **Diseño Moderno & Optimizado:** Experiencia de usuario (UX) fluida construida sobre componentes modulares de Tailwind CSS.

### ⚙️ Arquitectura y Seguridad Local
* **Variables de Entorno:** Configuración gestionada y aislada mediante los archivos nativos de Angular (`src/environments/`) para mitigar la exposición de credenciales o URLs de servidores de datos en producción.
* **Control de Versiones:** Repositorio estructurado rigurosamente bajo Git, garantizando la exclusión estricta de carpetas de dependencias (`node_modules`) y archivos de caché mediante un `.gitignore` optimizado para Angular.

### 🛡️ Blindaje y Protección del Código Fuente (Portafolio Seguro)
* **Compilación Con Ofuscación Avanzada:** Para mitigar ataques de ingeniería inversa, el código de producción se compila utilizando un script personalizado en el ciclo *Post-Build* sobre **Esbuild**. 
* **Estructura Criptográfica:** Toda la lógica de componentes y librerías reactivas dentro del bundle principal (`main.js`) es transformada a un laberinto indescifrable de arreglos hexadecimales, codificación en Base64 e inyección de código muerto (*Dead Code Injection*).
* **Mecanismo Anti-Depuración (Anti-Tampering):** El software implementa una protección estricta en tiempo de ejecución (`debugProtection`). Si se intentan abrir las herramientas de desarrollador del navegador (DevTools) para inspeccionar los procesos lógicos, el script activa de manera inmediata un congelamiento de pila a través de bucles condicionales infinitos, neutralizando la inspección maliciosa sin afectar la experiencia de usuario nativa.


### 🔒 Arquitectura y Repositorio del Backend
Por razones de seguridad, confidencialidad y protección de propiedad intelectual, el código fuente del servidor se encuentra alojado en un **repositorio privado**. El acceso está restringido exclusivamente al autor del proyecto y evaluadores externos autorizados.

El núcleo de servicios se encuentra **desplegado y en ejecución en entornos de producción en la nube (Render)** bajo una arquitectura de microservicios independiente.

Sin embargo, para fines de evaluación técnica, se detalla la pila tecnológica que compone el core del servidor:
* 🖥️ **Entorno de Ejecución & Hosting:** Node.js / Desplegado en la nube a través de Render.
* 🗄️ **Base de Datos:** PostgreSQL (Diseño relacional optimizado para la integridad del inventario).
* 🛡️ **Seguridad:** Implementación de variables de entorno protegidas y mitigación de brechas de exposición en producción.

### 👨‍💻 Autor
* **Creado por:** [code-with-infinite](https://github.com/code-with-infinite) (Desarrollador de Software)

<br>

---

## 🇬🇧 English

This project is a web application with a decoupled structure designed exclusively for the frontend of an inventory software. It is consolidated as a real-time task management platform that offers a modern, clean, and fully optimized interface.

🔗 **[Test the live application here](https://inventario-app-frontend-8yoi.onrender.com)**

### 💡 **Commercial Architecture Note:** The original source code for this inventory application is securely hosted in a private repository for security and confidentiality reasons. For this public portfolio, I configured an automated *Post-Build* script to inject advanced mathematical obfuscation and anti-tampering defenses into the final bundle, practically demonstrating how commercial software is deployed in the real world to protect intellectual property while preserving seamless user performance.

### 🚀 Project Status: 70% (Stabilization Phase)
Currently, the system has the base structure of inventory components, real-time task synchronization, and optimized asynchronous views. The remaining 30% is in development, focusing on advanced visual analytics modules, historical stock reports, and complex search filters.

### 🛠️ Technologies Used
* **Core Framework:** Angular (TypeScript).
* **Styles & Design:** Tailwind CSS / HTML5 (Modern interface and highly responsive design).
* **State & Logic:** JavaScript / TypeScript (ES6+) with reactive flow management.
* **Runtime Environment:** Node.js (Angular CLI ecosystem for efficient compilation).

### 💡 Key Features
* **Decoupled Structure:** Fully independent frontend ready to connect transparently to any API or Backend.
* **Real-Time Management:** Dynamic interface oriented towards tasks and inventories that updates states immediately.
* **Modern & Optimized Design:** Fluid user experience (UX) built on modular Tailwind CSS components.

### ⚙️ Architecture and Local Security
* **Environment Variables:** Managed and isolated configuration using Angular's native files (`src/environments/`) to mitigate the exposure of credentials or data server URLs in production.
* **Version Control:** Repository rigorously structured under Git, ensuring the strict exclusion of dependency folders (`node_modules`) and cache files via an optimized `.gitignore` for Angular.

### 🛡️ Source Code Hardening and Protection (Secure Portfolio)
* **Advanced Obfuscation Build:** To mitigate reverse engineering attempts, the production code is compiled leveraging a customized *Post-Build* script on top of **Esbuild**.
* **Cryptographic Architecture:** All component logic and reactive flows within the core bundle (`main.js`) are refactored into an indecipherable maze of hexadecimal naming structures, Base64 encryption strings, and Dead Code Injection.
* **Anti-Tampering & Anti-Debugging Mechanism:** The client-side software enforces a strict runtime defense checkpoint (`debugProtection`). If browser Developer Tools (DevTools) are attached to inspect core operational loops, the bundle instantly triggers an internal runtime stack freeze using infinite debugger traps, defusing profiling attempts while preserving standard user performance.


### 🔒 Backend Architecture and Repository
For security, confidentiality, and intellectual property protection reasons, the server source code is hosted in a **private repository**. Access is strictly restricted to the project author and authorized external evaluators.

The core services are **deployed and running in cloud production environments (Render)** under an independent microservices architecture.

However, for technical evaluation purposes, the technology stack making up the server core is outlined below:
* 🖥️ **Runtime Environment & Hosting:** Node.js / Cloud deployment through Render.
* 🗄️ **Database:** PostgreSQL (Relational design optimized for inventory integrity).
* 🛡️ **Security:** Implementation of protected environment variables and mitigation of production exposure risks.


### 👨‍💻 Author
* **Created by:** [code-with-infinite](https://github.com/code-with-infinite) (Software Developer)

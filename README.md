# 📦 Plataforma de Gestión - Inventario App Frontend / Inventory App Frontend

[![Live Demo](https://img.shields.io/badge/Live_Demo-Ver_Aplicación_en_Vivo-success?style=for-the-badge&logo=render)](https://inventario-app-frontend-8yoi.onrender.com) 
[![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)]()
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)]()
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)]()

[🇪🇸 Español](#-español) · [🇬🇧 English](#-english)

---

## 🇪🇸 Español

Este proyecto es una aplicación web con una estructura desacoplada diseñada exclusivamente para el frontend de un software de gestión de inventarios. Ofrece una interfaz moderna, limpia y completamente optimizada para la administración y consulta de información de inventario.

🔗 **[Prueba la aplicación en vivo aquí](https://inventario-app-frontend-8yoi.onrender.com)**

### 💡 **Nota de Arquitectura Comercial:**

El código fuente original de esta aplicación de inventario está resguardado en un repositorio privado por seguridad y confidencialidad. Para este portafolio público, configuré un script automatizado en el ciclo *Post-Build* para aplicar ofuscación avanzada y excluir *source maps* en el producto empaquetado.

Esto demuestra una práctica habitual de despliegue comercial para dificultar la ingeniería inversa, sin prometer una protección absoluta ni afectar la experiencia de usuario.

Este repositorio público contiene documentación, enlaces a la demo y los archivos compilados de producción procedentes de la carpeta `dist`, preparados mediante el proceso de ofuscación. No incluye el código fuente original del frontend ni del backend, ni el historial de desarrollo del repositorio privado. Por esta razón, funciona como una publicación de portafolio y demostración de la aplicación, no como un repositorio reproducible del proyecto original.

### 🚀 Estado del Proyecto: 70% (Fase de Estabilización)

Actualmente, el sistema cuenta con la estructura base de componentes de inventario, gestión de información y vistas optimizadas. Se encuentra en desarrollo el 30% restante enfocado en módulos avanzados de analítica visual, reportes de stock históricos y filtros complejos de búsqueda.

### 🛠️ Tecnologías Utilizadas

* **Framework Principal:** Angular (TypeScript).
* **Estilos & Diseño:** Tailwind CSS / HTML5 (Interfaz moderna y diseño altamente responsivo).
* **Estado & Lógica:** JavaScript / TypeScript (ES6+) con manejo de flujos reactivos.
* **Entorno de Ejecución:** Node.js (Ecosistema de Angular CLI para compilación eficiente).

### 💡 Características Principales

* **Estructura Desacoplada:** Frontend totalmente independiente preparado para conectarse a cualquier API o Backend de manera transparente.
* **Gestión de Inventarios:** Interfaz dinámica orientada a la administración de productos, existencias y datos de inventario.
* **Diseño Moderno & Optimizado:** Experiencia de usuario (UX) fluida construida sobre componentes modulares de Tailwind CSS.

### ⚙️ Arquitectura y Seguridad Local

* **Variables de Entorno:** Configuración gestionada y aislada mediante los archivos nativos de Angular (`src/environments/`) para organizar la configuración pública por entorno. En Angular, todo lo que se incluye en el frontend es público, por lo que estas variables no deben usarse para almacenar secretos ni credenciales sensibles; esas credenciales se gestionan exclusivamente en el backend.
* **Control de Versiones:** Repositorio estructurado rigurosamente bajo Git, garantizando la exclusión estricta de carpetas de dependencias (`node_modules`) y archivos de caché mediante un `.gitignore` optimizado para Angular. El repositorio público se creó desde cero para evitar exponer el historial del código privado.

### 🛡️ Blindaje y Protección del Código Fuente (Portafolio Seguro)

* **Compilación Con Ofuscación Avanzada:** Para dificultar la ingeniería inversa, el código de producción se compila utilizando un script personalizado en el ciclo *Post-Build* sobre **Esbuild**. La ofuscación es una medida disuasoria, no una garantía criptográfica ni una barrera absoluta.
* **Ofuscación del Bundle:** La lógica del bundle principal (`main.js`) se transforma mediante minificación, renombrado de identificadores, codificación de cadenas y técnicas de ofuscación. Se excluyen *source maps* en producción. Esto no vuelve el código indescifrable ni sustituye la seguridad del backend.
* **Nota sobre Anti-Depuración (Anti-Tampering):** La demo pública no incorpora mecanismos agresivos de anti-depuración, como bucles infinitos o *debugger traps*, porque pueden afectar rendimiento, accesibilidad y estabilidad. La protección se limita a minificación, ofuscación y ausencia de *source maps*; las credenciales y la lógica sensible permanecen en el backend privado.

### 🔒 Arquitectura y Repositorio del Backend

Por razones de seguridad, confidencialidad y protección de propiedad intelectual, el código fuente del servidor se encuentra alojado en un **repositorio privado**. El acceso está restringido exclusivamente al autor del proyecto y evaluadores externos autorizados.

El núcleo de servicios se encuentra **desplegado y en ejecución en entornos de producción en la nube (Render)** bajo una arquitectura de microservicios independiente.

Sin embargo, para fines de evaluación técnica, se detalla la pila tecnológica que compone el core del servidor:

* 🖥️ **Entorno de Ejecución & Hosting:** Node.js / Desplegado en la nube a través de Render.
* 🗄️ **Base de Datos:** PostgreSQL (Diseño relacional optimizado para la integridad del inventario).
* 🛡️ **Seguridad:** Implementación de variables de entorno protegidas y mitigación de brechas de exposición en producción.

### 👨‍💻 Autor

* **Creado por:** [code-with-infinite](https://github.com/code-with-infinite) (Desarrollador de Software)
* © Todos los derechos reservados.

<br>

---

## 🇬🇧 English

This project is a web application with a decoupled structure designed exclusively for the frontend of an inventory management software. It provides a modern, clean, and fully optimized interface for managing and consulting inventory information.

🔗 **[Test the live application here](https://inventario-app-frontend-8yoi.onrender.com)**

### 💡 **Commercial Architecture Note:**

The original source code for this inventory application is securely hosted in a private repository for security and confidentiality reasons. For this public portfolio, I configured an automated *Post-Build* script to apply advanced obfuscation and exclude source maps from the packaged production bundle.

This demonstrates a common commercial deployment practice to make reverse engineering harder, without promising absolute protection or affecting user experience.

This public repository contains documentation, demo links, and compiled production files originating from the `dist` folder, prepared through the obfuscation process. It does not include the original frontend or backend source code, nor the development history of the private repository. For this reason, it serves as a portfolio publication and application demonstration, not as a reproducible repository of the original project.

### 🚀 Project Status: 70% (Stabilization Phase)

Currently, the system has the base structure of inventory components, information management, and optimized views. The remaining 30% is in development, focusing on advanced visual analytics modules, historical stock reports, and complex search filters.

### 🛠️ Technologies Used

* **Core Framework:** Angular (TypeScript).
* **Styles & Design:** Tailwind CSS / HTML5 (Modern interface and highly responsive design).
* **State & Logic:** JavaScript / TypeScript (ES6+) with reactive flow management.
* **Runtime Environment:** Node.js (Angular CLI ecosystem for efficient compilation).

### 💡 Key Features

* **Decoupled Structure:** Fully independent frontend ready to connect transparently to any API or Backend.
* **Inventory Management:** Dynamic interface focused on managing products, stock levels, and inventory data.
* **Modern & Optimized Design:** Fluid user experience (UX) built on modular Tailwind CSS components.

### ⚙️ Architecture and Local Security

* **Environment Variables:** Managed and isolated configuration using Angular's native files (`src/environments/`) to organize public configuration per environment. In Angular, everything included in the frontend is public, so these variables must not be used to store secrets or sensitive credentials; those credentials are managed exclusively in the backend.
* **Version Control:** Repository rigorously structured under Git, ensuring the strict exclusion of dependency folders (`node_modules`) and cache files via an optimized `.gitignore` for Angular. The public repository was created from scratch to avoid exposing the private code history.

### 🛡️ Source Code Hardening and Protection (Secure Portfolio)

* **Advanced Obfuscation Build:** To make reverse engineering harder, the production code is compiled leveraging a customized *Post-Build* script on top of **Esbuild**. Obfuscation is a deterrent measure, not a cryptographic guarantee or an absolute barrier.
* **Bundle Obfuscation:** The logic within the core bundle (`main.js`) is transformed through minification, identifier renaming, string encoding, and obfuscation techniques. Source maps are excluded in production. This does not make the code indecipherable and does not replace backend security.
* **Note on Anti-Debugging (Anti-Tampering):** The public demo does not include aggressive anti-debugging mechanisms, such as infinite loops or debugger traps, because they can affect performance, accessibility, and stability. Protection is limited to minification, obfuscation, and the absence of source maps; credentials and sensitive logic remain in the private backend.

### 🔒 Backend Architecture and Repository

For security, confidentiality, and intellectual property protection reasons, the server source code is hosted in a **private repository**. Access is strictly restricted to the project author and authorized external evaluators.

The core services are **deployed and running in cloud production environments (Render)** under an independent microservices architecture.

However, for technical evaluation purposes, the technology stack making up the server core is outlined below:

* 🖥️ **Runtime Environment & Hosting:** Node.js / Cloud deployment through Render.
* 🗄️ **Database:** PostgreSQL (Relational design optimized for inventory integrity).
* 🛡️ **Security:** Implementation of protected environment variables and mitigation of production exposure risks.

### 👨‍💻 Author

* **Created by:** [code-with-infinite](https://github.com/code-with-infinite) (Software Developer)
* © All rights reserved.

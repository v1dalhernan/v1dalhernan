# Jhonathan Vidal

**Ingeniero de Software y Desarrollador Fullstack · Software Engineer & Fullstack Mobile/Web Developer**

Especializado en **Clean Architecture**, aplicaciones móviles nativas y multiplataforma (**Flutter**, **SwiftUI**) y desarrollo backend y frontend empresarial (**NestJS**, **Angular**, **Node.js**).

Specialized in **Clean Architecture**, native & cross-platform mobile apps (**Flutter**, **SwiftUI**), and enterprise backend/frontend systems (**NestJS**, **Angular**, **Node.js**).

---

## Contacto · Contact

[jhonathanvidalvv@gmail.com](mailto:jhonathanvidalvv@gmail.com) ·
[LinkedIn](https://www.linkedin.com/in/jhonathan-vidal/) ·
[GitHub](https://github.com/v1dalhernan)

---

## Proyectos Destacados · Featured Showcases

### [Trama · Mensajería offline en malla · Flutter App](https://github.com/v1dalhernan/message_blue)

[![Descargar APK demo](https://img.shields.io/badge/Descargar-APK_demo-3DDC84?style=flat-square&logo=android&logoColor=white)](https://github.com/v1dalhernan/message_blue/releases/latest)

**ES:** Mensajería sin Internet entre teléfonos cercanos desarrollada en **Flutter** sobre **Google Nearby Connections** (Bluetooth, BLE y Wi-Fi). Los dispositivos forman una **red en malla multi-salto**: un chat privado de A a C puede viajar a través de B sin que B pueda leerlo, gracias a **cifrado de extremo a extremo** (X25519 + HKDF + AES-256-GCM). Incluye verificación de enlaces con PIN rotativo, texto, fotos y notas de voz, ediciones, confirmaciones de lectura, entrega diferida, servicio nativo en **Kotlin** y **CI/CD con GitHub Actions** que publica los APK en cada versión.

**EN:** Offline peer-to-peer messenger built with **Flutter** on **Google Nearby Connections** (Bluetooth, BLE, Wi-Fi). Phones form a **multi-hop mesh network**: a private chat from A to C can be relayed through B without B being able to read it, using **end-to-end encryption** (X25519 + HKDF + AES-256-GCM). Features rotating-PIN link verification, text, photos and voice notes, edits, read receipts, store-and-forward delivery, a native **Kotlin** foreground service, and **GitHub Actions CI/CD** that publishes APKs on every release.

---

### [Deals & Coupons Marketplace · Flutter App](https://github.com/v1dalhernan/flutter-deals-marketplace)

**ES:** Aplicación móvil de marketplace y cuponera desarrollada en **Flutter** con **Feature-First Clean Architecture**, gestión de estado con **BLoC**, carrito de compras, catálogo categorizado, billetera de cupones con validación dinámica de código QR y un **motor determinista de modo demo/training** que permite ejecutar la app de forma 100% offline sin dependencias externas.

**EN:** Full-featured deals and coupons marketplace mobile app built in **Flutter** with **Feature-First Clean Architecture**, **BLoC State Management**, shopping cart, dynamic QR coupon redemption, and a **deterministic offline training engine** supporting zero-credential simulated backend scenarios.

---

### [Flutter Clean Architecture Showcase](https://github.com/v1dalhernan/flutter-clean-architecture-showcase)

**ES:** Aplicación móvil offline-first desarrollada con **Flutter**, aplicando estrictamente **Clean Architecture** (separación en capas *Domain*, *Data*, *Presentation* y *Core*), gestión de estado con **BLoC**, inyección de dependencias con `get_it`, persistencia local en **SQLite** (`sqflite`) y cobertura completa de pruebas unitarias y de BLoC con `mocktail` y `bloc_test`.

**EN:** Production-grade offline-first mobile application built with **Flutter**, demonstrating **Clean Architecture** (*Domain*, *Data*, *Presentation*, and *Core* layers), **BLoC State Management**, `get_it` dependency injection, local **SQLite** persistence (`sqflite`), and 100% passing unit & BLoC tests with `mocktail` and `bloc_test`.

---

### [NestJS Clean Architecture API](https://github.com/v1dalhernan/nestjs-clean-architecture-api)

**ES:** API RESTful empresarial desarrollada con **NestJS** y **TypeScript**, implementando **Arquitectura Hexagonal / Limpia**, autenticación segura **JWT con Passport**, hashing con **bcrypt**, persistencia desacoplada con **TypeORM (SQLite)**, validación con `class-validator`, documentación interactiva con **Swagger / OpenAPI 3.0** y pruebas unitarias con **Jest**.

**EN:** Enterprise-ready RESTful API built with **NestJS** and **TypeScript**, showcasing **Hexagonal / Clean Architecture**, secure **JWT Authentication with Passport**, **TypeORM (SQLite)** persistence, strict DTO validation, interactive **Swagger / OpenAPI 3.0** documentation, and unit testing with **Jest**.

---

### [Angular 18 Clean Architecture Dashboard](https://github.com/v1dalhernan/angular-clean-architecture-dashboard)

**ES:** Panel de administración y dashboard reactivo construido con **Angular 18**, aprovechando las últimas capacidades del framework: **Standalone Components** (sin NgModules), reactividad reactiva con **Angular Signals** (`signal`, `computed`), arquitectura de componentes inteligentes y de presentación (*Smart & Dumb components*), formularios reactivos y desacoplamiento de almacenamiento.

**EN:** Modern reactive web dashboard built with **Angular 18**, utilizing framework advancements: **Standalone Components**, fine-grained reactivity via **Angular Signals** (`signal`, `computed`), **Smart & Dumb Component Pattern**, reactive forms, and decoupled repository storage.

---

### [Paws · iOS App](https://github.com/v1dalhernan/Paws)

**ES:** Aplicación nativa para iOS desarrollada con **SwiftUI** y **SwiftData** para registrar mascotas, editar información, seleccionar fotografías mediante `PhotosPicker` y persistir datos localmente.

**EN:** Native iOS application built with **SwiftUI** and **SwiftData** to register pets, edit records, choose photos using `PhotosPicker`, and store data locally in a modern CRUD flow.

---

### [Consola de Información de Ciudad](https://github.com/v1dalhernan/consola-informacion-de-ciudad)

**ES:** Herramienta de línea de comandos en **Node.js** que interactúa con las APIs de Mapbox y OpenWeather, gestionando variables de entorno, peticiones con Axios e historial con persistencia JSON.

**EN:** Command-line automation tool in **Node.js** integrating Mapbox and OpenWeather APIs with environment variables, Axios HTTP requests, and JSON persistence.

---

## Aplicaciones en Producción · Published in Production

### [Schedule: Horario y Tareas · Google Play Store](https://play.google.com/store/apps/details?id=com.threedors.schedule_app)

[![Google Play](https://img.shields.io/badge/Google_Play-Schedule:_Horario_y_Tareas-414141?style=flat-square&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.threedors.schedule_app)

**ES:** Aplicación móvil activa en Google Play Store para la organización de horarios de clase, asignaturas y tareas académicas. Desarrollada en **Flutter** con arquitectura limpia, persistencia local en **SQLite**, notificaciones y recordatorios en segundo plano, soporte multilenguaje y widgets de pantalla de inicio.

**EN:** Live production mobile application available on Google Play Store for managing class schedules, subjects, and academic tasks. Built with **Flutter** featuring Clean Architecture, local **SQLite** persistence, background notifications and reminders, multi-language localization, and home screen widgets.

- Enlace directo / Direct link: [Google Play Store](https://play.google.com/store/apps/details?id=com.threedors.schedule_app)

---

### [Tablora: Diagramas de BD · Google Play Store](https://play.google.com/store/apps/details?id=com.threedors.table_database)

[![Google Play](https://img.shields.io/badge/Google_Play-Tablora:_Diagramas_de_BD-414141?style=flat-square&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.threedors.table_database)

**ES:** Aplicación móvil activa en Google Play Store para diseñar esquemas de bases de datos de forma visual desde el teléfono o la tablet. Desarrollada en **Flutter** con arquitectura limpia y **BLoC**, permite crear tablas, relaciones, índices y enumeraciones en un lienzo con zoom, **importar SQL o DBML** y **generar SQL para PostgreSQL, MySQL y SQLite**, exportar a DBML o PNG, y trabajar **100% offline** con persistencia local en **Hive**.

**EN:** Live production mobile application available on Google Play Store for visually designing database schemas on phones and tablets. Built with **Flutter** featuring Clean Architecture and **BLoC**, it lets you create tables, relationships, indexes and enums on a zoomable canvas, **import SQL or DBML**, **generate SQL for PostgreSQL, MySQL and SQLite**, export DBML or PNG, and work **fully offline** with local **Hive** persistence.

- Enlace directo / Direct link: [Google Play Store](https://play.google.com/store/apps/details?id=com.threedors.table_database)

---

## Tecnologías · Tech Stack

`Flutter` · `Dart` · `BLoC` · `NestJS` · `TypeScript` · `Angular 18` · `Angular Signals` · `Kotlin` · `Swift` · `SwiftUI` · `SwiftData` · `Hive` · `Node.js` · `TypeORM` · `SQLite` · `Swagger / OpenAPI` · `Clean Architecture` · `Jest` · `GitHub Actions` · `Git`

---

## Oportunidades · Opportunities

**ES:** Disponible para oportunidades laborales (Full-time / Remoto) y proyectos freelance de alto impacto en desarrollo móvil y fullstack.

**EN:** Open to full-time remote software engineering roles and high-impact freelance projects in mobile and fullstack engineering.

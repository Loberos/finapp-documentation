<h1 align="center">💰 FinApp</h1>

<p align="center">
  <strong>Sistema de gestión de cuentas corrientes y créditos para pequeños establecimientos comerciales</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white" alt="Angular"/>
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white" alt="Spring Boot"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"/>
</p>

<p align="center">
  <img src="https://i.postimg.cc/FznM017r/Whats-App-Image-2026-01-03-at-16-41-44.jpg" alt="FinApp Banner" width="100%"/>
</p>

---

## 📋 Tabla de Contenidos

- [Descripción del Proyecto](#-descripción-del-proyecto)
- [Objetivo](#-objetivo)
- [Características Principales](#-características-principales)
- [Tecnologías Utilizadas](#-tecnologías-utilizadas)
- [Arquitectura del Sistema](#-arquitectura-del-sistema)
- [Capturas de Pantalla](#-capturas-de-pantalla)
  - [Landing Page](#landing-page)
  - [Aplicación Web](#aplicación-web)
  - [API REST Documentation](#api-rest-documentation)

---

## 📖 Descripción del Proyecto

**FinApp** es una aplicación web diseñada para llevar el control de cuentas corrientes por créditos otorgados por pequeños establecimientos comerciales a clientes ubicados en su zona de influencia. La solución está orientada a negocios como bodegas, supermercados de barrio, panaderías, carnicerías, fruterías, bazares, licorerías, entre otros comercios que ofrecen crédito a sus vecinos y clientes frecuentes.

El sistema permite gestionar de forma eficiente los créditos, calcular intereses (nominales o efectivos), controlar límites de crédito, generar reportes de saldos y pagos, además de manejar tasas de interés moratorio para clientes con deudas vencidas.

El proyecto fue desarrollado como parte del curso de **Aplicaciones para Negocios Web** en la **Universidad Peruana de Ciencias Aplicadas (UPC)**, aplicando metodologías ágiles y buenas prácticas de desarrollo de software.

---

## 🎯 Objetivo

Crear una solución tecnológica que:

- **Digitalice el control de créditos** que tradicionalmente se llevaba en cuadernos o libretas de fiado.
- **Automatice el cálculo de intereses** tanto nominales como efectivos según la configuración de cada establecimiento.
- **Controle los límites de crédito** evitando que los clientes sobrepasen el monto autorizado.
- **Genere reportes detallados** de saldos, pagos y consumos en intervalos de tiempo configurables.
- **Gestione la morosidad** aplicando tasas de interés moratorio y restringiendo nuevos créditos a clientes con deudas vencidas.

---

## ✨ Características Principales

### Gestión de Clientes
- 👤 Alta de nuevos clientes con datos personales completos
- 💳 Configuración individual de cuentas y límites de crédito
- 📅 Fecha de pago mensual configurable por cliente
- 🚫 Bloqueo automático de crédito por morosidad

### Control de Créditos
- 🧮 Cálculo de intereses con tasas nominales o efectivas
- 📊 Dos modalidades de crédito:
  - **Crédito simple:** Compras a cancelar en la siguiente fecha de pago (valor futuro)
  - **Crédito en cuotas:** Compras a cancelar en varios meses (anualidad simple vencida con o sin plazos de gracia)
- ⚠️ Control automático de límites de crédito
- 📈 Tasa de interés moratorio configurable

### Reportes y Consultas
- 📋 Estado de cuenta con detalle de consumos y fechas
- 💵 Historial de pagos efectuados
- 📆 Consolidación de cuenta con intereses calculados a fecha de pago
- 🖨️ Generación de reportes en intervalos de tiempo personalizados

### Seguridad
- 🔐 Acceso obligatorio con usuario y contraseña
- 🛡️ Control de roles y permisos
- 🔒 Protección de datos sensibles

---

## 🛠 Tecnologías Utilizadas

### Frontend Web
| Tecnología | Descripción |
|------------|-------------|
| Angular | Framework principal para SPA |
| PrimeNG | Biblioteca de componentes UI |
| TypeScript | Lenguaje de programación tipado |
| Tailwind CSS | Framework de estilos utilitario |
| RxJS | Programación reactiva |

### Backend
| Tecnología | Descripción |
|------------|-------------|
| Spring Boot | Framework Java para APIs REST |
| Spring Security | Autenticación y autorización |
| Spring Data JPA | Persistencia de datos |
| MySQL | Base de datos relacional |
| Swagger/OpenAPI | Documentación de API |
| JWT | Tokens de autenticación |

### DevOps & Tools
| Tecnología | Descripción |
|------------|-------------|
| Git | Control de versiones |
| GitHub | Repositorio y colaboración |
| Postman | Testing de APIs |
| Figma | Diseño UI/UX |

---

## 🏗 Arquitectura del Sistema

### Software Architecture Context Diagram

[![Context Diagram](https://i.postimg.cc/WzDWL8bZ/image.png)](https://postimg.cc/Pvjz1mDf)

### Software Architecture Container Diagrams

[![Container Diagram](https://i.postimg.cc/W4XXdCDc/image.png)](https://postimg.cc/PLvmc6zS)

---

## 📸 Capturas de Pantalla

### Landing Page

La landing page presenta la plataforma de manera profesional, destacando los beneficios para comerciantes y las principales funcionalidades del sistema (https://finapp-aa4c6.web.app/).

[![Landing 1](https://i.postimg.cc/FznM017r/Whats-App-Image-2026-01-03-at-16-41-44.jpg)](https://postimg.cc/FznM017r)
[![Landing 2](https://i.postimg.cc/PJFg1NPt/Whats-App-Image-2026-01-03-at-16-41-44-(1).jpg)](https://postimg.cc/PJFg1NPt)
[![Landing 3](https://i.postimg.cc/NFP3RL5t/Whats-App-Image-2026-01-03-at-16-41-44-(2).jpg)](https://postimg.cc/NFP3RL5t)
[![Landing 4](https://i.postimg.cc/ZnDG60CS/Whats-App-Image-2026-01-03-at-16-41-44-(3).jpg)](https://postimg.cc/ZnDG60CS)
[![Landing 5](https://i.postimg.cc/hv3kVhfq/Whats-App-Image-2026-01-03-at-16-41-44-(4).jpg)](https://postimg.cc/hv3kVhfq)
[![Landing 6](https://i.postimg.cc/3Nbs2Wd5/Whats-App-Image-2026-01-03-at-16-41-44-(5).jpg)](https://postimg.cc/3Nbs2Wd5)
[![Landing 7](https://i.postimg.cc/SRtBcjj5/Whats-App-Image-2026-01-03-at-16-41-44-(6).jpg)](https://postimg.cc/SRtBcjj5)

---

### Aplicación Web

La aplicación web ofrece todas las funcionalidades para la gestión de clientes, créditos, pagos y reportes.

[![App 1](https://i.postimg.cc/9XGw1TpQ/Whats-App-Image-2026-01-03-at-16-36-40.jpg)](https://postimg.cc/9XGw1TpQ)
[![App 2](https://i.postimg.cc/59wQpv34/Whats-App-Image-2026-01-03-at-16-36-40-(1).jpg)](https://postimg.cc/59wQpv34)
[![App 3](https://i.postimg.cc/3rg09pBY/Whats-App-Image-2026-01-03-at-16-36-40-(2).jpg)](https://postimg.cc/3rg09pBY)
[![App 4](https://i.postimg.cc/Vsj04MRP/Whats-App-Image-2026-01-03-at-16-36-40-(3).jpg)](https://postimg.cc/Vsj04MRP)
[![App 5](https://i.postimg.cc/Kcn3QLNF/Whats-App-Image-2026-01-03-at-16-36-40-(4).jpg)](https://postimg.cc/Kcn3QLNF)
[![App 6](https://i.postimg.cc/G3kTzYjf/Whats-App-Image-2026-01-03-at-16-36-40-(5).jpg)](https://postimg.cc/G3kTzYjf)
[![App 7](https://i.postimg.cc/tRhnDPzf/Whats-App-Image-2026-01-03-at-16-36-40-(6).jpg)](https://postimg.cc/tRhnDPzf)
[![App 8](https://i.postimg.cc/9XGw1TBK/Whats-App-Image-2026-01-03-at-16-36-40-(7).jpg)](https://postimg.cc/9XGw1TBK)
[![App 9](https://i.postimg.cc/zDnHpWk4/Whats-App-Image-2026-01-03-at-16-36-40-(8).jpg)](https://postimg.cc/zDnHpWk4)
[![App 10](https://i.postimg.cc/7hMC6860/Whats-App-Image-2026-01-03-at-16-36-40-(9).jpg)](https://postimg.cc/7hMC6860)

---

### API REST Documentation

Documentación interactiva de la API implementada con Swagger/OpenAPI.

[![API 1](https://i.postimg.cc/yxqQK9g4/Whats-App-Image-2026-01-03-at-16-47-54.jpg)](https://postimg.cc/yxqQK9g4)
[![API 2](https://i.postimg.cc/5yc7JvYc/Whats-App-Image-2026-01-03-at-16-47-54-(1).jpg)](https://postimg.cc/5yc7JvYc)
[![API 3](https://i.postimg.cc/d3MHFdkc/Whats-App-Image-2026-01-03-at-16-47-54-(2).jpg)](https://postimg.cc/d3MHFdkc)
[![API 4](https://i.postimg.cc/MHkPwRcg/Whats-App-Image-2026-01-03-at-16-47-54-(3).jpg)](https://postimg.cc/MHkPwRcg)
[![API 5](https://i.postimg.cc/zvmtNWLM/Whats-App-Image-2026-01-03-at-16-47-54-(4).jpg)](https://postimg.cc/zvmtNWLM)

---

## 📄 Licencia

Este proyecto fue desarrollado con fines académicos para la **Universidad Peruana de Ciencias Aplicadas (UPC)**.

---

<p align="center">
  <strong>Desarrollado con ❤️ para digitalizar el comercio local</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/UPC-Universidad%20Peruana%20de%20Ciencias%20Aplicadas-red?style=for-the-badge" alt="UPC"/>
</p>
# GestionCitas - Sistema de Gestión de Citas Médicas

**GestionCitas** es una aplicación integral de gestión de citas médicas que permite a pacientes agendar consultas, a doctores gestionar su disponibilidad y a administradores supervisar el sistema completo. La aplicación está construida con una arquitectura moderna de dos capas: un backend robusto y un frontend intuitivo.

## 📋 Estructura del Proyecto

El proyecto está organizado en dos carpetas principales:

### 🔧 Backend - `gestioncitas/`

Backend desarrollado con **Spring Boot** que proporciona una API REST completa para la gestión de citas, usuarios, doctores, especialidades y auditoría del sistema.

**Documentación disponible:**
- [`API_DOCUMENTATION.md`](./gestioncitas/API_DOCUMENTATION.md) - Especificación completa de los endpoints de la API
- [`CREATE_USERS.md`](./gestioncitas/CREATE_USERS.md) - Guía para crear y gestionar usuarios
- [`DOCUMENTACION_BK.md`](./gestioncitas/DOCUMENTACION_BK.md) - Documentación general del backend
- [`HELP.md`](./gestioncitas/HELP.md) - Guía de ayuda y troubleshooting
- [`SPECIALITIES_ID.md`](./gestioncitas/SPECIALITIES_ID.md) - Referencias de IDs de especialidades médicas

**Tecnología:** Java, Spring Boot, Maven

---

### 🎨 Frontend - `GestionCitas_Frontend/`

Frontend desarrollado con **React + TypeScript** que proporciona una interfaz de usuario moderna y responsiva para interactuar con la API del backend.

**Documentación disponible:**
- [`README.md`](./GestionCitas_Frontend/README.md) - Guía de instalación y ejecución del frontend
- [`CONTRIBUTING.md`](./GestionCitas_Frontend/CONTRIBUTING.md) - Guía de contribución y estándares de código

**Tecnología:** TypeScript, React, Vite, TailwindCSS

---

## 🚀 Inicio Rápido

### Requisitos Previos
- Java 11+ (para el backend)
- Node.js 16+ (para el frontend)
- Maven (para compilar el backend)
- npm o yarn (para el frontend)

### Ejecutar el Backend
```bash
cd gestioncitas
./mvnw spring-boot:run
```

### Ejecutar el Frontend
```bash
cd GestionCitas_Frontend
npm install
npm run dev
```

## 📚 Documentación Detallada

Para obtener información más detallada sobre cada componente del sistema, consulta:
- **Backend:** [`gestioncitas/DOCUMENTACION_BK.md`](./gestioncitas/DOCUMENTACION_BK.md)
- **Frontend:** [`GestionCitas_Frontend/README.md`](./GestionCitas_Frontend/README.md)
- **API:** [`gestioncitas/API_DOCUMENTATION.md`](./gestioncitas/API_DOCUMENTATION.md)

## 🔐 Características Principales

- ✅ Autenticación y autorización basada en roles (Paciente, Doctor, Administrador)
- ✅ Gestión de citas médicas
- ✅ Programación de disponibilidad de doctores
- ✅ Gestión de especialidades médicas
- ✅ Registros médicos electrónicos
- ✅ Sistema de auditoría y seguridad
- ✅ Notificaciones del sistema


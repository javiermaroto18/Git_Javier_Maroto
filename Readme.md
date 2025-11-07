# 🛡️ Gate Manager -- Sistema de Control de Acceso RFID

##  Introducción

Gate Manager es la interfaz web del Sistema de Control de Acceso RFID a
Salas del CPD. Su objetivo es proporcionar una plataforma moderna, clara
y centralizada para la gestión de salas, usuarios, accesos y eventos de
seguridad dentro del Centro de Procesamiento de Datos.\
Este documento README describe la arquitectura, componentes clave,
funcionalidades principales y estructura general del sistema. Las
capturas de pantalla y explicaciones detalladas serán añadidas
posteriormente.

------------------------------------------------------------------------

## 🚀 Características Principales

-   ✅ Dashboard en tiempo real
-   ✅ Gestión de usuarios (permisos, tarjetas, estados)
-   ✅ Administración de salas (ocupación, capacidad, bloqueo)
-   ✅ Historial completo de accesos
-   ✅ Alertas y eventos en tiempo real
-   ✅ Diseño responsive y adaptable

------------------------------------------------------------------------

## 🧩 Arquitectura del Sistema

El ecosistema completo está compuesto por:

-   **Frontend (React)** para visualización general
-   **Panel de administración** para configuraciones avanzadas
-   **Backend (Laravel + API REST)** para lógica de negocio
-   **Base de datos MySQL**

------------------------------------------------------------------------

## 🛠️ Tecnologías Utilizadas

### Frontend

-   React
-   TailwindCSS

### Backend

-   Laravel\
-   MySQL/MariaDB

### Hardware

-   Lectores RFID MFRC522/PN532\
-   Arduino UNO / Nano\
-   Raspberry Pi

------------------------------------------------------------------------

## 🧱 Módulos Principales

### 🔹 Dashboard

El panel principal muestra: - Estado de salas
- Ocupación actual
- Alertas activas
- Gráficos de uso histórico
- Eventos recientes

*(Aquí añadirás las capturas correspondientes)*

------------------------------------------------------------------------

### 🔹 Gestión de Usuarios

-   CRUD completo\
-   Estados (activo/inactivo)\
-   Tarjetas RFID asociadas\
-   Permisos por sala y franjas horarias\
-   Filtros avanzados

------------------------------------------------------------------------

### 🔹 Gestión de Salas

-   Estado en tiempo real\
-   Capacidad y últimos accesos\
-   Usuarios dentro\
-   Bloqueo/desbloqueo\
-   Filtro por estado

------------------------------------------------------------------------

### 🔹 Historial y Registro

-   Búsqueda por usuario, sala o fecha\
-   Registro de accesos, salidas y eventos\
-   Exportación CSV/JSON

------------------------------------------------------------------------

### 🔹 Alertas y Notificaciones

Tipos de alertas: - Acceso denegado\
- Tarjeta inválida\
- Sala bloqueada\
- Puerta abierta demasiado tiempo\
- Fallos de sensores

Las alertas pueden marcarse como atendidas.

------------------------------------------------------------------------

## 🎨 Diseño UI/UX

El diseño está basado en: - Minimalismo\
- Jerarquía clara de información\
- Colores asociados a estados\
- Componentes limpios y consistentes\
- Diseño completamente responsive

*(Aquí añadirás capturas del mockup GATE MANAGER)*

------------------------------------------------------------------------

## 📦 Instalación

``` bash
# Clonar repositorio
git clone https://github.com/usuario/gate-manager.git

# Frontend
cd frontend
npm install
npm run dev

# Backend
cd backend
composer install
php artisan migrate --seed
php artisan serve
```

------------------------------------------------------------------------

## 🧪 Pruebas

-   Unitarias (PHPUnit, Jest)\
-   Integración API\
-   Validación hardware (RFID/Arduino)\
-   Stress test de accesos

------------------------------------------------------------------------

## 📚 Documentación Relacionada

-   Documento de Requisitos del Usuario (DRU)\
-   Mockup oficial Gate Manager

------------------------------------------------------------------------

## 👥 Autores

Proyecto desarrollado para el Centro Profesional U-Tad.

------------------------------------------------------------------------

## ✅ Estado del Proyecto

🟢 Versión entregable (documentación + diseño UI)\
🔄 Pendiente de integración hardware/servidor

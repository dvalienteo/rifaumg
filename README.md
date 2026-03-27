# rifaumg
control de tickets para rifa umg en industrial
# 🎟️ Sistema de Control de Tickets - Aniversario UMG

Sistema web integral para la gestión, venta y monitoreo de tickets de rifa para el Aniversario 2026 de la **Universidad Mariano Gálvez, Sede Puerto Barrios**.

## 🚀 Características Principal
- **Seguridad por Roles:** Acceso controlado para Administradores, Vendedores y Consultores.
- **Buscador Inteligente:** Localización rápida de estudiantes y catedráticos en el listado oficial.
- **Registro en Tiempo Real:** Conexión directa con Google Sheets para almacenamiento persistente.
- **Gestión de Datos:** Permite completar ciclo y sección de alumnos que no cuenten con registro previo.
- **Panel de Estadísticas:** Visualización de recaudación total (Exclusivo para Admins).

## 🛠️ Tecnologías Utilizadas
- **Frontend:** HTML5, CSS3 (Flexbox/Grid), JavaScript (Vanilla).
- **Backend:** Google Apps Script (GAS).
- **Base de Datos:** Google Sheets.
- **Hosting:** GitHub Pages.

## 📊 Estructura de la Base de Datos (Google Sheets)
El sistema requiere una hoja de cálculo con las siguientes pestañas:
1. **Listado2026:** `Nombre Completo` | `Ciclo` | `Sección`.
2. **Listado_TICKETS:** `Nombre` | `Ciclo` | `Ticket` | `Monto` | `Vendedor` | `Fecha` | `Sección`.
3. **usuarios:** `Usuario` | `Nombre` | `Password` | `Rol` (admin, vendedor, consultor).

## 📋 Instrucciones de Instalación
1. Copia el código de `Código.gs` en un nuevo proyecto de **Google Apps Script**.
2. Implementa como **Aplicación Web** (Acceso: Cualquier persona).
3. Copia la URL generada y pégala en la variable `API_URL` del archivo `index.html`.
4. Sube el archivo `index.html` a este repositorio y activa **GitHub Pages**.

---
### Créditos
**Institución:** Universidad Mariano Gálvez · Puerto Barrios, Izabal  
**Autoría y Dirección:** M.A. Inga. Delmy Valiente  
**Año:** 2026

# 🏟️ Cancha.net

**Cancha.net** es un sistema integral de gestión para complejos deportivos de fútbol 5 y 6. Su objetivo principal es facilitar el manejo de stock, turnos, ventas y control de clientes de forma eficiente y adaptable a múltiples localidades.

---

## 🚀 Funcionalidades principales

### ✅ Gestión de turnos
- Registro de jugadores por turno.
- Control de asistencia real.
- Identificación de turnos fijos para conteo de fidelidad.

### ✅ Ventas individualizadas
- Registro de ventas por jugador.
- Asociación de cada venta con el empleado que la aprobó.
- Soporte para múltiples métodos de pago.

### ✅ Control de stock por sede
- Gestión de stock individual por cancha y producto.
- Visibilidad clara del inventario en cada localidad.
- Base para automatizar pedidos por baja de stock.

### ✅ Cierre de caja diario
- Informes de cierre por día, cancha y usuario.
- Registro de ingresos y observaciones asociadas.
- Facilitación de auditorías internas.

### ✅ Recompensas por fidelidad
- Conteo automático de turnos fijos cumplidos.
- Recompensa configurable (ej. choripaneada) al cumplir 15 partidos.
- Registro de entregas de recompensa.

### ✅ Anotes y cuentas pendientes
- Gestión de deudas por inasistencia o problemas de pago.
- Seguimiento por cliente, con estado y motivo detallado.
- Historial de resolución de anotes.

---

## 🗄️ Base de datos

El sistema está respaldado por una base de datos relacional optimizada, con tablas dedicadas para:

- `turno`, `jugador`, `usuario`, `persona`, `venta`
- `producto`, `stock`, `metodo_pago`, `rol`
- `caja`, `anote_cliente`, `turno_fijo_cliente`

La estructura favorece la trazabilidad de acciones, la segmentación por cancha y la integridad de los datos.

---

## 📍 Localidades múltiples

Diseñado para soportar **más de una sede/cancha**, permitiendo:
- Gestión separada de stock, caja y usuarios.
- Reportes filtrados por locación.

---

## 🛠️ Tecnología

- Base de datos: MySQL .
- Backend:
- **Lenguaje:** C#  
- **Framework:** .NET 6+  
- **ORM:** Entity Framework Core  
- Frontend: Vue.js 3  

---

## 📌 Estado del proyecto

✅ Estructura de base de datos completa  
✅ Listo para integración con frontend/backend  

---

## 📫 Contacto

Para más información o sugerencias, escribime a:  
stiegervalentin123@gmail.com



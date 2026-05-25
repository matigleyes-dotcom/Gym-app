# GymApp — Demo

Aplicación de gestión de gimnasio con panel cliente y panel administrador.
Funciona como **PWA** (se instala en el iPhone como una app nativa).

## Cómo probarla en la PC

Doble click en `index.html` y se abre en el navegador. Listo.

## Accesos de demo

**Administrador**
- Contraseña: `admin123`

**Clientes** (entrá con DNI)
- Juan Pérez → `30111222`
- María González → `32555444`
- Carlos Ruiz → `28999888`
- Lucía Fernández → `35222111`

## Funcionalidades

### Panel cliente
- Resumen del día (entrenamiento de hoy + estado de pago)
- Ver rutina completa por día con series, reps y descansos
- Historial de pagos y cuota pendiente
- Perfil con datos personales

### Panel administrador
- Dashboard con clientes activos, ingresos del mes y morosos
- ABM de clientes (alta, baja, modificación, búsqueda)
- Detalle de cliente con sus pagos y rutina asignada
- ABM de rutinas (días, ejercicios, series, reps)
- Registro de pagos con filtros
- Ajustes del gimnasio (nombre, dirección, cuota, contraseña admin)

## Datos

Los datos se guardan en `localStorage` del navegador (sólo en ese dispositivo).
Desde el panel admin → Ajustes podés restablecer la demo.

Para vender la app a varios gimnasios habrá que migrar a una base de datos en
la nube (Supabase / Firebase). El código está estructurado para que ese cambio
sea acotado.

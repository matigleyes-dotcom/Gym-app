# Tiempo Vital — App del gimnasio

Aplicación PWA para gestión de gimnasio. Inspirada en Qivox, adaptada con la identidad
de **Tiempo Vital** (paleta verde / gris / negro).

## Cómo probarla en la PC

Doble click en `index.html` y se abre en el navegador.

## Accesos de demo

**Administrador**: contraseña `admin123`

**Clientes** (login con DNI):
- Víctor Leyes → `30111222`
- María González → `32555444`
- Carlos Ruiz → `28999888`
- Lucía Fernández → `35222111`

## Pantallas del cliente

- **Hoy tienes**: saludo, entrenamiento del día con progreso, composición corporal, estado de cuota, invitar amigo.
- **Mi centro**: tu entrenamiento, reserva de actividades, gymder, contacto.
- **Mi perfil**: avatar grande con stats (peso, grasa, músculo), registrar peso, histórico, seguimiento.
- **Más** (bottom sheet): QR, Mi actividad (calendario), Mis entrenamientos, Cartera, Notificaciones, gymder.

## Pantallas del admin

- **Inicio**: dashboard con clientes activos, ingresos del mes, morosos, últimos pagos.
- **Clientes**: ABM con búsqueda, detalle con pagos y rutina, asignar rutina.
- **Rutinas**: catálogo de rutinas con sesiones y progreso.
- **Pagos**: registrar pago, filtrar, ver historial.
- **Ajustes**: configurar gym, restablecer demo, cerrar sesión.

## Cómo subir cambios a GitHub Pages

1. Andá al repo en github.com/matigleyes-dotcom/Gym-app
2. Tocá `Add file` → `Upload files`
3. Arrastrá los archivos `index.html`, `manifest.json` y `README.md` (sobreescriben los existentes)
4. Commit changes
5. Esperá 1-2 minutos y refrescá la URL del sitio en el iPhone para ver los cambios

## Stack

- HTML + React (CDN) + Tailwind (CDN) + Babel standalone
- Persistencia en `localStorage` del navegador
- PWA: instalable en iOS desde Safari con "Añadir a pantalla de inicio"

Sin build, sin dependencias, sin servidor.

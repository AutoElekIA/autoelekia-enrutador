# AutoElekIA Enrutador

**PWA de enrutamiento y logística.**

## 1. Propósito
Módulo de gestión de rutas, optimización de trayectos y seguimiento logístico para repartidores o transporte de carga ligera.

Forma parte del ecosistema **AutoElekIA** y **no es autónomo**: depende del `autoelekia-core`.

## 2. Estado del Vertical
- **Fase:** Conceptualización
- **Frontend:** PWA (JavaScript) base.
- **Backend:** Consume el Core vía API REST.

## 3. Dependencia del Core
- `Auth`: Login.
- `Usuarios` / `Roles`: Repartidores y despachadores.
- `Access Control`: Si aplica validación de unidades.
- `Storage`: Evidencias fotográficas de entregas.

## 4. Próximos Pasos
1. Definir alcance exacto (última milla, carga, o personal).
2. Modelado Prisma en el Core: `Ruta`, `Parada`, `AsignacionVehiculo`.
3. Integración con mapas (Leaflet/Google Maps).
4. App móvil para chofer/repartidor.

---
**Autoría:** Carlos Fernando Aleman Garcia + Equipo AutoElekIA

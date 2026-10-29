# Dashboard Operativo · Talento Impulsa Consulting

Tablero interno desde el que se gestiona Talento Impulsa: proyectos, clientes, potenciales, pendientes y bitácora en un solo lugar.

**Estado:** Producción · uso interno (acceso restringido con cuenta de Google)
**App:** [msoledadvila-afk.github.io/talento-impulsa-dashboard](https://msoledadvila-afk.github.io/talento-impulsa-dashboard/)

## Qué hace

- Inicio con el resumen del día
- Proyectos, clientes y recursos
- Potenciales y pipeline de consultas, con etapas y prioridad
- Pendientes por área y proyecto, y bitácora de trabajo
- Marketing, reuniones y brainstorming de ideas
- Acceso directo al [Hub PCA™](https://msoledadvila-afk.github.io/hub-pca/) y a Presupuestos PCA™

## Stack

| Capa | Tecnología |
| --- | --- |
| Frontend | HTML + JS vanilla, archivo único |
| Íconos e interacción | Lucide, SortableJS |
| Datos | Firebase Firestore (Compat SDK) |
| Acceso | Firebase Auth con Google, limitado a cuentas autorizadas |
| Hosting | GitHub Pages |

## Seguridad

La `apiKey` de Firebase que aparece en el código es pública por diseño. La protección está en las Reglas de Firestore, que solo permiten cuentas autorizadas con email verificado, y en los dominios autorizados del proyecto. Las capturas de este tablero no se publican porque muestran datos reales.

## Licencia

© 2026 Talento Impulsa Consulting. Todos los derechos reservados. Código visible solo como referencia; no se autoriza su reutilización comercial.

---

**Talento Impulsa Consulting** · [talentoimpulsa.com.ar](https://talentoimpulsa.com.ar)
hola@talentoimpulsa.com.ar · presupuestos@talentoimpulsa.com.ar

# EcoSystem Connect - Proyecto Final

## Arquitectura de Software: Patrón N-Capas
Este proyecto implementa una arquitectura N-Capas (N-Tier Architecture) para garantizar la separación de responsabilidades, mantenibilidad y escalabilidad del sistema.

### Estructura del Proyecto:
* **EcoSystem.API (Presentación):** Capa exterior encargada de exponer los endpoints RESTful mediante controladores C# y gestionar las peticiones HTTP/respuestas JSON.
* **EcoSystem.Business (Lógica de Negocio):** El cerebro del sistema. Orquesta los flujos de trabajo y valida las reglas de negocio de forma agnóstica a la persistencia.
* **EcoSystem.Data (Acceso a Datos):** Cimientos del sistema encargados de la persistencia física e interacción con la base de datos mediante Entity Framework Core (Code-First).

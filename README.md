# Proyecto de validación del proyecto de grado

## Primera Fase: Diseño de la Infraestructura

- **Selección de estrategia de Branching.**

Escogimos GitHub-Flow con TBD (Trunk Based Development). Debido a la simplicidad del flujo de trabajo, esta estrategia de branching permite la entrega y la integración continua para productos de SaaS como una aplicación Web. Se va a implementar los siguientes branches: main, test y production. En cada una de estas ramas se piensa trabajar en funcionalidades específicas e independientes para no generar incovenientes en cada merge.

- **Identificación de los elementos actuales**

Los elementos actuales le han permitido a la empresa poder hostear una aplicación web que ha sido suficiente para unos requerimientos de disponibilidad y escalabilidad básicos con poco flujo de clientes.

**Diagrama de la infraestructura actual (on-premise).**

![Diagrama Físico Actual - AIK](https://user-images.githubusercontent.com/47835629/170802440-2731e30b-55a3-41c8-a34a-1768888ff6df.png)

**Diagrama de la arquitectura del servicio actual.**

![Application description drawio](https://user-images.githubusercontent.com/47835629/170802445-d7d67257-a857-447a-894c-4a3fa06ef212.png)

- Propuesta de solución.

Teniendo en cuenta los nuevos requerimientos del problema en tanto a disponibilidad y escalabilidad, se propone re-estructurar la infraestructura actual para un despliegue en la nube. Después de un proceso de diseño se llegó al siguiente modelo de infraestructura: 

![Diagrama Propuesto en AWS - AIK](https://user-images.githubusercontent.com/47835629/170802453-a9ce3432-3a69-40b8-a03e-0e34d9bedd14.png)

## Segunda Fase: Codificación

...
  

## Diagrama de Flujo  - Procedimiento Astillero Digital

Este flujo modela las bifurcaciones, interacciones y rutas que sigue un proyecto en Astillero Digital según su naturaleza (tipo de navío) y entorno (zona de navegación).

---

### 🌐 NODO 1. Ingreso del Proyecto

- **Entrada:** Solicitud del cliente, idea o necesidad interna.
- **Salida:** Activación del Procedimiento General.
- **Flujo hacia:** Nodo 2.

---

### 🧭 NODO 2. Análisis Inicial de Requisitos

- **Entradas:** Idea inicial, visión del cliente, referencias.
- **Salidas:** Perfil del usuario, alcance, objetivos, riesgos, Carta Náutica preliminar.
- **Flujo hacia:** Nodo 3.

---

### ⚓ NODO 3. Clasificación: Zona + Navío

- **Entradas:** Carta Náutica, perfil de usuario, objetivos.
- **Decisión bifurcada:**
  - ¿Navegación ligera? → Lagunas + Barco de Papel
  - ¿Visual y estética? → Islas Flotantes o Mar Abierto + Velero Interactivo / Catamarán
  - ¿Funcionalidad técnica o lógica de negocio? → Inmersiones o Mar Abierto + Submarino Modular
  - ¿Procesamiento o análisis de datos? → Inmersiones + Submarino de Datos
  - ¿Automatización pura? → Ríos + Dron Autónomo
  - ¿Escalabilidad y producción robusta? → Mar Abierto + Trasatlántico
- **Salida:** Fijación de Ruta.
- **Flujo hacia:** Nodo 4.

---

### 📐 NODO 4. Bocetado Funcional y Técnico

- **Entradas:** Fijación de Ruta.
- **Salidas:** Wireframes, diagramas de flujo, arquitectura técnica, elección de stack.
- **Flujos hacia:** Nodo 5.

---

### 🔧 NODO 5. Planeación Modular e Infraestructura

- **Entradas:** Boceto técnico, estructura funcional.
- **Salidas:** Definición de módulos, configuración de entornos, infraestructura de despliegue.
- **Flujos hacia:** Nodo 6.

---

### 🔄 NODO 6. Validación con Cliente (Bitácora Abierta)

- **Entradas:** Módulos planificados, arquitectura, prototipos.
- **Salidas:** Ajustes aprobados, bitácora abierta, aceptación de criterios.
- **Flujos hacia:** Nodo 7 o retrocede al Nodo 4 si hay cambios mayores.

---

### 🛠️ NODO 7. Setup + Desarrollo Modular

- **Entradas:** Aprobación cliente, entorno de trabajo, módulos definidos.
- **Salidas:** Funcionalidades implementadas, integración parcial o total.
- **Flujo hacia:** Nodo 8.

---

### ✅ NODO 8. QA Manual + Checklist

- **Entradas:** Producto integrado, criterios de aceptación.
- **Salidas:** Reporte QA, incidencias, validación final.
- **Flujos hacia:** Nodo 9.

---

### 📚 NODO 9. Documentación y Bitácora Técnica

- **Entradas:** Producto final validado, componentes implementados.
- **Salidas:** Manual técnico, usuario, bitácora de viaje.
- **Bitácora se alimenta:** De nodos 2, 3, 4, 5, 6, 8.
- **Flujos hacia:** Nodo 10.

---

### 🚢 NODO 10. Despliegue / Demo / Entrega

- **Entradas:** Documentación completa, validación QA.
- **Salidas:** Producto entregado, entorno productivo activo, cliente notificado.
- **Flujo hacia:** Nodo 11.

---

### 📊 NODO 11. Retroalimentación + Mejora

- **Entradas:** Feedback del cliente, métricas de uso, logs.
- **Salidas:** Plan de mejoras, backlog técnico, iteración planificada.
- **Bifurcación:**
  - ¿Iteración menor? → Nodo 7.
  - ¿Cambio mayor o pivoteo? → Nodo 2.
  - ¿Fin del viaje? → Cierre de Bitácora.

---

### 📝 NODO ESPECIAL: Indicadores y Riesgos (Anexo)

- Se alimenta desde los nodos 2, 4, 6, 8 y 11.
- **Salida:** Base para SGC.
- **Nota:** Procedimiento específico a desarrollar.

---

> Cada bifurcación se acompaña visualmente de iconografía náutica (brújula, olas, profundidades), y la Bitácora se abre en la Validación con el cliente y se cierra tras la retroalimentación final. El flujo es cíclico, preparado para abordar nuevas olas con cada nueva iteración.


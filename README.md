# HMI AS/RS - Sistema de Control de Almacenamiento Automatizado 🤖📦

Este repositorio contiene el subsistema de Interfaz Hombre-Máquina (HMI) para el control y supervisión de un sistema **AS/RS (Automated Storage and Retrieval System)**. Desarrollado con **React.js**, este frontend permite la gestión de inventario, monitoreo de telemetría y control del transelevador en tiempo real.

## 1. Sistema de Diseño Visual

Se ha implementado un sistema de diseño basado en principios de **usabilidad industrial**, priorizando la legibilidad, la reducción de la fatiga visual y la respuesta rápida del operador.

### 🎨 Identidad Visual
- **Paleta de Colores Académica/Industrial:**
  - `Primary (#0055CC)`: Acciones principales y navegación.
  - `Success (#388E3C)`: Estado operativo normal y conexiones activas.
  - `Warning (#FBC02D)`: Alertas de proximidad o estados de transición.
  - `Danger (#D32F2F)`: Paros de emergencia, errores críticos y desconexión.
  - `Background (#F4F7FA)`: Fondo neutro para mejorar el contraste de datos.



### 🔡 Tipografía
- **Fuente:** `Inter` / `Roboto` (Sans-serif).
- **Jerarquía:** - Títulos: 24px (Bold) para encabezados de sección.
  - Cuerpo: 16px para datos de sensores y formularios.
  - Labels: 12px (Uppercase) para etiquetas de telemetría.

  <img width="712" height="338" alt="image" src="https://github.com/user-attachments/assets/5e92c42a-dbde-47b4-b5f7-b5eca89a6d4b" />


### 🍱 Componentes Core (UI Library)
- **Botones:** Tamaño mínimo de 44x44px para facilitar la interacción táctil en pantallas industriales.
- **Indicadores de Estado:** Badges dinámicos que cambian de color según el estado del robot.
- **Tarjetas de Inventario:** Contenedores modulares para representar las celdas del almacén.

---

## 2. Arquitectura de la Interfaz

La HMI se divide en los siguientes módulos funcionales:

1. **Dashboard:** Vista general con KPIs (ocupación del almacén, estado del transelevador).
2. **Control de Inventario:** Grilla interactiva que representa la estructura física del AS/RS.
3. **Operaciones:** Formularios de entrada (Reception) y salida (Dispatch) de mercancía.
4. **Diagnóstico:** Pantalla de telemetría con gráficos en tiempo real (WebSockets).

---

## 3. Integración Técnica (Backend & WebSockets)

La interfaz está diseñada para consumir datos en tiempo real mediante el protocolo **WebSocket (ws://)**, permitiendo:
- Visualización de la posición robot sin recargar la página.
- Actualización instantánea del stock al realizar movimientos.
- Notificaciones de alarma inmediatas (Push notifications en UI).

### Pruebas de Conexión


---

## 4. Instalación y Ejecución 🚀

1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/Arrieta442/InterfazDise-o.git](https://github.com/Arrieta442/InterfazDise-o.git)

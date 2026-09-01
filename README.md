Infraestructura Financiera — Ollas de Barro y Canastas Tejidas  
**Producto:** Plataforma de repositorio digital y gestión financiera para artesanías tradicionales de la Mixteca  
**Metodología:** eduScrum  
**Integrantes:** Edgar Axel Sandoval Hernández y Adriana Hernández Martínez  

---

### 1. Product Goal
Desarrollar un repositorio digital seguro e infraestructura financiera simplificada que permita a los talleres de ollas de barro y canastas tejidas gestionar su inventario de piezas, registrar transacciones comerciales y facilitar flujos de pago directos y transparentes, adaptados a las condiciones reales de conectividad de la región Mixteca.

---

### 2. Product Backlog

| Prioridad | ID | Historia de Usuario | Resultado esperado | Dependencia | Estimación |
| :---: | :--- | :--- | :--- | :---: | :---: |
| 1 | **HU-01** | Como artesano productor de ollas o canastas, quiero registrarme en el sistema financiero con mi número de celular y un código de validación, para acceder a mi panel de control de ventas sin claves complejas. | Registro y autenticación móvil | Servicio SMS | 5 pts |
| 2 | **HU-02** | Como artesano, quiero dar de alta en el repositorio mis piezas de barro y canastas indicando costos de producción, materiales (barro rojo/negro, ixtle, carrizo), precios de venta y stock disponible, para mantener inventarios precisos. | Repositorio e inventario de piezas artesanales | HU-01 | 8 pts |
| 3 | **HU-03** | Como artesano, quiero registrar cada pedido especial de ollas o canastas y su respectivo anticipo económico, para generar un comprobante financiero transparente frente al cliente. | Infraestructura de control de anticipos | HU-02 | 8 pts |
| 4 | **HU-04** | Como comprador, quiero consultar el repositorio digital mediante un código QR para ver el precio oficial de la olla o canasta y los detalles financieros de la transacción. | Consulta pública del repositorio | HU-03 | 5 pts |
| 5 | **HU-05** | Como artesano, quiero registrar mis datos de cobro o CLABE de forma cifrada en la plataforma, para recibir retribuciones financieras directas de mis ollas y canastas sin comisiones de intermediarios. | Canal de pago e infraestructura financiera | HU-01 | 5 pts |
| 6 | **HU-01b** | Recuperación de credenciales de acceso ante pérdida o cambio de dispositivo móvil. | Recuperación de cuenta | HU-01 | Por definir |
| 7 | **HU-04b** | Soporte para descripciones monetarias y de costos en lengua originaria de la región para productores locales. | Soporte lingüístico local | HU-04 | Por definir |
| 8 | **HU-06** | Módulo de capacitación y soporte para el registro financiero y control de costos básico en talleres de ollas y canastas. | Accesibilidad financiera y educación | Por definir | Por definir |

---

### 3. Criterios de aceptación

* **HU-01 – Autenticación en la infraestructura**
  * Validación mediante número telefónico móvil.
  * Acceso seguro al panel financiero del artesano de ollas y canastas.
  * Mecanismo básico de recuperación de cuenta.

* **HU-02 – Repositorio de productos (Ollas de Barro y Canastas)**
  * Registro estructurado de fichas con costos, tipo de material (barro, carrizo, ixtle) y precios.
  * Carga y almacenamiento optimizado de fotografías en el repositorio.
  * Actualización en tiempo real de estatus (Disponible / Vendido / En producción).

* **HU-03 – Control de anticipos y transacciones**
  * Registro de órdenes de compra con monto total y anticipo recibido para piezas artesanales.
  * Generación de identificador único de transacción.
  * Cálculo automático de saldos pendientes de pago.

* **HU-04 – Consulta pública en repositorio**
  * Acceso rápido mediante escaneo de código QR de la pieza.
  * Visualización de precios oficiales y características de la olla o canasta.
  * Interfaz ligera optimizada para conexiones móviles intermitentes.

* **HU-05 – Infraestructura de pago y retribución directa**
  * Encriptación de datos sensibles de cuentas o métodos de pago.
  * Botones de redirección y confirmación clara para el envío de fondos directos al artesano.
  * Exclusión de comisiones ocultas o retenciones de la plataforma.

---

### 4. Tablero eduScrum

#### Estado actual del trabajo
| BACKLOG | POR HACER | EN PROCESO | EN REVISIÓN / PRUEBAS | TERMINADO |
| :--- | :--- | :--- | :--- | :--- |
| HU-01b - Recuperación de cuenta | HU-01 - Autenticación | HU-02 - Repositorio de productos (Ollas y Canastas) | *(Sin elementos)* | Acta de criterios de aceptación validada |
| HU-04b - Soporte bilingüe | HU-03 - Control de anticipos | | | |
| HU-06 - Educación financiera | HU-04 - Consulta en repositorio | | | |
| | HU-05 - Infraestructura de pagos | | | |

---

### 5. Flujo del tablero

```text
┌──────────────┐
│   BACKLOG    │
└──────┬───────┘
       ↓
┌──────────────┐
│  POR HACER   │
└──────┬───────┘
       ↓
┌──────────────┐
│ EN PROCESO   │
└──────┬───────┘
       ↓
┌─────────────────────┐
│ EN REVISIÓN/PRUEBAS │
└──────────┬──────────┘
           ↓
┌─────────────────────┐
│      TERMINADO      │
└─────────────────────┘

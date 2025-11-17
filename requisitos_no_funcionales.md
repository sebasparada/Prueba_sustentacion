# REQUISITOS NO FUNCIONALES


## RNF-001: RENDIMIENTO Y CAPACIDAD

### RNF-001.1: Tiempo de Respuesta de Interfaz

### **Descripción**

El sistema debe responder de manera rápida para que los usuarios puedan usarlo sin demoras.

### **Métrica Específica**

* Operaciones estándar (navegación, búsqueda): ≤ **3 segundos**
* Operaciones simples (login, abrir páginas): ≤ **2 segundos**

### **Medición**

Tiempo desde que el usuario hace clic hasta que el sistema muestra la información completa.

### **Condiciones de Prueba**

* Conexión 4G promedio
* Horario de uso común (tardes)
* Base de datos con aproximadamente **5.000 registros**

### **Criterios de Aceptación**

* 95% de las operaciones cumplen el tiempo esperado
* Solo 1% puede tardar más del doble
* Mostrar indicador de carga si tarda más de 2 segundos

### **Prioridad**

**MUST (Crítico)**

### **Fuente**

Requerimiento operativo

---

## RNF-002: SEGURIDAD DE DATOS

### RNF-002.1: Protección de Información y Acceso

### **Descripción**

La información de huéspedes y documentos internos debe estar protegida y solo accesible por personal autorizado.

### **Condiciones de Seguridad**

* Datos protegidos al guardarse y al transmitirse
* Permisos según rol de usuario
* Contraseña segura y doble verificación

### **Criterios de Aceptación**

* Nadie accede sin autorización
* La privacidad de la información está garantizada

### **Prioridad**

**MUST (Crítico)**

### **Fuente**

Área de seguridad

---

## RNF-003: DISPONIBILIDAD Y ACCESIBILIDAD

### RNF-003.1: Acceso Continuo 24/7

### **Descripción**

El sistema debe estar disponible todo el tiempo y ser accesible desde dispositivos móviles y computadores.

### **Condiciones de Prueba**

* Disponibilidad mínima: **99.5%**
* Funcionamiento en móviles, tablets y computadoras

### **Criterios de Aceptación**

* Acceso estable sin interrupciones prolongadas
* Todas las funciones disponibles en los dispositivos compatibles

### **Prioridad**

**MUST (Crítico)**

### **Fuente**

Requerimiento de operación continua

---

## RNF-004: ESCALABILIDAD Y RENDIMIENTO

### RNF-004.1: Soporte de Usuarios Concurrentes

### **Descripción**

El sistema debe funcionar correctamente aunque varias personas lo usen al mismo tiempo.

### **Condiciones de Prueba**

* Simular entre **50 y 100 usuarios** conectados
* Varias solicitudes y consultas en simultáneo

### **Criterios de Aceptación**

* El sistema se mantiene estable
* No hay retrasos mayores a **5 segundos**

### **Prioridad**

**MUST (Crítico)**

### **Fuente**

Requerimiento de rendimiento

---

## RNF-005: RENDIMIENTO EN TEMPORADA ALTA

### RNF-005.1: Tiempo de Respuesta en Temporadas de Alta Demanda

### **Descripción**

El sistema debe seguir funcionando bien cuando aumente la cantidad de reservas y consultas.

### **Criterios de Aceptación**

* Tiempo de respuesta ≤ **6 segundos**
* Todas las funciones siguen operativas

### **Prioridad**

**MUST (Crítico)**

### **Fuente**

Temporadas de alta ocupación

---

## RNF-006: USABILIDAD Y FACILIDAD DE APRENDIZAJE

### RNF-006.1: Interfaz Intuitiva y Fácil de Aprender

### **Descripción**

El sistema debe ser fácil de entender y utilizar incluso para personal nuevo o con poca experiencia en herramientas tecnológicas. Las funciones principales deben ser claras, accesibles y no requerir capacitación avanzada.

### **Criterios de Aceptación**

* El personal puede aprender a usar las funciones básicas en menos de **30 minutos**
* Navegación sencilla, con botones y opciones claramente identificados
* Flujo de uso coherente para evitar confusiones o pasos innecesarios

### **Prioridad**

**MUST (Crítico)**

### **Fuente**

Retroalimentación del personal operativo del apartahotel

---

## RNF-007: HOUSEKEEPING / VENTAS Y COMERCIAL

### RNF-007.1: Actualización Rápida de Estado de Habitaciones

### **Descripción**

Cuando se actualiza el estado de una habitación, este debe verse casi al instante en el área de ventas. Esto aplica para móviles, tablets y la versión web.

### **Criterios de Aceptación**

* Actualización visible en ≤ **1–1.5 segundos**
* Interfaz fácil de usar en móviles, tablets y web

### **Prioridad**

**MUST (Crítico)**

### **Fuente**

Housekeeping y comercial

---

## RNF-008: FINANCIERO

### RNF-008.1: Precisión y Respaldo de Información

### **Descripción**

Los reportes de pagos y reservas deben ser completamente correctos y la información debe respaldarse.

### **Criterios de Aceptación**

* Reportes sin errores
* Copias de seguridad diarias

### **Prioridad**

**MUST (Crítico)**

### **Fuente**

Área financiera

---

## RNF-009: PROCESOS ADMINISTRATIVOS Y DE ALMACENAMIENTO

### RNF-09.1: Gestión de Inventario

### **Descripción**

El sistema debe gestionar el inventario sin volverse lento y avisar cuando los insumos estén por agotarse.

### **Criterios de Aceptación**

* Manejar entre **20–30 insumos** sin pérdidas de rendimiento
* Alertas de stock bajo en ≤ **5 segundos**

### **Prioridad**

**MUST (Crítico)**

### **Fuente**

Área administrativa

---

## RNF-010: CANALES DE COMUNICACIÓN

### RNF-010.1: Centralización y Sincronización

### **Descripción**

El sistema debe mostrar reservas y mensajes en un solo lugar y estar disponible la mayor parte del tiempo.

### **Criterios de Aceptación**

* Disponibilidad ≥ **99.5%**

### **Prioridad**

**MUST (Crítico)**

### **Fuente**

Área de comunicaciones

---

## RNF-011: SISTEMA OPERATIVO

### RNF-011.1: Disponibilidad y Seguridad

### **Descripción**

El sistema debe funcionar casi sin caídas, permitir acceso seguro y responder rápido.

### **Criterios de Aceptación**

* Tiempo de respuesta ≤ **3 segundos**
* Máximo **2 horas de inactividad** al mes
* Acceso seguro y autenticado

### **Prioridad**

**MUST (Crítico)**

### **Fuente**

Equipo técnico

---

## RNF-012: SISTEMA DE MANTENIMIENTO

### RNF-012.1: Notificación de Incidentes

### **Descripción**

Cuando se reporte un problema, el sistema debe notificar rápidamente al personal técnico.

### **Criterios de Aceptación**

* Notificaciones enviadas en ≤ **15 segundos**
* Registro del incidente disponible

### **Prioridad**

**MUST (Crítico)**

### **Fuente**

Área de mantenimiento

---

## RNF-013: TIEMPO DE RESPUESTA DEL SISTEMA

### RNF-013.1: Consultas y Reportes

### **Descripción**

Las consultas deben ser rápidas y los reportes deben generarse en tiempos razonables.

### **Criterios de Aceptación**

* Consultas simples: ≤ **5 segundos**
* Reportes complejos: ≤ **45 segundos**

### **Prioridad**

**MUST (Crítico)**

### **Fuente**

Requerimiento general

---

## RNF-014: INTEGRIDAD DE LA INFORMACIÓN

### RNF-014.1: Prevención de Pérdida o Duplicación

### **Descripción**

La información debe mantenerse correcta, sin duplicados ni pérdidas aunque ocurra un fallo técnico.

### **Criterios de Aceptación**

* Datos completos
* Sin duplicaciones ni pérdidas

### **Prioridad**

**MUST (Crítico)**

### **Fuente**

Requerimiento de confiabilidad








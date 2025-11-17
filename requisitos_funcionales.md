## RF-001: GESTIÓN DE CONTRATOS Y DOCUMENTOS DIGITALES

### RF-001.1: Almacenamiento y Consulta de Documentos

**Descripción:**  
El sistema debe permitir guardar, organizar y consultar contratos y documentos administrativos. Toda la información debe estar centralizada y fácil de encontrar.

**Actor:**  
Administrador del sistema

**Precondiciones:**  
* El usuario debe haber iniciado sesión.  
* Los documentos deben estar subidos al sistema.

**Flujo Principal:**  
* El administrador entra al módulo de contratos y documentos.  
* El sistema muestra todos los documentos existentes.  
* El administrador puede elegir un documento.  
* Puede revisarlo o editarlo.  
* El sistema guarda los cambios y actualiza la información.

**Criterios de Aceptación:**  
* Acceso permitido solo a personal autorizado.  
* Búsqueda rápida y eficiente.

**Prioridad:** MUST

**Fuente:** Entrevista CEO – “Toda la información debe estar centralizada y fácil de acceder.”

---

## RF-002: CONTROL DE LA CAPACIDAD DEL HOTEL

### RF-002.1: Registro de Ocupación

**Descripción:**  
El sistema debe llevar el registro de la ocupación y mostrar la disponibilidad de los 27 apartamentos y 10 habitaciones en tiempo real.

**Actor:**  
Recepcionista

**Precondiciones:**  
- Habitaciones y apartamentos registrados.  
- Personal registrado.

**Flujo Principal:**  
* El encargado abre el módulo de capacidad.  
* El sistema muestra la disponibilidad actual.  
* Puede consultar la ocupación por unidad.  
* La disponibilidad se actualiza automáticamente con cada reserva o check-out.

**Criterios de Aceptación:**  
- Información precisa y actualizada.  
- Visualización clara por tipo de unidad.

**Prioridad:** MUST

**Fuente:** Entrevista CEO – “Se debe gestionar eficientemente la ocupación del hotel.”

---

## RF-003: ADMINISTRACIÓN DE SERVICIOS DEL HOTEL

### RF-003.1: Gestión de Servicios por Apartamento/Habitación

**Descripción:**  
El sistema debe permitir asignar y gestionar servicios como housekeeping, mantenimiento y atención personalizada para cada habitación o apartamento.

**Actor:**  
Personal administrativo y de limpieza

**Precondiciones:**  
- Habitaciones y apartamentos registrados.  
- Personal registrado.

**Flujo Principal:**  
* El personal accede al módulo de servicios.  
* El sistema muestra los servicios asignados a cada unidad.  
* Se registran nuevas tareas o servicios.  
* El sistema actualiza el estado en tiempo real.

**Criterios de Aceptación:**  
- Servicios correctamente asignados.  
- Información visible para todas las áreas.

**Prioridad:** MUST

**Fuente:** Entrevista CEO – “Cada servicio debe estar correctamente asignado.”

---

## RF-004: GESTIÓN DE NOTIFICACIONES AUTOMÁTICAS

### RF-004.1: Generación de Notificaciones

**Descripción:**  
El sistema debe generar automáticamente notificaciones de pagos, confirmaciones de reservas o avisos importantes, enviándolas en tiempo real.

**Actor:**  
Administrador del sistema / Usuario

**Precondiciones:**  
- Usuario registrado.  
- Evento que genere la notificación.

**Flujo Principal:**  
* Se registra un evento relevante.  
* El sistema genera la notificación.  
* El usuario la recibe mediante Gmail o WhatsApp.  
* El sistema registra la notificación.

**Criterios de Aceptación:**  
* Notificaciones automáticas en tiempo real.

**Prioridad:** MUST

**Fuente:** Entrevista CEO – “El sistema debe mantener a los usuarios informados al instante.”

---

## RF-005: ADMINISTRACIÓN DE APARTAMENTOS AMOBLADOS CON SERVICIOS HOTELEROS

### RF-005.1: Registro y Gestión de Apartamentos

**Descripción:**  
El sistema debe permitir registrar y gestionar los apartamentos amoblados, vinculándolos con los servicios hoteleros disponibles.

**Actor:**  
Administrador del sistema

**Precondiciones:**  
- Apartamentos y servicios registrados.  
- Personal autenticado.

**Flujo Principal:**  
* El administrador ingresa al módulo de apartamentos amoblados.  
* El sistema muestra los apartamentos registrados.  
* Se asignan los servicios correspondientes.  
* El sistema guarda y actualiza la información.

**Criterios de Aceptación:**  
- Apartamentos correctamente vinculados con servicios.  
- Información accesible para personal autorizado.

**Prioridad:** SHOULD

**Fuente:** Entrevista CEO – “Garantizar una experiencia integral para el cliente.”

---

## RF-006: SOPORTE TÉCNICO MULTICANAL

### RF-006.1: Atención Telefónica y WhatsApp

**Descripción:**  
El sistema debe ofrecer soporte técnico vía teléfono y WhatsApp, facilitando la comunicación con los clientes.

**Actor:**  
Cliente

**Precondiciones:**  
- Cliente registrado.  
- Personal de soporte disponible.

**Flujo Principal:**  
* El cliente solicita soporte telefónico o por WhatsApp.  
* El sistema registra la solicitud.  
* Un agente atiende y registra la solución.  
* El cliente recibe notificación de cierre.

**Criterios de Aceptación:**  
- Respuesta oportuna.  
- Registro completo de interacciones.

**Prioridad:** SHOULD

**Fuente:** Entrevista CEO – “Mantener comunicación constante y eficiente.”

---

## RF-007: REGISTRO Y GESTIÓN DE CLIENTES FRECUENTES

### RF-007.1: Identificación y Beneficios

**Descripción:**  
El sistema debe identificar clientes frecuentes y ofrecerles beneficios como descuentos y preferencias.

**Actor:**  
Administrador del sistema

**Precondiciones:**  
- Clientes registrados con historial.

**Flujo Principal:**  
* El administrador accede al módulo de clientes frecuentes.  
* El sistema muestra su historial y preferencias.  
* Se aplican beneficios automáticamente.

**Criterios de Aceptación:**  
- Historial completo y actualizado.  
- Beneficios asignados correctamente.

**Prioridad:** MUST (Crítico)

**Fuente:** Entrevista CEO – “Reconocer y premiar a clientes frecuentes.”

---

## RF-008: CHECK-IN Y CHECK-OUT DIGITAL

### RF-008.1: Registro Digital de Entrada y Salida

**Descripción:**  
El sistema debe permitir check-in y check-out digital para reducir tiempos de espera.

**Actor:**  
Recepcionista

**Precondiciones:**  
- Cliente registrado con reserva activa.

**Flujo Principal:**  
* El recepcionista accede al módulo.  
* Ingresa los datos.  
* El sistema valida y registra la entrada/salida.  
* La disponibilidad se actualiza.

**Criterios de Aceptación:**  
- Proceso rápido ≤ 5 minutos.  
- Disponibilidad actualizada inmediatamente.

**Prioridad:** MUST

**Fuente:** CEO – “Reducir tiempos en recepción.”

---

## RF-009: GESTIÓN DE MANTENIMIENTO DE HABITACIONES

### RF-009.1: Registro y Asignación de Tareas

**Descripción:**  
El sistema debe registrar fallas y asignarlas automáticamente al personal disponible.

**Actor:**  
Personal de mantenimiento

**Precondiciones:**  
- Habitaciones registradas.  
- Personal autenticado.

**Flujo Principal:**  
* Se registra una falla o mantenimiento.  
* El sistema asigna la tarea automáticamente.  
* Se actualiza el estado cuando se completa.

**Criterios de Aceptación:**  
- Asignación automática correcta.

**Prioridad:** SHOULD

**Fuente:** CEO – “Optimizar el tiempo de respuesta.”

---

## RF-010: FINANCIERO

### RF-010.1: Vinculación Automática con Reservas y Servicios

**Descripción:**  
El sistema debe vincular automáticamente las reservas y servicios con el módulo financiero para generar reportes.

**Actor:**  
Gerente financiero

**Precondiciones:**  
- Reservas y servicios registrados.  
- Módulo financiero activo.

**Flujo Principal:**  
* El sistema recibe información.  
* Genera reportes diarios y mensuales.  
* Se consultan desde el módulo financiero.

**Criterios de Aceptación:**  
- Reportes 100% precisos.  
- Copias de seguridad automáticas.

**Prioridad:** MUST

**Fuente:** CEO – “Evitar ingreso manual de datos.”

---

## RF-011: PROCESOS ADMINISTRATIVOS Y DE ALMACENAMIENTO

### RF-011.1: Gestión de Inventario y Alertas

**Descripción:**  
El sistema debe gestionar el inventario y generar alertas cuando el stock sea bajo.

**Actor:**  
Administrador de inventario

**Precondiciones:**  
- Insumos registrados.  
- Personal autenticado.

**Flujo Principal:**  
* Se accede al módulo de inventario.  
* El sistema muestra el stock.  
* Genera alertas automáticas.  
* Se registran acciones de reposición.

**Criterios de Aceptación:**  
- Alertas en menos de 5 segundos.  
- Inventario en tiempo real.

**Prioridad:** MUST

**Fuente:** CEO – “Evitar desabastecimiento.”

---

## RF-012: SISTEMA OPERATIVO

### RF-012.1: Acceso 24/7 y Consultas en Tiempo Real

**Descripción:**  
El sistema debe permitir acceso 24/7 para consultas y solicitudes con respuesta en tiempo real.

**Actor:**  
Cliente y Empleado

**Precondiciones:**  
- Usuario autenticado.

**Flujo Principal:**  
* Acceder desde cualquier dispositivo.  
* Realizar una consulta o solicitud.  
* El sistema responde y registra la acción.

**Criterios de Aceptación:**  
- Respuesta ≤ 5 minutos.  
- Autenticación segura.

**Prioridad:** MUST

**Fuente:** CEO – “Garantizar acceso continuo.”

---

## RF-013: ACCESIBILIDAD MULTIPLATAFORMA

### RF-013.1: Acceso desde Múltiples Dispositivos

**Descripción:**  
El sistema debe funcionar en navegadores (Chrome, Safari, Edge, Firefox) y en computadores, tabletas y móviles.

**Actor:**  
Cliente / Colaborador

**Precondiciones:**  
- Usuario registrado.  
- Dispositivo compatible.

**Flujo Principal:**  
* El usuario accede desde cualquier dispositivo.  
* La interfaz se adapta automáticamente.  
* Puede consultar o gestionar información.

**Criterios de Aceptación:**  
- Funcional en todos los dispositivos.  
- Interfaz responsiva.

**Prioridad:** SHOULD

**Fuente:** CEO – “Acceso sin limitaciones técnicas.”

---

## RF-014: REPORTE DE SOLICITUDES DE SERVICIOS ADICIONALES

### RF-014.1: Generación de Informes

**Descripción:**  
El sistema debe generar informes sobre solicitudes de servicios adicionales como restaurante, transporte o seguridad.

**Actor:**  
Administrador del hotel

**Precondiciones:**  
- Servicios registrados.  
- Solicitudes realizadas.

**Flujo Principal:**  
* Acceder al módulo de reportes.  
* Generar informe detallado.  
* Exportar o visualizar.

**Criterios de Aceptación:**  
- Informe preciso y actualizado.  
- Optimiza la planificación de recursos.

**Prioridad:** SHOULD

**Fuente:** CEO – “Mejorar atención y planificación.”

---

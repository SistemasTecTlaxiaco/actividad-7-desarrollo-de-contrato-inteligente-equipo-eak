#  Sprint 3 - Implementación de Contrato Inteligente (LOC-SERV)

##  Enfoque del Sprint

Durante este sprint se desarrollará un contrato inteligente utilizando Soroban sobre la red de prueba de Stellar (TestNet), con el propósito de integrar funcionalidades Web3 dentro de la plataforma LOC-SERV.

La intención es construir una solución que permita gestionar servicios de forma descentralizada, asegurando que la información registrada sea transparente, verificable y persistente en blockchain.

Con este desarrollo se pretende:

- Registrar servicios directamente en la blockchain  
- Consultar la información almacenada en cualquier momento  
- Ejecutar operaciones mediante transacciones reales en TestNet  
- Permitir la conexión con una aplicación externa (frontend o scripts)  

---

##  Implementación en la Red de Prueba

El contrato será preparado para su despliegue en la red TestNet de Stellar, lo que permitirá validar su funcionamiento en un entorno real sin afectar redes productivas.

**Detalles del despliegue:**

- Red: Stellar TestNet  
- Estado: En proceso / Desplegado  
- Identificador del contrato: (Se agregará posteriormente)

Una vez desplegado, será posible verificar su actividad mediante herramientas externas como exploradores de blockchain, donde se reflejarán las interacciones realizadas.

---

##  Descripción General del Contrato

El contrato inteligente estará enfocado en la gestión de servicios dentro de LOC-SERV, funcionando como un sistema de almacenamiento descentralizado.

Permitirá:

- Registrar nuevos servicios con datos básicos  
- Mantener un historial de registros  
- Consultar servicios previamente almacenados  
- Garantizar que la información no sea alterada  

---

##  Operaciones Principales

El contrato contemplará funciones como:

- Alta de servicios  
- Consulta individual de registros  
- Recuperación de información almacenada  

---

##  Condiciones para Validación

### 🔹 Funcionamiento
- El contrato debe compilar correctamente  
- Debe permitir registrar información sin errores  
- Debe responder correctamente a consultas  
- La lógica debe ser clara y funcional
<img width="1600" height="751" alt="image" src="https://github.com/user-attachments/assets/ff9633df-a436-4e6c-8751-76efd5289026" />


### 🔹 Seguridad
Se considerarán aspectos básicos de seguridad en el diseño:

- Verificación de identidad para ejecutar acciones  
- Validación de datos antes de almacenarlos  
- Prevención de ejecuciones indebidas  
- Control en el acceso a funciones críticas  

---

##  Conectividad 
<img width="1248" height="341" alt="image" src="https://github.com/user-attachments/assets/33942863-cd5f-4326-a50c-3d96f4461ce9" />


El contrato estará diseñado para ser utilizado permitiendo su integración con el sistema LOC-SERV.

Para ello se contempla el uso de:

- SDK de Stellar  
- Billetera Freighter  
- Conexión directa a TestNet  

Esto facilitará la interacción del usuario con la blockchain sin necesidad de conocimientos técnicos avanzados.

---

##  Preparación del Entorno de Desarrollo

Para llevar a cabo el desarrollo se configuró el siguiente entorno:

###  Tecnologías utilizadas
- Rust  
- Soroban SDK  
- Stellar CLI  
- Freighter  

###  Configuración realizada
- Instalación de herramientas necesarias  
- Configuración de acceso a la red de prueba  
- Validación de comandos de compilación  
- Verificación de conexión con la blockchain  

---

##  Validación Inicial

Antes del despliegue, se realizarán pruebas para asegurar:

- Correcta compilación del contrato  
- Funcionamiento básico en entorno local  
- Preparación adecuada para su publicación en TestNet  

---

##  Consideraciones Finales

Este sprint representa el primer paso hacia la incorporación de tecnología blockchain dentro de la plataforma LOC-SERV.

Se espera que al finalizar:

- El contrato esté listo para desplegarse en TestNet  
- Se cuente con una base funcional para futuras integraciones  
- Se establezca una estructura sólida para el desarrollo Web3  

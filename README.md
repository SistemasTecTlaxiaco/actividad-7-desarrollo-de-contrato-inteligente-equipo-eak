# 📑 Sprint 3 - LOC-SERV: Contrato Inteligente en Soroban

##  Definición del Sprint

El objetivo principal de este sprint es lograr el desarrollo y despliegue de un Smart Contract funcional en la red de prueba (TestNet) de Stellar, así como su integración con una aplicación externa para la plataforma LOC-SERV.

Se busca que el sistema sea capaz de:

- Registrar servicios en blockchain
- Consultar información almacenada de manera descentralizada
- Interactuar correctamente con la red TestNet
- Permitir interacción mediante una interfaz web o scripts
- Validar operaciones mediante transacciones verificables

---

##  Despliegue del Smart Contract (TestNet)

El contrato inteligente será desplegado en la red TestNet de Stellar utilizando Soroban.

- Red: TestNet  
- Estado: En desarrollo / Activo  
- Contract ID: (Agregar aquí el ID cuando lo despliegues)

El contrato podrá ser verificado en el explorador de bloques, donde se podrán consultar:

- Transacciones realizadas  
- Estado del contrato  
- Interacciones con la red  

Esto asegura que el contrato funciona en un entorno real y no depende de ejecución local.

---

##  Descripción del Contrato

Se desarrollará un contrato inteligente orientado al registro de servicios dentro de la plataforma LOC-SERV.

El contrato permitirá:

- Registrar servicios con información básica
- Almacenar datos en la blockchain
- Consultar servicios registrados
- Garantizar integridad de la información

---

## Funciones Implementadas

- register_service → Registrar un servicio  
- get_service → Consultar un servicio específico  
- get_all_services → Obtener todos los servicios registrados  

---

##  Criterios de Aceptación

### 🔹 Lógica del Contrato
- Implementación correcta del registro de servicios  
- Estructura clara del código  
- Uso de almacenamiento persistente  
- Validación de datos antes de guardarlos  

### 🔹 Seguridad
Se aplicarán buenas prácticas de seguridad en blockchain:

- Uso de `require_auth()` para validar identidad  
- Validación de datos de entrada  
- Prevención de ejecución incorrecta  
- Control de acceso a funciones  

Nota: Se considera la seguridad propia de Soroban, evitando malas prácticas en el diseño.

---

##  Integración con Aplicación

El contrato será diseñado para integrarse con una aplicación externa (frontend en Vue o scripts), permitiendo su uso dentro de la plataforma LOC-SERV.

Se utilizarán herramientas como:

- Stellar SDK  
- Billetera Freighter  
- Conexión a TestNet  

---

##  Configuración del Entorno

###  Herramientas utilizadas

- Rust  
- Soroban SDK  
- Stellar CLI  
- Freighter Wallet  

###  Configuración realizada

- Instalación de dependencias necesarias  
- Configuración de acceso a TestNet  
- Preparación del entorno para compilación y despliegue  
- Verificación de conexión con la red  

---

##  Pruebas Iniciales

Se realizarán pruebas para validar:

- Compilación correcta del contrato  
- Funcionamiento en entorno local  
- Preparación para despliegue en TestNet  

---

##  Conclusión

Este sprint permitirá establecer las bases de una arquitectura Web3 para la plataforma LOC-SERV, integrando un contrato inteligente funcional en la red TestNet de Stellar.

Se busca lograr:

- Registro descentralizado de servicios  
- Integración con aplicaciones externas  
- Uso correcto de herramientas blockchain  
- Preparación para pruebas y despliegue completo  

# Sistema de Gestión para Laboratorio Clínico

Sistema de información web desarrollado para optimizar el flujo de trabajo en la unidad de laboratorio del Hospital Militar Tipo I "Cnel. Nelson Sayago Mora". El proyecto nació para reemplazar el control manual en papel por una plataforma digital que agilizara la entrega de resultados y garantizara la trazabilidad de los datos clínicos.

## Propósito del Proyecto

El sistema automatiza la recepción de órdenes médicas, el registro de muestras, la validación analítica de parámetros y la generación de reportes clínicos. Con esto se logró reducir los tiempos de espera de los pacientes y minimizar los errores humanos de digitación en los informes médicos.

## Arquitectura y Tecnologías

El desarrollo del sistema se estructuró bajo una arquitectura cliente-servidor desacoplada:

- Frontend: React para una interfaz dinámica, responsiva y de rápida navegación, estilizada con Tailwind CSS.
- Backend: PHP implementado mediante una arquitectura API REST para procesar la lógica de negocio y las peticiones del cliente.
- Base de Datos: MySQL para el modelado relacional y almacenamiento centralizado de datos.
- Prototipado: Figma para el diseño previo de la experiencia e interfaz de usuario (UI/UX).
- Control de Versiones: Git y GitHub para el seguimiento del código fuente.

## Módulos y Funcionalidades

### 1. Gestión de Pacientes e Historias Clínicas
- Registro de datos filiatorios de pacientes (militares y civiles).
- Búsqueda avanzada por cédula o nombre.
- Consulta de antecedentes y órdenes médicas anteriores.

### 2. Catálogo Analítico y Parámetros
- Configuración de tipos de exámenes (Hematología, Bioquímica, Uroanálisis, entre otros).
- Definición de parámetros específicos y rangos de referencia biológicos según edad y sexo.

### 3. Carga de Resultados y Validación Automática
- Módulo de captura de datos para el personal técnico y bioanalistas.
- Validación automática que detecta si un resultado está fuera de los rangos biológicos normales antes de emitir el reporte.

### 4. Generación de Reportes Clínicos
- Compilación automatizada de los resultados validados.
- Exportación directa de informes médicos a formato PDF para impresión o consulta digital.

### 5. Administración y Seguridad
- Autenticación y control de acceso basado en roles (Administrador, Bioanalista, Recepción).
- Bitácora de eventos e historial de operaciones en el sistema.

## Consideraciones de Seguridad y Privacidad

Por motivos de confidencialidad, privacidad de los pacientes y acuerdos con la institución de salud, la base de datos real y los registros médicos no forman parte de este repositorio público.

## Autor

José Ángel Fernández González  
Ingeniero en Sistemas

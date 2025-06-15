# Proyecto_E-commerce:


### :page_facing_up: *Documentación utilizada:* 
- Dirección del servidor: https://www.demoblaze.com/
- Requisitos: No hay requisitos
  
### 🛠️ *Lenguajes y herramientas utilizadas:*
<div id="header" align="left">

- Navegador web: Para la ejecución de las pruebas.
- DevTools (F12): Para inspeccionar elementos, ver errores en consola y monitorear solicitudes de red.
- Jira: Registro y seguimiento de errores.
- MS Office: Documentación de las pruebas.

</a>
<img decoding="async" src="https://img.shields.io/badge/WEB-black?style=for-the-badge&logo=Web&logoColor=white" alt="WEB"/>
<img decoding="async" src="https://img.shields.io/badge/DevTools-D80B01?style=for-the-badge&logo=DevTools&logoColor=white" alt="DevTools"/>
<img decoding="async" src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=Jira&logoColor=white" alt="Jira"/>
<img decoding="async" src="https://img.shields.io/badge/Microsoft_Office-D86B01?style=for-the-badge&logo=microsoft-office&logoColor=white" alt="microsoft-office"/>
</a>

### :fireworks: *Descripción del Aplicativo Ecommerce*
#### 1. Objetivo General:
El objetivo principal de este plan de pruebas es asegurar la funcionalidad crítica, la estabilidad y la usabilidad básica de la plataforma e-commerce, minimizando los riesgos asociados con la experiencia de compra del usuario final y las operaciones comerciales.

#### 2. Alcance de las Pruebas
Dado que no se dispone de requisitos formales, el alcance se definirá en función de las funcionalidades esenciales esperadas en cualquier plataforma de comercio electrónico. Se priorizarán las pruebas de las siguientes áreas:

### :page_facing_up: *Lista de Comprobación de Pruebas:*  

- Flujo de Compra Completo (End-to-End): Desde la navegación del producto hasta la confirmación del pedido y el pago.
- Gestión de Productos: Visualización, búsqueda y detalle de productos.
- Gestión de Carrito de Compras: Adición, eliminación y actualización de ítems en el carrito.
- Proceso de Pago: Integración de pasarelas de pago, cálculo de impuestos y gastos de envío.
- Gestión de Usuarios (Clientes): Registro, inicio de sesión, recuperación de contraseña y gestión de perfiles.
- Funcionalidades de Búsqueda y Filtrado: Precisión y relevancia de los resultados.

#### 3. Estrategia de Pruebas
Se adoptará una estrategia de pruebas basada en el riesgo, enfocándose primero en las funcionalidades de mayor impacto para el negocio y la experiencia del usuario.

- Pruebas Exploratorias: Inicialmente, se realizarán pruebas exploratorias para entender el comportamiento del sistema y descubrir posibles fallas inesperadas, dada la falta de requisitos.
- Pruebas Funcionales: Se validará que cada componente del flujo de compra y las funcionalidades clave operen según lo esperado desde la perspectiva del usuario.
- Pruebas de Integración: Se confirmará que los módulos críticos (ej. pasarela de pago, inventario) se comuniquen y funcionen correctamente entre sí.
- Pruebas de Usabilidad: Se evaluará la facilidad de uso y la intuición de la interfaz para el usuario final.
- Pruebas de Regresión: A medida que se realicen correcciones o nuevas implementaciones, se ejecutarán pruebas de regresión para asegurar que los cambios no introduzcan nuevos defectos o afecten funcionalidades existentes.
- Pruebas de Rendimiento (Básicas): Se realizarán verificaciones manuales o con herramientas simples para identificar cuellos de botella obvios en el rendimiento de páginas clave.

#### 4. Entorno de Pruebas
Se requerirá un entorno de pruebas dedicado que simule lo más fielmente posible el entorno de producción, con datos de prueba realistas pero ficticios para evitar impactar datos de clientes reales.
5. Criterios de Entrada y Salida
Criterios de Entrada:
La versión de la aplicación bajo prueba (AUT) ha sido desplegada en el entorno de pruebas.
Acceso disponible al entorno de pruebas y herramientas necesarias.
Identificación de los flujos de usuario más críticos para la validación inicial.
Criterios de Salida:
Las funcionalidades críticas identificadas han sido probadas y aprobadas.
No hay defectos de alta prioridad o que bloqueen el negocio abiertos.
Se ha completado la cobertura de pruebas acordada para el alcance definido.
El equipo de negocio ha validado la usabilidad y la experiencia del usuario.

### 🧪 *Resultados de las pruebas:* 
 La documentación de las pruebas se desarrollaro en los siguientes archivos disponibles.
#### :file_folder: Documentación para el aplicativo Web:
 
  - Lista de comprobación: https://docs.google.com/spreadsheets/d/1ze6Uuh9ctoRhi1UCen8MAyI6l6_5wKYlRDqmtZSSq24/edit?usp=sharing
  - Reporte y seguimiento de errores:
    
### :page_facing_up: *Informe resumen:* 
 - Informe del producto: Resumen de Pruebas End-to-End (ETE)
Las pruebas End-to-End (ETE) son un tipo de prueba de software que valida un flujo de usuario completo de principio a fin a través de la aplicación. Su objetivo principal es asegurar que todo el sistema, incluyendo todas sus integraciones y componentes (base de datos, APIs, servicios externos, interfaz de usuario), funciona correctamente como una unidad cohesiva para cumplir con los objetivo de negocio.

Puntos Clave de las Pruebas ETE:

- Simulación de Usuarios Reales: Las pruebas ETE replican la experiencia de un usuario real, ejecutando secuencias completas de acciones. Por ejemplo, en un e-commerce, un flujo ETE podría ser: iniciar sesión, buscar un producto, añadirlo al carrito, proceder al pago, completar la compra y recibir una confirmación.
- Cobertura de Flujos Críticos: Se enfocan en los flujos de negocio más importantes y críticos para la operación de la aplicación, ya que un fallo en estos podría tener un impacto significativo en el usuario o en los ingresos.
- Validación de Integraciones: Son esenciales para verificar que las interacciones entre diferentes módulos de la aplicación y sistemas externos (como pasarelas de pago, servicios de terceros, sistemas de inventario) funcionan sin problemas.
- Enfoque en el Sistema Completo: A diferencia de las pruebas unitarias (que prueban componentes individuales) o las pruebas de integración (que prueban la comunicación entre pocos componentes), las ETE abarcan la funcionalidad del sistema de punta a punta.
- Detección de Defectos Mayores: Son muy efectivas para descubrir defectos de alto impacto que solo se manifiestan cuando múltiples partes del sistema interactúan, como problemas de rendimiento, inconsistencias de datos o fallos en el flujo de trabajo.
- Ejecución Regular: Se recomienda ejecutarlas con frecuencia, especialmente después de cada nueva implementación o cambio significativo, para garantizar que las nuevas funcionalidades no rompan las existentes (pruebas de regresión ETE).
- En síntesis, las pruebas ETE son cruciales para garantizar la confiabilidad y la estabilidad de una aplicación, ofreciendo confianza en que los usuarios pueden completar sus tareas principales sin obstáculos y que el negocio puede operar eficientemente. Son la validación final antes de que un producto o una nueva funcionalidad llegue a manos del usuario.

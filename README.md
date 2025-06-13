# Proyecto_E-commerce:


### :page_facing_up: *Documentación utilizada:* 
- Dirección del servidor:
- Requisitos:
  
### 🛠️ *Lenguajes y herramientas utilizadas:*
<div id="header" align="left">
    
- Jira: Registro y seguimiento de errores.
- Drawio: Elaboración de mapa mental.
- MS Office: Documentación de las pruebas.

</a>
<img decoding="async" src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=Jira&logoColor=white" alt="Jira"/>
<img decoding="async" src="https://img.shields.io/badge/Figma-black?style=for-the-badge&logo=Figma&logoColor=white" alt="Figma"/>
<img decoding="async" src="https://img.shields.io/badge/Drawio-D85B01?style=for-the-badge&logo=Drawio&logoColor=white" alt="Drawio"/>
<img decoding="async" src="https://img.shields.io/badge/DevTools-D80B01?style=for-the-badge&logo=Drawio&logoColor=white" alt="Drawio"/>
<img decoding="async" src="https://img.shields.io/badge/SQL-009975?style=for-the-badge&logo=mysql&logoColor=white" alt="mysql"/>
<img decoding="async" src="https://img.shields.io/badge/AVS-404040?style=for-the-badge&logo=AVS&logoColor=white" alt="AVS"/>
<img decoding="async" src="https://img.shields.io/badge/Postman-D83B01?style=for-the-badge&logo=Postman&logoColor=white" alt="Postman"/>
<img decoding="async" src="https://img.shields.io/badge/JSON-30D5C8?style=for-the-badge&logo=JSON&logoColor=white" alt="JSON"/>
<img decoding="async" src="https://img.shields.io/badge/Microsoft_Office-D86B01?style=for-the-badge&logo=microsoft-office&logoColor=white" alt="microsoft-office"/>
</a>

### :fireworks: *Descripción del Aplicativo Ecommerce*
1. Objetivo General
El objetivo principal de este plan de pruebas es asegurar la funcionalidad crítica, la estabilidad y la usabilidad básica de la plataforma e-commerce, minimizando los riesgos asociados con la experiencia de compra del usuario final y las operaciones comerciales.

2. Alcance de las Pruebas
Dado que no se dispone de requisitos formales, el alcance se definirá en función de las funcionalidades esenciales esperadas en cualquier plataforma de comercio electrónico. Se priorizarán las pruebas de las siguientes áreas:

### :page_facing_up: *Lista de Comprobación de Pruebas:*  

1. Flujo de Compra Completo (End-to-End): Desde la navegación del producto hasta la confirmación del pedido y el pago.
2. Gestión de Productos: Visualización, búsqueda y detalle de productos.
3. Gestión de Carrito de Compras: Adición, eliminación y actualización de ítems en el carrito.
4. Proceso de Pago: Integración de pasarelas de pago, cálculo de impuestos y gastos de envío.
5. Gestión de Usuarios (Clientes): Registro, inicio de sesión, recuperación de contraseña y gestión de perfiles.
6. Funcionalidades de Búsqueda y Filtrado: Precisión y relevancia de los resultados.
7. Rendimiento Básico: Tiempos de carga de páginas clave y capacidad de respuesta.
8. Seguridad Básica: Protección de datos sensibles (pagos, información personal) y autenticación.

3. Estrategia de Pruebas
Se adoptará una estrategia de pruebas basada en el riesgo, enfocándose primero en las funcionalidades de mayor impacto para el negocio y la experiencia del usuario.

- Pruebas Exploratorias: Inicialmente, se realizarán pruebas exploratorias para entender el comportamiento del sistema y descubrir posibles fallas inesperadas, dada la falta de requisitos.
- Pruebas Funcionales: Se validará que cada componente del flujo de compra y las funcionalidades clave operen según lo esperado desde la perspectiva del usuario.
- Pruebas de Integración: Se confirmará que los módulos críticos (ej. pasarela de pago, inventario) se comuniquen y funcionen correctamente entre sí.
- Pruebas de Usabilidad: Se evaluará la facilidad de uso y la intuición de la interfaz para el usuario final.
- Pruebas de Regresión: A medida que se realicen correcciones o nuevas implementaciones, se ejecutarán pruebas de regresión para asegurar que los cambios no introduzcan nuevos defectos o afecten funcionalidades existentes.
- Pruebas de Rendimiento (Básicas): Se realizarán verificaciones manuales o con herramientas simples para identificar cuellos de botella obvios en el rendimiento de páginas clave.

4. Entorno de Pruebas
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


# Proyecto_ demoblaze (e-commerce):
![image](https://github.com/user-attachments/assets/5e3573e6-5b3b-4ec8-8fbd-c99dc7c5f95c)

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

### :fireworks: *Descripción del Aplicativo Demoblaze (ecommerce).*
#### 1. Objetivo General:
Este plan de pruebas es asegurar la funcionalidad crítica, la estabilidad y la usabilidad básica de la plataforma demoblaze e-commerce, minimizando los riesgos asociados con la experiencia de compra del usuario final y el comportamiento durante el proceso de compra.

#### 2. Alcance de las Pruebas
- Aplicación a probar: Aplicación web DemoBlaze (versión de escritorio) accesible en https://www.demoblaze.com/.
- Funcionalidad principal: Proceso de realización de pedidos, desde la navegación de productos hasta la finalización de la orden.
- Tipo de prueba: Exploratoria, enfocada en la usabilidad y flujo general

#### 3. Entorno de Pruebas
- Navegador(es) recomendado(s): Chrome, Firefox, Edge (utilizaremos Chrome para las pruebas).
- Configuración: (Navegador Chrome Versión 137.0.7151.104 (Build oficial) (64 bits)). Sistema operativo: (SO Windows 10, 64 bits), resolución 1920x1080.).
- Conexión a internet: Estable.
- Credenciales de usuario: Se recomienda tener al menos una cuenta de usuario registrada y, si es posible, una cuenta nueva para probar el registro.
  
#### 4. Lista de Comprobación de Pruebas Exploratorias.
#### *Acceso y navegación*
- Acceso a la web:
  Verificar que se puede acceder a https://www.demoblaze.com/.
  Comprobar la carga inicial de la página y que los elementos principales son visibles (barra de navegación, productos, etc.).
- Inicio de sesión/Registro:
Intentar registrarse con un nuevo usuario. Verificar los mensajes de éxito/error.
Intentar iniciar sesión con credenciales válidas e inválidas.
Verificar la opción de "Log out" y que la sesión se cierre correctamente.
- Navegación general:
Explorar el menú principal y las categorías de productos (Teléfonos, Laptops, Monitores).
Verificar que los enlaces principales funcionan y dirigen a las páginas correctas.
Verificar la funcionalidad de los botones "Next" y "Previous" en las listas de productos.
#### *Búsqueda y Selección de Productos (simulada).*
-Página principal:
Explorar los productos destacados en la página principal.
Hacer clic en diferentes categorías para ver si los productos se actualizan.
-Página de producto:
Seleccionar un producto haciendo clic en su imagen o nombre.
Verificar que se muestra la información relevante del producto (descripción, precio, imágenes).
Verificar que el botón "Add to cart" es visible y funcional.
#### *Adición de Productos al Carrito.*
-Agregar al carrito:
Desde la página de un producto, hacer clic en "Add to cart".
Verificar que aparece un mensaje de alerta de éxito ("Product added."). Aceptar el mensaje.
Repetir el proceso con varios productos diferentes.
-Visualización del carrito:
Navegar a la página del carrito de compras haciendo clic en "Cart" en la barra de navegación.
Verificar que los productos agregados se muestran correctamente en el carrito.
Comprobar que el nombre, precio y cantidad de cada producto sean correctos.
#### *Proceso de Checkout.*
-Página del carrito:
Verificar que se muestran los productos seleccionados y sus precios.
No hay una opción directa para modificar cantidades o eliminar ítems en el carrito de DemoBlaze. Observar y documentar este comportamiento.
Hacer clic en el botón "Place Order".
-Formulario de compra:
Completar todos los campos requeridos en el formulario ("Name", "Country", "City", "Credit card", "Month", "Year").
Intentar dejar campos vacíos y observar los mensajes de error.
Ingresar datos inválidos (ej. letras en campos numéricos) y observar las validaciones.
Ingresar datos válidos y hacer clic en "Purchase".
-Confirmación de compra:
Verificar que aparece el mensaje de "Thank you for your purchase!" o similar.
Verificar que se muestra el ID de la orden y el monto.
Hacer clic en "OK".

### :page_facing_up: *Resumen Lista de Comprobación de Pruebas:*  
- Registro y acceso a la cuenta: Verificación del proceso de creación de una cuenta nueva, incluyendo la adición de datos de envío (si aplica en el flujo de registro inicial de DemoBlaze), y la funcionalidad de inicio de sesión con una cuenta existente.
- Navegación y selección de productos: Exploración de categorías, visualización de detalles de productos y simulación de búsqueda (ya que DemoBlaze no tiene una barra de búsqueda explícita).
- Adición de productos al carrito: Añadir unidades individuales, múltiples y variados productos, observando la actualización del carrito y las alertas de confirmación.
- Proceso de checkout: Revisión de productos en el carrito, exploración del botón "Place Order" y completado del formulario de compra con datos válidos e inválidos, hasta la confirmación final del pedido (sin realizar una compra real).
  
#### 5. Estrategia de Pruebas 
Esta estrategia de pruebas se enfoca en una exploración ágil y sencilla de la aplicación web DemoBlaze para escritorio, específicamente en el proceso de pedidos, enfocándose primero en las funcionalidades clave de mayor impacto para el negocio, la experiencia del usuario y áreas que requieren atención adicional en una fase inicial.

- Pruebas Exploratorias: Inicialmente, se realizarán pruebas exploratorias para entender el comportamiento del sistema y descubrir posibles fallas inesperadas, dada la falta de requisitos.
- Pruebas Funcionales: Se validará que cada componente del flujo de compra y las funcionalidades clave operen según lo esperado desde la perspectiva del usuario.
- Pruebas de Usabilidad: Se evaluará la facilidad de uso y la intuición de la interfaz para el usuario final.

### 🧪 *Resultados de las pruebas:* 
 La documentación de las pruebas se desarrollaro en los siguientes archivos disponibles.
#### :file_folder: Documentación para el aplicativo Web:
 
  - Lista de comprobación: https://docs.google.com/spreadsheets/d/1ze6Uuh9ctoRhi1UCen8MAyI6l6_5wKYlRDqmtZSSq24/edit?usp=sharing
  - Reporte y seguimiento de errores:
    
### :page_facing_up: *Informe resumen:* 
 - Informe del producto:
   Este plan es un punto de partida para una exploración efectiva. Dado que DemoBlaze es una aplicación de demostración, puede que algunas funcionalidades sean intencionalmente limitadas o no estén completamente desarrolladas


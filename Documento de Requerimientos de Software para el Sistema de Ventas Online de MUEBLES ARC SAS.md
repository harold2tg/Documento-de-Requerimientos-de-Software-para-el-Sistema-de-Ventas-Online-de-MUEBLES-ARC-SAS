




Documento de Requerimientos de Software para el Sistema de Ventas Online de MUEBLES ARC SAS









Versión: 0.0.1















Elaborado:

Harold de Jesús Torres Gallo.

Ingeniero de sistemas.

Especialista en el desarrollo de software.


Para la empresa:

MUEBLES ARC SAS.
















Introducción.



Este documento de requerimientos de software establece las bases y especificaciones necesarias para el desarrollo del Sistema de Ventas Online destinado a MUEBLES ARC SAS. En respuesta a la creciente demanda del mercado y a la necesidad de adaptarse a las tendencias digitales, se propone la implementación de una plataforma que permita a MUEBLES ARC SAS ofrecer sus productos a través de un canal de ventas en línea. Este sistema no solo busca proporcionar una experiencia de compra conveniente y accesible para los clientes, sino también optimizar la gestión interna de inventario, promociones y seguimiento de ventas para MUEBLES ARC SAS. A través de este documento, se delinean los requisitos funcionales y no funcionales necesarios para el desarrollo exitoso de esta plataforma de ventas en línea.
































**Objetivo General.**

El objetivo general es concebir, diseñar y desarrollar un Sistema de Ventas Online integral para MUEBLES ARC SAS, ofreciendo una plataforma digital que permita a los clientes realizar compras de manera eficiente y atractiva, mientras optimiza los procesos internos de la empresa.



**Objetivos Específicos.**

- Definir Requisitos Funcionales y No Funcionales: Establecer claramente los requerimientos de la plataforma, tanto en funcionalidades como en características técnicas y de rendimiento. 
- Diseñar una Interfaz de Usuario Intuitiva y Atractiva: Desarrollar una interfaz web amigable que permita a los clientes navegar fácilmente por el catálogo de productos y realizar compras de manera sencilla. 
- Implementar Gestión Automatizada de Inventario: Desarrollar un sistema que actualice automáticamente el inventario en tiempo real al realizar ventas, garantizando la precisión de los niveles de stock. 
- Crear un Sistema de Promociones y Seguimiento de Ventas: Habilitar la gestión de promociones y descuentos, además de proporcionar a los clientes herramientas para seguir el estado de sus pedidos.














**Casos de uso.**

Caso de uso general de la aplicación.

![](Aspose.Words.50fa7b4d-c6f0-4e45-9033-db40e48435d9.001.png)

Caso de uso detallado por el cliente.


![](Aspose.Words.50fa7b4d-c6f0-4e45-9033-db40e48435d9.002.png)


















Caso de uso detallado Muebles ARC  S.A.S

![](Aspose.Words.50fa7b4d-c6f0-4e45-9033-db40e48435d9.003.png)












**Historias de usuarios.**

**Historias de usuario cliente**

**Historia de Usuario 001**: Como cliente, quiero poder registrarme fácilmente en la plataforma de ventas online para acceder a los productos y recibir notificaciones relevantes. 

Campos necesarios: nombres completos, dirección física, email, contraseña, celular.

**Historia de Usuario 002:** Como cliente, deseo recibir confirmaciones por correo electrónico sobre mi registro, mis compras realizadas y cualquier promoción o descuento disponible.

**Historia de Usuario 003:** Como cliente, me gustaría recibir correos electrónicos con información sobre promociones y descuentos para aprovechar ofertas especiales al realizar compras. 

**Historia de Usuario 004:** Como cliente, quiero poder buscar fácilmente productos en la plataforma y ver detalles como precio, descripción y disponibilidad. 

**Historia de Usuario 005:** Como cliente, necesito acceder a un historial completo de mis compras anteriores para realizar un seguimiento de mis transacciones. 

**Historia de Usuario 006:**  Como cliente, deseo tener la capacidad de seguir la trazabilidad del envío para conocer el estado y la ubicación de los productos que he comprado.

**Historia de Usuario 017**: cliente  quiero acceder a todos los pagos que he realizado para llevar un control interno de mis compras

**Historias de usuario Personal muebles ARC S.A.S**

**Historia de Usuario 008**: Como personal de MUEBLES ARC SAS, necesito tener la capacidad de agregar nuevos productos al sistema, incluyendo detalles como nombre, descripción, precio y cantidad en inventario. 

**Historia de Usuario 009**: Como personal de MUEBLES ARC SAS, quiero que el sistema actualice automáticamente el inventario cada vez que se realice una venta para mantener un registro preciso de los niveles de stock. 

**Historia de Usuario 010**: Como personal de MUEBLES ARC SAS, deseo crear promociones especiales y cupones de descuento para ofrecer a los clientes ofertas atractivas. 

**Historia de Usuario 011**: MUEBLES ARC SAS quiero implementar una pasarela de pago para permitir a los clientes comprar con facilidad y seguridad

**Historia de Usuario 012**: Personal MUEBLES ARC SAS quiero acceder a todas las confirmaciones de pagos de mis clientes para llevar un control interno.









**Diagramas C4**




**Diagrama de contexto.**

![](Aspose.Words.50fa7b4d-c6f0-4e45-9033-db40e48435d9.004.png)








**Diagrama de contenedores.**





![](Aspose.Words.50fa7b4d-c6f0-4e45-9033-db40e48435d9.005.png)








**Diagrama de Componentes**



![](Aspose.Words.50fa7b4d-c6f0-4e45-9033-db40e48435d9.006.png)





**Diagrama de secuencia.**

**Cliente**

![](Aspose.Words.50fa7b4d-c6f0-4e45-9033-db40e48435d9.007.png)

![](Aspose.Words.50fa7b4d-c6f0-4e45-9033-db40e48435d9.008.png)![](Aspose.Words.50fa7b4d-c6f0-4e45-9033-db40e48435d9.009.png)


































Muebles ACR S.A.S


![](Aspose.Words.50fa7b4d-c6f0-4e45-9033-db40e48435d9.010.png)

![](Aspose.Words.50fa7b4d-c6f0-4e45-9033-db40e48435d9.011.png)



















**Requerimientos no funcionales**

Rendimiento: 

- Tiempo de Carga: La plataforma debe cargar en menos de 3 segundos para garantizar una experiencia fluida al usuario.
- Escalabilidad: El sistema debe ser escalable para manejar un aumento gradual del tráfico de usuarios sin degradación del rendimiento. 

Seguridad: 

- Protección de Datos: Cumplir con los estándares de seguridad para proteger la información del cliente y garantizar la privacidad de los datos personales.
- Autenticación y Autorización: Implementar un sistema de autenticación seguro y permisos de acceso adecuados para proteger áreas sensibles de la plataforma. 

Usabilidad:

- Accesibilidad: La plataforma debe ser accesible para personas con discapacidades, cumpliendo con estándares de accesibilidad web. Interfaz Intuitiva: La interfaz de usuario debe ser intuitiva y fácil de usar, independientemente del nivel de experiencia del usuario.

Disponibilidad: 

- Tiempo de Disponibilidad: Garantizar un tiempo de actividad del sistema del 99.9% para evitar interrupciones en el servicio. Respaldo y Recuperación: Implementar sistemas de respaldo periódicos y planes de recuperación en caso de fallas o pérdida de datos. 

Mantenimiento: 

- Facilidad de Mantenimiento: El sistema debe ser fácil de mantener y actualizar, con documentación clara para los desarrolladores y administradores. 
- Monitorización y Registro: Implementar herramientas de monitorización para identificar y solucionar problemas de rendimiento o seguridad. 

Compatibilidad: 

- Navegadores y Dispositivos: Garantizar la compatibilidad con una amplia gama de navegadores web y dispositivos móviles para una experiencia consistente. 


Rendimiento del Sistema:

- Carga Máxima de Usuarios: Establecer la capacidad máxima de usuarios concurrentes que el sistema puede manejar sin degradación del rendimiento.
- Tiempo de Respuesta del Servidor: Definir el tiempo máximo permitido para las solicitudes del servidor y las respuestas del sistema.





**Escenarios que no manifiesta el enunciado pero se tienen en cuenta para hacer el proyecto**:

- Se debe tener una pasarela de pago para que el cliente pueda comprar
- La aplicación o software se asume que se realizara con Python y FastAPi en la parte del back-End.



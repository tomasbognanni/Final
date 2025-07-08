5. Diagrama de Secuencia

Definición:
Representa la interacción entre objetos en una secuencia temporal.

![image](https://github.com/user-attachments/assets/97f19c63-f97e-41ef-9617-39d673847cfd)

 Participantes del sistema:
 Actor (cliente): Inicia la interacción desde la interfaz de compra online.

 Interfaz de compra online: Punto de entrada al sistema.

 Lista de productos: Provee los datos de productos.

 Interfaz de compra: Encargada de gestionar el proceso de selección, consulta y compra.

 Pedido: Representa el registro del pedido generado.

 Opción de pago: Procesa la forma de pago elegida.


Buscar y seleccionar productos:

El cliente busca y selecciona productos desde la interfaz online.

Se realiza una consulta de producto a la Lista de productos.

Comprar productos:

El cliente selecciona comprar, lo que activa la obtención de productos seleccionados.

La Interfaz de compra consulta la información de precios a la Lista de productos.

Mostrar resultados:

El sistema muestra los productos seleccionados y sus precios al cliente.

Notificaciones:

El sistema envía una notificación y luego un correo electrónico al cliente para confirmar la acción.

Autorización y pago:

La Interfaz de compra solicita autorización de la compra y luego imprime la información de pago.

El cliente elige la opción de pago y efectúa el pago.

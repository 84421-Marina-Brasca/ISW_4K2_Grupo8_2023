# ISW
## PRÁCTICO 6 - REQUERIMIENTOS ÁGILES - Implementación de user stories 

## User stories:
### Realizar Pedido a un Comercio adherido
Como Solicitante quiero realizar un Pedido a un comercio adherido para recibir los Productos en mi domicilio
### Criterios de Aceptación
 - Se debe indicar la dirección (calle, número, ciudad y referencia opcional en formato de texto). 
 - Se debe poder seleccionar la ciudad de un listado de ciudades disponibles.
 - Se debe seleccionar la forma de pago: Efectivo o Tarjeta de Débito/Crédito.
 - Si paga en efectivo debe indicar el monto con el que va a pagar. 
 - Si paga con tarjeta debe ingresar el número de la tarjeta, nombre y apellido del Titular, fecha de vencimiento (MM/AAAA) y CVC.
 - Debe ingresar cuando quiere recibirlo: “Lo antes posible” o una fecha/hora de recepción.
 - El Carrito debe contener al menos un Producto del Comercio adherido.
### Criterios de Prueba
 - Probar realizar un Pedido a un Comercio adherido en efectivo “lo antes posible” (pasa)
 - Probar realizar un Pedido a un Comercio adherido con tarjeta “lo antes posible” (pasa)
 - Probar realizar un Pedido a un Comercio adherido programando la fecha/hora de entrega (pasa)
 - Probar realizar un Pedido a un Comercio adherido con el carrito vacío (falla)
 - Probar realizar un Pedido a un Comercio adherido con una tarjeta inválida (falla)
 - Probar realizar un Pedido a un Comercio adherido con una tarjeta de crédito MasterCard (pasa)
 - Probar realizar un Pedido a un Comercio adherido en efectivo sin indicar el monto a pagar (falla)
 - Probar realizar un Pedido a un Comercio adherido programando una fecha/hora de entrega no válida (falla)

# Sistema-de-Gestion

Microservicios:

1.-ms-usuarios: El "directorio". Guarda la información blanda y pública del usuario (nombre, apellido, teléfono, dirección de envío, avatar). 

2.-ms-reportes: Analítica para el administrador.

3.-ms-seguimiento: Tracking del estado del pedido.

4.-ms-notificaciones: Envío de alertas (correos/mensajes).

5.-ms-pagos: Procesamiento y validación financiera.

6.-ms-logistica: Gestión de entregas o trámites legales.

7.ms-seguridad: El "guardia". Se encarga exclusivamente de las credenciales (email y contraseña), aplicar el encriptado BCrypt, manejar los roles (Vendedor, Cliente, Admin) y emitir el token JWT.

8.-ms-promociones: Gestión de descuentos y ofertas.

9.-ms-inventario(stock): Disponibilidad y estados de stock.

10.-ms-catalogo: Información de productos/propiedades (sin lógica de stock).

11.--ms-pedidos: Generación y gestión de órdenes de venta.

VIDEO DE PROYECTO SISTEMA GESTION PROPIEDADES:
https://drive.google.com/file/d/1qFel2TqzFmHlOSR4uwMjM6OZxOgh28dK/view?usp=sharing

Lo que se hizo fue ingresar los problemas que tuvimos y agregar los comandos @Tag, @Operation y @ApiResponses
despues probamos que todo esta fuincionando correctamente todos los ms y conectarlos para que sea un ms

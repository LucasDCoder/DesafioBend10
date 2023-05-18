# Managing-Errors


Consigna

Se aplicará un módulo de mocking y un manejador de errores a tu servidor actual

Formato

Link al repositorio de github sin node_modules

Sugerencias
Céntrate solo en los errores más comunes 
Puedes revisar el documento de testing aquí: 

Aspectos a incluir

- [X] Generar un módulo de Mocking para el servidor, con el fin de que, al inicializarse pueda generar y entregar 100 productos con el mismo formato que entregaría una petición de Mongo. Ésto solo debe ocurrir en un endpoint determinado (‘/mockingproducts’)

COMENTARIO: SE IMPLEMENTA EXITOSAMENTE EN ENDPOINT REQUERIDO, EXISTE UNA VALIDACION PARA NO AGREGAR PRODUCTOS AL CARRITO QUE NO ESTAN AGREGADOS EN LA BASE DE DATOS, ESTO APLICA PARA LOS MOCKING PRODUCTS.


- [X] Además, generar un customizador de errores y crear un diccionario para tus errores más comunes al crear un producto, agregarlo al carrito, etc.
COMENTARIO: SE ESTA OCUPANDO UN ERROR PERSONALIZADO PARA LA CREACION DE USUARIOS.



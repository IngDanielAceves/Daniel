### Objetos SalesForce

------

| Num | Object   | Data | Relationship |
| ------------ | ------------ |------------ |------------ |
| 1 | Lead          | Este objeto tiene como caracteristica guardar los datos de las personas que deseas como clientes. | none |
| 2 | Account       | Estobjeto tiene la caracteristica de guardar datos de una cuenta individual, que es una organización o persona involucrada con su negocio (como clientes, competidores y socios).| 4 , 8 , 9|
| 3 | Contact       | En este objeto podemos encontrar los datos de la persona, empresa o dependencia guardada que a la ves esta asociada con Account.| 2 , 8 , 9 |
| 4 | Opportunity   | Este objeto tiene la caracteristica de guardar datos para la administracion sobre una venta o trato pendiente tambien se puede sincronizar este objeto con una cotizacion. | 3 , 6 , 10 |
| 5 | Product       | Este objeto tiene la caracteristica de guardar los datos de varios campos que se usan solo para programaciones de cantidad e ingresos.| 2 , 9 |
| 6  | PriceBook    | Este objeto guarda los datos de precios que contiene la lista de productos que vende su organizacion.| 5 , 4 , 10|
| 7 | Quote         | Este objeto en particular que representa una cotizacion que contiene los datos de registro de precios propuestos para productos y servicios.| 5 |
| 8  | Assest       | Este objeto tiene la caracterisitica de guardar los datos para realizar un seguimiento de los productos vendidos a los clientes.| 2 , 3 , 5 , 9 |
| 9  | Case         | En este objeto guarda datos particularmente los asuntos o problemas del cliente. | 2 , 3 , 5 , 8 |
| 10  | Article     | Este objeto se puede utilizar para asociar un artículo con categorías de datos de un grupo de categorías de datos o para consultar las selecciones de categoría de un artículo. | 4 , 6|

-----




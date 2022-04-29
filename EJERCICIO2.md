#### Comprensión del protocolo HTTP

![3400326432](https://user-images.githubusercontent.com/91232190/165890113-86fa5b9b-a27e-4a8a-8892-db0ceb1d4a01.png)


1️⃣ ¿Qué es un servidor HTTP❓ 

    Es un protocolo de acceso para las páginas web a través de Internet. Es el nombre de un protocolo el cual nos permite
    realizar una petición de       datos y recursos,El HTTP es el protocolo que se usa para comunicarse con el servidor web
    con el fin de acceder a un navegador web o página web.

2️⃣ ¿Qué son los verbos HTTP❓ Mencionar los más conocidos

   	POST o GET, que son los verbos más conocidos, de hecho, son utilizados con formularios HTML.
    
3️⃣ ¿Qué es un request y un response en una comunicación HTTP❓ ¿Qué son los headers❓
    
    Request HTTP 💬 📥
    La línea de salida de una petición HTTP se conoce como línea de la petición. Siempre es la primera línea del mensaje de solicitud y contiene         tres campos:
    
    • Un método HTTP
    • Un identificador universal de recursos (URI)
    • Una versión del protocolo HTTP

    Response HTTP 💬📤
    
    Una vez que el servidor ha recibido y procesado la solicitud, éste debe devolver un mensaje de respuesta HTTP hacia el cliente.
    
    Los HTTP headers son la parte central de los HTTP requests y responses, y transmiten información acerca del navegador del cliente, de la página     solicitada, del servidor, etc. 

4️⃣. ¿Qué es un queryString❓ (En el contexto de una url)

    Es la parte de una URL que contiene los datos que deben pasar a aplicaciones web como los programas CGI.
   [CGI](https://es.wikipedia.org/wiki/Interfaz_de_entrada_com%C3%BAn).

5️⃣.	¿Qué es el responseCode❓ ¿Qué significado tiene los posibles valores devueltos❓

      Indica si la solicitud de codificación geográfica se ha realizado correctamente o no. Como el error 401 es 
      otro http response code.Son el tipo de comunicación web que se utiliza para indicar problemas o situaciones
      de los sitios y páginas que se dan por parte del cliente o del servidor.
      
6️⃣.	¿Cómo se envía la data en un Get y cómo en un POST❓ 
      
      La diferencia entre los métodos get y post radica en la forma de enviar los datos a la página cuando se pulsa
      el botón “Enviar”. Mientras que       el método GET envía los datos usando la URL, el método POST los envía de
      forma que no podemos verlos (en un segundo plano u "ocultos" al usuario).
   --------
      
      GET:
      Un resultado usando el método GET, a modo de ejemplo, podría ser el siguiente:
      http://www.aprenderaprogramar.com/newuser.php?nombre=Pepe&apellido=Flores&email=h52turam%40uco.es&sexo=Mujer  
      
      POST:
      Un ejemplo de uso del método post sería este:
      <form action="http://www.aprenderaprogramar.com/prog/newuser" method ="post">

7️⃣.	¿Qué verbo http utiliza el navegador cuando accedemos a una página❓

      Utilizamos el metodo GET ya que solo estamos solicitando informacion.

8️⃣ .	💭Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles.

      XML es uno de los formatos más utilizados para el intercambio de información entre sistemas. 
      El formato de este estándar está basado en texto para representar información estructurada: 
      datos, documentos, configuración, etc..

```XML 
     <pieza tipo="A">
        <nombre>Tornillo</nombre>
    <descripcion>Cilindro mecanico con una cabeza utilizado en la fijación temporal de unas piezas con otras 
      </descripcion>
      <caracateristica>
        <tipo>metal</tipo>
        <tamanyo>10</tamanyo>
      </caracateristica>
      <vacio></vacio>
    </pieza>
 ```
 ------
 
       JSON (JavaScript Object Notation): 
       Formato de intercambio de información más legible por el ser humano e igual de eficaz que XML para la comunicación entre maquinas  
       y está basado en un subconjunto del lenguaje de programación JavaScript.
       Ejemplo anterior utilizando JSON.
       
 ``` JSON
        {
          “pieza”: {
             “tipo”: “A”
             “nombre”: “Tornillo”,
             “descripcion”: “Cilindro mecánico con una cabeza utilizado en la fijación temporal de unas piezas con otras”,
             “caracteristica”: {
                “tipo”: “metal”
                “tamanyo”: 10
           },
        “vacio”: “”
        }
    }

```
       
     

9️⃣.	💭Explicar brevemente el estándar SOAP

    SOAP es un estándar basado en XML para la transmisión de mensajes en HTTP y otros protocolos de Internet. Es un protocolo 
    ligero para el intercambio de información en un entorno descentralizado y distribuido.

🔟.	💭Explicar brevemente el estándar REST Full

    RESTful hace referencia a servicios que se implementan como una arquitectura (API).

1️⃣1️⃣.¿Qué son los headers en un request❓ ¿Para qué se utiliza el key Content-type en un header❓

    Transmiten información acerca del navegador del cliente a la pagina solicitada.
 ------
 
     Cada vez que visitas cualquier sitio se pueden observar los headers del request enviado. 
 Ejemplo:
   
     GET php.net HTTP/1.1 **Accept**: text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,*/*;q=0.8
     **Accept-Encoding**: gzip, deflate, sdch
     **Accept-Language**: es-ES,es;q=0.8,en;q=0.6
     **Cache-Control**: max-age=0
     **Connection**: keep-alive
     **Cookie**: COUNTRY=NA%2C122.16.430.651; LAST_LANG=es; LAST_NEWS=3847110839
     **Host**: php.net
     **If-Modified-Since**: Mon, 09 Nov 2015 11:50:11 GMT
     **Upgrade-Insecure-Requests**: 1
     **User-Agent**: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_10_4) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/46.0.2490.80 Safari/537.36
     
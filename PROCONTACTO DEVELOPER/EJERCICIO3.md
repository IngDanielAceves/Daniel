## Postman request como cliente

![getpostman-ar21](https://user-images.githubusercontent.com/91232190/166068250-9d717472-ef98-46e9-8c5e-a45e90e15deb.png)


1️⃣.	Realizar un request GET a la URL: https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json

![GetPostman](https://user-images.githubusercontent.com/91232190/166070648-46111b49-bf05-4cb5-81f6-6177342c5ccb.PNG)

2️⃣.	Realizar un request POST a la URL anterior, y con body:
      
  ```Json
        {
              "name":"Tu nombre",
              "email":tunombre.tuapellido@procontacto.com.mx
        }
        
  ```
Tip: (Marcar la opción “raw” como body)

![POST](https://user-images.githubusercontent.com/91232190/166085182-a84e1f25-5a82-496b-a74a-a32415e3a757.PNG)

3️⃣	Realizar nuevamente un request GET a la URL: https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json

![GET2](https://user-images.githubusercontent.com/91232190/166085214-8866527b-60fc-4515-9f12-ceeafb39811f.PNG)


[LINK EJERCICIOS POSTMAN](https://go.postman.co/workspace/Team-Workspace~f4be053e-19e8-4a13-835c-45e5f59cb56e/collection/20153200-5887538e-3dd3-4716-a517-be3be0a72e66?action=share&creator=20153200)

4️⃣   ¿Qué diferencias se observan entre las llamadas el punto 1 y 3❓

      Podemos observar que en el primer get nos da la informacion que se encuentra en el link http proporcionado en cambio cuano hacemos el post con los datos correspondientes se dan de alta en el servidor de la pagina web y al momento de hacer otro get podremos observar que los datos proporcionados en POSTMAN body RAW.
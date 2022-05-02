## ID,OBJECT AND TRIGER

-----

![getpostman-ar21](https://user-images.githubusercontent.com/91232190/166068250-9d717472-ef98-46e9-8c5e-a45e90e15deb.png)

-----

### Id Postman

-----


```Json
     "-N0s2y5h8KgsdhnDzyIs": {
        "email": "Daniel.Aceves@procontacto.com.mx",
        "name": "Daniel Aceves"
    }
 ```


-----

### Object idprocontacto

-----

![idprocontact](https://user-images.githubusercontent.com/91232190/166290668-9482a224-3f52-40e5-b0b4-e329c77d24ff.PNG)

-----

### Codigo Call apex IdProcontacto

```java
        public with sharing class CallEmailDaniel {
            
            public static final String URL = 'https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json';
            
            public static void getCharacter(Integer Id){
                
                //Instanciar las clases Http, HttpRequest y HttpResponse
                Http http = new Http();
                HttpRequest request = new HttpRequest();
                request.setEndpoint(URL+Id);
                request.setMethod('GET');
                HttpResponse response = http.send(request);
                Map<String, Object> results = new Map<String, Object>();
                List<Object> listResponse = new List<Object>();
                // If the request is successful, parse the JSON response.
                if(response.getStatusCode() == 200) {
                    // Deserialize the JSON string into collections of primitive data types.
                    results = (Map<String, Object>) JSON.deserializeUntyped(response.getBody());
                    System.debug(results);
                    }
                }
                    
        }

```

### Apex Code

```java

CallEmailDaniel.getCharacter(-N0s2y5h8KgsdhnDzyIs);

```

### Result Debug






# invoiceWebApi

Para la utilizacion apropiada de la api web es necesario: 

Instalar Visual Studio Community 2015: 

https://www.visualstudio.com/vs/community/

Conectar la BD que el cliente vaya a utilizar de la siguiente manera:

1-Abrir el archivo Web.config

2-Localizar el tag <connectionStrings>

3-Modificar en la linea <add... data-source=DIRECCION DEL SERVIDOR ...>

4-Guardar el archivo


Probar api: 

Recomendamos el uso de POSTMAN:

https://chrome.google.com/webstore/detail/postman/fhbjgbiflinjbdggehcddcbncdddomop

URLs:

GET: localhost:port/api/invoice/{id} -> muestra la informacion de la factura.

POST: localhost:port/api/invoice -> recibiendo desde la app mediante una llamada a ajax un objeto "invoice" la misma guarda la informacion en la BD
 
POST: localhost:port/api/invoice/details -> recibiendo desde la app mediante una llamada a ajax un objeto "invoice_detail" la misma guarda la informacion en la BD

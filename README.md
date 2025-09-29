# Gestion de Producto

## Requisitos
- .NET 7 SDK o superior
- MongoDB (local o remoto)

## Configuracion de la conexion a MongoDB
- La cadena de conexion, nombre de base de datos y coleccion se configuran en el archivo `appsettings.json`:
  ```json
  "MongoDbSettings": {
    "ConnectionString": "mongodb://localhost:27017/",
    "DatabaseName": "Gestion_Producto"
  }
  ```
- Asegurate de que el servidor de MongoDB este corriendo y accesible en la direccion configurada.
  
## Ejecucion de la aplicacion Blazor
1. Abre la carpeta del proyecto `Gestion de producrto`.
2. Ejecuta el Gestion de producrto.exe
3. Accede a la aplicacion en tu navegador en `http://localhost:5000/products` o la URL que indique la terminal.


## Notas
- Puedes cambiar la configuracion de MongoDB en `appsettings.json` para adaptarla a tu entorno.
- La pagina principal de la aplicacion es "Products".

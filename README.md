# APIs de Información Geográfica de España

## Descripción General
Este repositorio contiene tres archivos JSON que proporcionan información geográfica y de contacto relacionada con España. Las APIs están diseñadas para ser fácilmente accesibles y útiles para desarrolladores que necesiten datos precisos sobre países, provincias y municipios en sus aplicaciones. 

## Contenido del Repositorio

1. **Información de Países:**
   - **URL:** [Nombre del país, imagen de la bandera y el código de número de teléfono del país](https://api-spain-pm.vercel.app/PhoneNumberCode.json)
   - **Descripción:** Este JSON contiene información básica sobre varios países, incluyendo el nombre del país, la imagen de la bandera y el código de número de teléfono internacional.

2. **Provincias de España:**
   - **URL:** [Todas las Provincias de España](https://api-spain-pm.vercel.app/Provincias.json)
   - **Descripción:** Este JSON incluye una lista completa de todas las provincias de España. Es ideal para aplicaciones que necesitan datos administrativos detallados del país.

3. **Municipios de España:**
   - **URL:** [Todos los Municipios de España con el código postal](https://api-spain-pm.vercel.app/Municipios.json)
   - **Descripción:** Este JSON proporciona una lista exhaustiva de todos los municipios en España, junto con sus correspondientes códigos postales. Perfecto para proyectos que requieran información geográfica detallada a nivel municipal.

## Uso del Repositorio
Para acceder a la información, simplemente realiza una solicitud HTTP GET a las URLs proporcionadas. Los datos están estructurados en formato JSON, facilitando su integración en cualquier aplicación o sistema que necesite estos datos.

## Ejemplos de Uso en JavaScript
1. **Ejemplo de Solicitud para Obtener Información de Países:**
   ```javascript
   fetch('https://api-spain-pm.vercel.app/PhoneNumberCode.json')
     .then(response => response.json())
     .then(data => console.log(data))
     .catch(error => console.error('Error:', error));








Paises,
Provincias y  Municipios de España

https://api-spain-pm.vercel.app/Provincias.json

https://api-spain-pm.vercel.app/Municipios.json

https://api-spain-pm.vercel.app/PhoneNumberCode.json

# **ProContacto - Evaluación Práctica**
> Una interesante forma de resolver ejercicios prácticos propuesto por ProContacto
> <img src="profile-photo.png" align="right" width=180px height=180px />

J. Jordan D. Godoy
Desarrollador

> [!NOTE]
> No era consciente de la importancia de los archivos README hasta antes de toparme con esta evaluación práctica, ya siento que comienzo a aprender desde el momento cero.

## Ejercicios 
> A continuación se encuentran todos los ejercicios propuestos por ProContacto.

### Ejercicio 1
  1. Instalar el IDE Visual Studio Code:
    <br></br>
    <img src="IDEVSC.png" align="letf" width=140px height=140px />
    <br></br>
  2. Instalar GIT y GIT Bash:
    <br></br>
    <img src="GIT-GITBash.png" align="left" width=140px height=140px />
    <br></br><br></br><br></br>
> Instalados ambos programas


### Ejercicio 2
  1. **¿Qué es un servidor HTTP?**  
      Es una computadora que tiene un programa o servicio que almacena, procesa y entrega recursos web a una página en base a solicitudes mediante el protocolo HTTP.
  2. *¿Qué son los verbos HTTP? Mencionar los más conocidos*  
      * Son los métodos que definen las acciones que se pueden ejecutar en una comunicación HTTP, por ejemplo:
        * *GET:* Obtener datos de un recurso.
        * *POST:* Enviar datos para un nuevo recurso.
        * *PUT:* Actualizar datos de un recurso existente.
        * *DELETE:* Elimina los datos de un recurso.
  3. *¿Qué es un request y un response en una comunicación HTTP? ¿Qué son los headers?*  
      * *Request:* Es la solicitud que envía un cliente al servidor.
      * *Response:* Es la respuesta que recibe el cliente del servidor.
      * *Headers:* Es la información adicional que se envían en el _request_ y en el _response_ que proporcionan información sobre la solicitud o respuesta, por ejemplo, el tipo del contenido, tamaño, autenticación, etc.
  4. *¿Qué es una queryString? (En el contexto de una URL)*  
      Es la parte de la URL que que se encuentra después de *?*, estos son parámetros compuestos por pares de _clave-valor_ los cuales se usan para pasarle información al servidor.
  5. *¿Qué es el responseCode? ¿Qué significado tienen los posibles valores devueltos?*  
      Son los códigos de estado posibles que tienen las solicitudes, esto representa el estado de la respuesta de la solicitud. Por ejemplo:
        * *Cód. 200:* OK.
        * *Cód. 404:* Not Found.
        * *Cód. 500:* Internal Server Error
        * *Cód. 401:* Unauthorized
  6. *¿Cómo se envía la data en un GET y cómo en un POST?*  
      En un *GET* se envían los datos mediante la URL como parámetros en el _queryString_ y en un *POST* los datos se envían en el _body_ de la solicitud. 
  7. *¿Qué verbo HTTP utiliza el navegador cuando accedemos a una página?*  
      Se usa el verbo *GET* cuando accedemos a una página web mediante el navegador.
> [!IMPORTANT]
> El verbo *GET* es el verbo por defecto que se utiliza cuando no es especificado por la solicitud.
  8. *Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles*  
   JSON (JavaScript Object Notation):* Es un formato de intercambio de datos fácil de leer y de escribir. Ejemplo:
   ```
      {
      "nombre": "Jordan",
      "apellido": "Godoy",
      "correo": "jjordandg96@gmail.com",
      "edad": 28,
      "contratar": true
      }
   ```
   XML (eXtensible Markup Language):* Es un formato más estructurado y formal, usado para representar datos, es parecido a HTML. Ejemplo:

   ```
      <candidato>
        <nombre>Jordan</nombre>
        <apellido>Godoy</apellido>
        <correo>jjordandg96@gmail.com</correo>
        <edad>28</edad>
        <contratar>true</contratar>
      </candidato>
   ```
  9. *Explicar brevemente el estándar SOAP*  
      *SOAP (Simple Object Access Protocol):* Es un protocolo basado en XML que dicta cómo intercambiar mensajes estructurados entre aplicaciones a través de redes, usado mayormente en servicios web. Ofrece un alto nivel de seguridad y permite transacciones complejas.
  10. *Explicar brevemente el estándar RESTful*  
      *REST (REpresentational State Transfer):* Es una técnica de arquitectura de software que ayuda a crear una forma de pensar y contruir APIs. Separa a cliente y servidor, haciendo ambas partes independientes. Es un protocolo sin estado, cada petición HTTP debe contener toda la información necesaria para poder ser resuelta.
  11. *¿Qué son los headers en un request? ¿Para qué se utiliza el key Content-Type en un header?*  
      Los *headers* en un request son campos extra que proporcionan información sobre una solicitud, como por ejemplo, el tipo de cliente o el formato de los datos.
      El *header _Content-Type_* se usa para indicar el tipo de contenido que se está enviado o se espera recibir. Por ejemplo _application/json_. 

### Ejercicio 3
  1. Realizamos un request GET a la URL: https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json
        <img src="1.png" align="letf"/>
  2. Realizamos un request POST a la URL: https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json
        <img src="2.png" align="letf"/>
  3. Volvemos a realizar un request GET a la URL: https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json
        <img src="3.png" align="letf"/>
> Se puede observar, que el POST hecho en el **punto 2** ahora se ve reflejado
       
### Ejercicio 4
  [Ver mi perfil de Trailhead](https://www.salesforce.com/trailblazer/t5dhro8lc2mqbpqhmj)

### Ejercicio 5  

### Ejercicio 6  

#### Soluciones de Salesforce
  - **¿Qué es Salesforce?**  
    + Salesforce es una plataforma de software en la nube que ofrece soluciones de gestion de relaciones con los clientes (CRM), este ayuda a las empresas a gestionar y automatizar sus procesos. Dado que es una solución en la nube, permite acceder a la información desde cualquier lugar facilitando el trabajo de sus clientes.  
  - **¿Qué es Sales Cloud?**  
    + Sales Cloud es uno de los productos de Salesforce fabricado especialmente para optimizar procesos de ventas.  
  - **¿Qué es Service Cloud?**  
    + Service Cloud es una solución enfocada en mejorar el servicio y soporte al cliente.   
  - **¿Qué es Health Cloud?**  
    + Health Cloud es una plataforma de Salesforce enfocada en el sector de la salud.  
  - **¿Qué es Marketing Cloud?**  
    + Marketing Cloud es una plataforma de Salesforce enfocada en mejorar y optimizar estrategias de marketing digital.


#### Funcionalidades de Salesforce

  - **¿Qué es un RecordType?**
    * Es una configuración que permite personalizar el comportamiento de un objeto según distintos tipos de registros. 
  - **¿Qué es un ReportType?**
    * Es una plantilla que define qué objetos y campos están disponibles en un reporte.  
  - **¿Qué es un Page Layout?**
    * Es la configuración que define la disposición de campos, secciones y botones en una página de un registro. 
  - **¿Qué es un Compact Layout?**
    * Es el diseño simplificado de campos clave que se muestra en dispositivos móviles.   
  - **¿Qué es un Perfil?**
    * Es la configuración que define los permisos de acceso y control sobre objetos, campos y funciones de Salesforce para sus usuarios.   
  - **¿Qué es un Rol?**
    * Es la estructura que define la jerarquía de acceso y visibilidad de datos.  
  - **¿Qué es un Validation Rule?**
    * Es una regla que valida la entrada de datos en un campo, asegura que esta entrada de datos cumple con ciertos criterios para guardarse.
  - **¿Qué diferencia hay entre una relación Master Detail y Lookup?**
    * _Master-Detail_ es una relación de dependencia fuerte entre registros, con control de permisos y eliminación en cascada.
    * _Lookup_ es una relación más flexible, sin dependencia total entre registros.
  - **¿Qué es un Sandbox?** 
    * Es un entorno de pruebas aislado de producción donde los desarrolladores pueden realizar tests sin afectar los datos reales.    
  - **¿Qué es un ChangeSet?**
    * Es una colección de cambios que se pueden enviar de un entorno de Salesforce a otro.   
  - **¿Para qué sirve el import Wizard de Salesforce?**
    * Sirve para importar datos en masa a Salesforce desde archivos   
  - **¿Para qué sirve la funcionalidad Web to Lead?**
    * Es para capturar automáticamente prospectos de un formulario web y crear registros de los clientes potenciales (_leads_) en Salesforce.   
  - **¿Para qué sirve la funcionalidad Web to Case?**
    * Es capturar solicitudes de soporte desde un formulario web, creando casos automáticamente en Salesforce para su seguimiento.   
  - **¿Para qué sirve la funcionalidad Omnichannel?**
    * Es para gestionar y asignar solicitudes de clientes desde distintos canales como, chat y correo electrónico, a los agentes disponibles para mejorar la eficiencia del soporte.    
  - **¿Para qué sirve la funcionalidad Chatter?**
    * Es una herramienta de chat en Salesforce que permite a los empleados enviar mensajes, compartir archivos y trabajar en equipo dentro de la plataforma.
   
#### Conceptos generales   


### Ejercicio 7  

































 

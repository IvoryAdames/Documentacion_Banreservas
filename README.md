# Documentacion_Banreservas
Documentación del proyecto realizado en C# y SQL Server

# Manual de instalación 
Para poder llevar a cabo este proyecto instalé SQL Server 2019 Developer para Windows de 64 bts la cual es una herramienta gratuita que me permite trabajar con las bases de datos sin tener que estar en un entorno de producción.
Luego instale Visual Studio 2022 Community de Microsoft para Windows de 64 bts, con todas sus librerías para poder trabajar en C#.

Aquí se encuentran los link para realizar las descargas:
* https://www.microsoft.com/es-es/sql-server/sql-server-downloads
* https://visualstudio.microsoft.com/es/

# Descripción del proyecto
El programa consistió en realizar una aplicación de escritorio que pudiera conectarse a la base de datos y que le permitiera al usuario poder consultar, actualizar, eliminar y por supuesto guardar.
Este le va a permitir al usuario ingresar un nuevo id, colocar su nombre y poner su fecha de nacimiento para que se almacenen en la base de datos.

# Propósito
El programa se encarga de buscar una forma más eficiente y de fácil acceso para que el usuario pueda ingresar a la base de datos sin ningún problema y pueda trabajar en ella desde la aplicación.

# Alcance
En este proyecto se realiza la creación de una aplicación que se conecte con la base de datos creada en SQL Server para almacenar datos. En este proyecto los procesos que se quiere alcanzar para que haga el trabajo requerido son:
* Consultar la tabla de la base de datos.
* Actualizar la información que se encuentre en la base de datos.
* Guardar la información que ingrese el usuario a la base de datos.
* Eliminar dicha información si así lo desea el usuario.

# Requisitos fundamentales
* La aplicación le va a permitir al usuario entrar desde cualquier navegador, digace Windows, MacOs o Linux.
* La aplicación le va a permitir ver la tabla desde la app.
* La aplicación le va a permitir al usuario ingresar un id.
* La aplicación le va a permitir al usuario colocar su nombre.
* La aplicación le va a permitir al usuario poner su fecha de nacimiento.
* La aplicación permite que todos los que descarguen el programa pueden usarlo sin ningun problema.

# Requisitos no fundamentales
* El programa debe permitir que todos los datos se guarden cuando el usuario ingrese uno.
* El programa debe de buscar en las columnas los nombres solicitados por el usuario.
* El programa debe funcionar sin ningún problema cuando el usuario quiera actualizar algún dato.
* El programa debe de eliminar la columna completamente de la base de datos si el usuario lo solicita.
* El programa debe de tener los botones de minimizar y cerrar funcionando correctamente.

# Estructura DB
                 Persona  
    ---------------------------------
      ID nvarchar(15) primary key,     <-- Este seria para id con su clave primaria.
      Nombre nvarchar(100) not null,   <-- para el nombre del usuario.
      Fecha_De_Nacimiento date         <-- para la fecha de nacimiento del usuario.
    ---------------------------------

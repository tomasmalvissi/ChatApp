#CHAT APP
Esta aplicacion es un chat en tiempo real para usuarios registados. Esta desarrollada en Blazor WebAssembly y .NET 5, utilizando componentes como Signal R, Identity Server, MudBlazor.


###Objetivos de la Aplicacion:
  * Crear una cuenta.
  * Iniciar sesión.
  * Chatear con otros usuarios.
  * Persistencia de mensajes.
  * Cerrar sesión.
 
 
###Pre Requisitos:
  *.NET 5 instalado.
  
  
###Para Empezar:
Para ejecutar este proyecto, luego de clonarlo, es abrir la Packets Manager Console y ejecutar el comando "update-database".
Este lo que hace es crear la base de datos para que funcione.


###Objetivo:
El fin con el que se desarollo esta aplicacion es para presentar ante nuestros tutores de Kinetic, un proyecto con integraciones "piolas". En este caso se realizo una investigacion sobre el lenguaje Blazor WebAssembly, el uso e integracion de Signal R, Identity Server y MudBlazor. 

###Desarrollo:
Lo primero que se realizo fue crear un proyecto web Blazor WebAssembly, hosteado en ASP.NET y Autenticacion de tipo "Individual Accounts".
Luego se instalo los Packages necesarios para las integraciones y funcionalidades. 
Se creo el modelo de Mensaje y Usuarios. También, se añadio la migracion correspondiente para hacer el despliegue de la base de datos.
A continuacion se añadió los modelos necesarios para poder utilizar Signal R y las funcionalidades en tiempo real.
Se desarrollo el controlador de chat, con todas las funcionalidades, para luego consumirlo en el lado del cliente.
De la mano de MudBlazor, se realizo la Interfaz de todo el proyecto.

###Funcionalidades:
#####*Realizadas:
  *UI Responsive desing.
  *Notificacion de Nuevo mensaje.
  
#####*Faltantes:
  *Foto de perfil en usuarios.
  *Buscar mensajes.
  *Destacar mensaje.

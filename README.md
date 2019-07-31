# WSEnvioEmail
Envio de email con archivos adjuntos por medio de SMTP

Cuando se requiere enviar un correo desde una aplicación debemos usar un servidor de correos SMTP(o otros), existen un servidor de correos de Google gratis que podemos usar y solo debemos configurar en la aplicación sus parámetros.
Pero debemos tener claro la diferencia entre una aplicación Web y una aplicación Escritorio.
Aplicación Escritorio: esta aplicación no corre por medio de un navegador entonces las peticiones que salen básicamente  lo realiza el host del computador.
Aplicación Web: esta aplicación corre por medio de un navegador  y esta aplicación esta unida a una aplicación que hace de cara a las peticiones  que es el Glassfish(Servidor de aplicaciones)  en esta deben generar configuraciones que formaran parte de la aplicacion.
Por ejemplo si tienes este error en tu aplicación:
Ya creas tu web services de envio de correos y tienes estas configuraciones  y no funciona el envio de correos es debido a que es un aplicación web 


Debes configurar estas propiedades en el glassfish y llamar a estas propiedades y esto es de igual manera mas efectivo, ejm. Por alguna razón cambias el host del SMTP solo debes entrar en el glassfish y modificarlo, y no entrar en el código y modificar.


Estas configuraciones harán que funcione correctamente tu aplicación.

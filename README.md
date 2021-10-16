# Python-KeyLogger
Un simple KeyLogger que soporta el envio de registros por gmail o puede guardarlos localmente =]

**El script escucha las pulsaciones de teclas en segundo plano, cada cierto intervalo los guarda en un archivo de texto o puede enviar el registro por email**

Debes instalar el modulo __keyboard__

# Enviar keylog por gmail
1. Cambiar los parametro de la linea 7 y 8 (ingresar datos validos)
2. Activar el **Acceso a aplicaciones menos seguras** en la configuracion de la cuenta de Google (debido a que inicia sesion usando smtplib)
3. Desactivar la autenticacion en pasos

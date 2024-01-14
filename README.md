## MicroClase 
Aplicacion NodeJs con MongoDB

# Comandos para iniciar proyecto
Ejecutar tu aplicación:
    node app.js

# Comandos para frenar proyecto
Abre terminal y ejecuta el siguiente comando para detener cualquier proceso que esté utilizando el puerto 3000:
    fuser -k 3000/tcp
Otra alternativa sería usar el comando kill:
    kill $(lsof -t -i:3000)

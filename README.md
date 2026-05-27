# Unidad3_node
# 1.- Crear el proyecto en node

```
npm init -y
```

# 2.- Instalar Express

    npm install express

# 3.- Crear estructura de carpetas para el proyecto:
    -Primero definimos  la carpeta madre(src)
    -Crear el Main de la aplicacion, que es el app.js
    -Creamos dos carpetas, una es para el ruter(definir 
    rutas) y la otra es para los middlewares(puente)
    src/
    ---app.js <- Este es el main de la aplicacion
    ---routes/
            ---users.js
    ---middlewares/
        ---logger.js


# 4.-Creacion de Logger.js
    Creamos el puente de la aplicacion.

    Logger.js

# 5.-Conexión de una ruta
    Crearemos un usuario con datos parseados (Meterlos a la mala) en la ruta.
    La ruta la usaremos para manejar las URL.

    users.js

# 6.- Creacion del Main
    Definimos el cerebro de la aplicacion
    
    app.js
# 7.-
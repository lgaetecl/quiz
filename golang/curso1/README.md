# Ejercicio Prueba

Crear un Microservicios (MS) que realice lo siguiente:

- Exponga el recurso llamado **/factorial** y que este endpoint gatille una función. Este método deberá recibir el siguiente json

```json
{
    "numero": 5
}
```

- La función que se gatillara con el handler deberá calcular el factorial del número que entro en el cuerpo del json.
- Una vez calculado el factorial se deberá enviar el siguiente json como respuesta

```json
{
    "mensaje": "el factorial de 5 es 120"
}

```

> Consideraciones y recomendaciones:
> - Puede usar echo o cualquier framework o libreria de routas
> - Puede dejar todo el código en un archivo .go
> - No es necesario programar los Test

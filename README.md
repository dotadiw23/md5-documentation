# MD5-documentation


## ¿Qué es?

Es un protocolo criptográfico que se usa para autenticar mensajes y verificar el contenido y las firmas digitales. Está basado en una función hash que verifica que un archivo que ha enviado coincide con el que ha recibido la persona a la que se lo ha enviado. Su principal uso actulamente es para la autenticación.

## ¿Cómo funciona?

El algoritmo de hashing MD5 se encarga de convertir el fichero en una cadena de 32 caracteres independientemente de la longitud original del mismo. El cambio de un solo bit en el fichero original implicaría a su vez que al menos la mitad del hash también lo haga. 

## ¿Cómo usar?

En una terminal, ejecute el siguiente comando:
```
md5sum <nombre_del_fichero>
```
Por consola obtendrá algo como esto:
```
e912a84a6329e662207817cb2daf79e3 <nombre_del_fichero>
```

## Aplicaciones



## Referencias

- http://md5deep.sourceforge.net/start-md5deep.html#basic
- https://www.avast.com/es-es/c-md5-hashing-algorithm

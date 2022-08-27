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

- ### Almacenamiento de contraseñas.
El algoritmo se puede usar generar de una contraseña y almacenar dicho hash en base de datos. Cuando el usuario se autentica en el sistema la contraseña en plano es verificada con el hash almacenado en la base de datos; De esta forma se evita que alguna persona con permisos de lectura sobre la base de datos pueda conocer las contraseñas reales de los usuarios.
- ### Verificar integridad de ficheros.
Cuando un proveedor de un fichero expone lo expone para uso general puede publicar tambien el hash de su fichero para que los usuarios que lo descargan puedan verificar la integridad de el fichero descargado.

## Referencias

- http://md5deep.sourceforge.net/start-md5deep.html#basic
- https://owasp.deteact.com/cheat/cheatsheets/Password_Storage_Cheat_Sheet.html
- https://cheatsheetseries.owasp.org/cheatsheets/File_Upload_Cheat_Sheet.html
- https://www.avast.com/es-es/c-md5-hashing-algorithm

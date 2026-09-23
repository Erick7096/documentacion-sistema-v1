# Especificación de Secuencia: Autenticación de Usuario[cite: 2]

## 1. Contexto del Flujo[cite: 2]
Se describe la interacción temporal entre la interfaz móvil, la API backend y la base de datos para la validación de credenciales.

## 2. Diagrama UML de Secuencia[cite: 2]
![Diagrama de Secuencia Autenticacion](../assets/secuencia_autenticacion.png)

## 3. Detalle de los Pasos[cite: 2]
1. El usuario ingresa sus credenciales en la aplicación.
2. La aplicación envía una solicitud HTTP POST al servidor.
3. El servidor valida la información consultando la base de datos.
4. La base de datos responde con los datos del usuario.
5. El servidor genera y retorna un token de sesión `200 OK`.
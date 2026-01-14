## 1️⃣ ¿Qué es un protocolo?

Un **protocolo** es un conjunto de reglas que indica:

* Cómo enviar un mensaje
* Cómo recibirlo
* Qué hacer si algo falla


## 2️⃣ ¿Por qué Internet necesita protocolos?

En Internet:

* Se comunican millones de computadoras
* Son de marcas diferentes
* Usan sistemas distintos
* Están en países distintos

👉 Los protocolos aseguran que **todas hablen el mismo idioma**.


## 3️⃣ Cómo viaja la información por Internet

Cuando se envía información:

* Los datos **no viajan completos**
* Se dividen en **paquetes pequeños**
* Cada paquete viaja por su cuenta

Durante el viaje, los paquetes pueden:

* Llegar **desordenados**
* Llegar **incompletos**
* **Perderse**

👉 Para manejar estos problemas existen protocolos como **TCP y UDP**.



## 🚚 TCP (Transmission Control Protocol)

**TCP** es el protocolo que prioriza la **seguridad y el orden**.

Se encarga de:

* Que los datos lleguen completos
* Que lleguen en el orden correcto
* Volver a pedir los paquetes que faltan

📌 TCP revisa todo antes de dar el mensaje por recibido.

#### 📌 ¿Dónde se usa TCP?

* Páginas web (HTTP / HTTPS)
* Correos electrónicos
* Envío de archivos importantes

👉 Cuando **no se puede perder información**.


## ⚡ UDP (User Datagram Protocol)

**UDP** es el protocolo que prioriza la **velocidad**.

Se encarga de:

* Enviar los datos sin verificar
* No revisar si llegaron todos
* No reenviar paquetes perdidos

📌 UDP confía en que los datos llegarán.

#### 📌 ¿Dónde se usa UDP?

* Videollamadas
* Streaming
* Juegos online

👉 Cuando **la rapidez es más importante que la perfección**.


### 📦 HTTP (HyperText Transfer Protocol)

**HTTP** se encarga de:

* La comunicación entre el navegador y el servidor web
* Pedir y recibir páginas web

Ejemplo:

* El navegador pide una página
* El servidor responde con la página

👉 HTTP usa el sistema **request → response**.


### 🔒 HTTPS (HTTP Seguro)

**HTTPS** es HTTP pero:

* Con información cifrada
* Más segura
* Protege datos

📌 Es el protocolo que se usa hoy en casi todos los sitios web.
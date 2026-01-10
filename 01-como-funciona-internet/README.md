## 1️⃣ ¿Qué es Internet?

Internet es una red global de computadoras y dispositivos conectados entre sí que se comunican usando protocolos.

Aunque muchas personas piensan que Internet funciona principalmente por satélites, **la mayor parte del tráfico no viaja por el aire**.

Funciona principalmente gracias a **cables de fibra óptica**, muchos de ellos **submarinos**, que:

- Cruzan océanos completos 🌊
- Conectan continentes 🌍
- Transportan datos como pulsos de luz
 
**📌 Dato importante:**

> Más del 95% del tráfico mundial de Internet viaja a través de cables submarinos.


## 2️⃣ ¿Qué pasa cuando te conectas a Internet?

Cuando te conectas a Internet ocurre lo siguiente:

1. Tu dispositivo se conecta a un **ISP** (Proveedor de Internet).
2. El ISP te asigna una **dirección IP**.
3. A partir de ese momento puedes **enviar y recibir datos** desde cualquir parte del mundo.


## 3️⃣ ¿Qué es una dirección IP?

Imagina una ciudad donde todas las casas existen, **pero ninguna tiene dirección**. Sería imposible enviar una carta.

En Internet pasa lo mismo. Por eso **cada dispositivo tiene una dirección única**, llamada **dirección IP.**

Las computadoras usan direcciones IP para saber **a dónde enviar la información**.

Ejemplo de dirección IP:

```bash
192.168.2.10
```

Y como los humanos **no somos buenos memorizando números**. Aquí entran en juego los dominios 👇


## 4️⃣ ¿Qué es un dominio?

Un dominio es un **nombre fácil de recordar** que representa una **dirección IP**.

Las computadoras no entienden nombres como `google.com`, ellas se comunican usando números (IP).

Ejemplo:

```bash
google.com → 173.194.121.32
```

Gracias a los dominios, no necesitamos memorizar direcciones numéricas.


## 5️⃣ ¿Qué es DNS y por qué es tan importante?

DNS significa **Domain Name System** (Sistema de Nombres de Dominio).

Su función es **traducir dominios en direcciones IP**.

Convierte esto:

```
google.com
```

En esto:

```
142.250.72.14
```


### 🔄 Flujo DNS simplificado

1. Escribes `google.com` en el navegador.
2. Tu computadora pregunta a un **servidor DNS** cuál es su IP.
3. El DNS responde con la dirección IP.
4. Ahora tu computadora ya sabe a qué servidor conectarse.


## 6️⃣ ¿Qué es un servidor?

Un **servidor** es una computadora que:

* Está siempre encendida.
* Escucha peticiones de otros dispositivos.
* Responde enviando datos.

Ejemplos de lo que puede enviar:

* Páginas web
* Imágenes
* Videos
* APIs


## 7️⃣ El viaje completo cuando visitas un sitio web

Este es el flujo real que ocurre cuando visitas un sitio:

1. Escribes `https://google.com`.
2. El navegador consulta al DNS.
3. El DNS devuelve la IP.
4. El navegador envía una petición al servidor.
5. La petición viaja por routers y cables de fibra óptica (incluidos cables submarinos).
6. El servidor recibe la petición.
7. El servidor responde con archivos.
8. El navegador interpreta el contenido.
9. Ves la página en pantalla.

🎯 **Eso es Internet funcionando**.


## 8️⃣ Protocolos: las reglas de Internet

Para que todo esto funcione, existen reglas que todos los dispositivos respetan:

* **IP** → identifica dispositivos en la red.
 * **TCP** → asegura que los datos lleguen completos y en orden.
* **HTTP / HTTPS** → Permite la comunicación entre navegador y servidor.

👉 Sin protocolos, Internet no funcionaría.


## 📚 Recursos recomendados

- 🔗 [Mapa interactivo de cables submarinos](https://www.submarinecablemap.com/)

- 📖 [MDN – ¿Cómo funciona Internet?](https://developer.mozilla.org/es/docs/Learn_web_development/Howto/Web_mechanics/How_does_the_Internet_work)
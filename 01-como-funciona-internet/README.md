
## ¿Qué pasa cuando buscamos una página web?

Ejemplo: 

    Escribes www.google.com

	1.	Tu dispositivo pregunta:“¿Dónde está google.com?”
	2.	Entra en acción el DNS: El DNS es como la agenda telefónica de Internet.
	•	Convierte “google.com” en un número (IP) Ejemplo: 142.250.190.14
	3.	Con esa dirección, tu dispositivo:
	•	Envía una petición al servidor de Google
	•	La información viaja por cables, fibra óptica o satélites
	4.	El servidor responde:
	•	Envía la página web
	•	Tu navegador la muestra

⏱️ Todo esto pasa en milésimas de segundo.

---

## 1️⃣ ¿Qué es Internet?

Internet Es un sistema que conecta computadoras y dispositivos en todo el mundo para que puedan comunicarse entre sí usando reglas comunes.

La mayoría de Internet funciona gracias a:

### 🌊 Cables submarinos

* Estos son cables de fibra óptica que cruzan océanos completos que transportan datos como pulsos de luz.

    📌 Dato interesante: **Más del 95% del tráfico de Internet mundial viaja por cables submarinos**.


## 4️⃣ ¿Qué pasa cuando te conectas a Internet?

1. Tu dispositivo se conecta a un **ISP** (Proveedor de Internet)
2. El ISP te asigna una **dirección IP**
3. Ya puedes enviar y recibir datos


## 5️⃣ ¿Qué es una dirección IP?

Imagina una ciudad donde todas las casas existen, pero **ninguna tiene dirección**.
Sería imposible enviar una carta.

En Internet pasa lo mismo. Por eso **cada computadora tiene una dirección única**, llamada **dirección IP**.

Las computadoras usan direcciones IP para saber **a dónde enviar la información**.

```bash
# Ejemplo de IP:
192.168.2.10
```

Y como los humanos **no somos buenos memorizando números**. Aquí entra el dominio 👇

---

## Dominios

Un dominio es simplemente un **alias** (un nombre fácil de recordar) que representa una **dirección IP**.

Las computadoras no entienden nombres como `google.com`, ellas se comunican usando números (direcciones IP).

Por ejemplo: `google.com = 173.194.121.32`

Cuando escribimos un dominio como `google.com` en el navegador, ocurre lo siguiente:

1. El navegador pregunta a un **servidor DNS** cuál es la IP de ese dominio
2. El DNS responde con la dirección IP correspondiente
3. Con esa IP, el navegador ya sabe a qué servidor conectarse

Gracias a los dominios, **no necesitamos memorizar números**, solo nombres fáciles de recordar.

## 7️⃣ ¿Qué es DNS y por qué es tan importante?

DNS = **Domain Name System**

Es como la **agenda telefónica de Internet**.

Convierte esto:

```
google.com
```

En esto:

```
142.250.72.14
```

### 🔄 Flujo DNS simplificado

1. Escribes `google.com`
2. Tu computadora pregunta: "¿qué IP es esta?"
3. El servidor DNS responde con la IP
4. Ahora ya sabe a dónde ir

---

## 8️⃣ ¿Qué es un servidor?

Un **servidor** es una computadora que:

* Está siempre encendida
* Escucha peticiones
* Responde con datos

Ejemplos de lo que puede enviar:

* Páginas web
* Imágenes
* Videos
* APIs

---

## 9️⃣ El viaje completo cuando visitas un sitio web

Este es el flujo REAL:

1. Escribes `https://google.com`
2. El navegador consulta al DNS
3. DNS devuelve la IP
4. El navegador envía una petición al servidor
5. La petición viaja por routers y cables submarinos
6. El servidor recibe la petición
7. El servidor responde con archivos
8. El navegador interpreta el contenido
9. Ves la página

🎯 **Eso es Internet funcionando**.

---

## 🔟 Protocolos (las reglas de Internet)

Para que todo esto funcione existen reglas:

* **IP** → identifica dispositivos
* **TCP** → asegura que los datos lleguen completos
* **HTTP / HTTPS** → comunicación web

👉 Sin protocolos, Internet no funcionaría.

## 📚 Recursos recomendados

- 🔗 [Mapa de cables submarinos interactivo](https://www.submarinecablemap.com/)
- 📖 [Lectura: MDN – ¿Cómo funciona Internet?](https://developer.mozilla.org/es/docs/Learn_web_development/Howto/Web_mechanics/How_does_the_Internet_work)
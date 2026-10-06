<!-- Fuente: 04-seminario-ia-profesion/diseno.md (plan E1) + material/mitos.md + material/demo-facilitador.md (guion E1).
     Fundamentos: Wilkinson (la IA no programa) · Romero (rutas que se refuerzan) · Huntley (el oficio se abarató, el acceso no) · Minsky (violín) · Naur en notas del acuerdo.
     Fragments: las listas se fragmentan solas (animateLists en index.html); los párrafos sueltos llevan
     el comentario .element en línea propia al final del texto (pegado al texto, fragmenta el negrita interna).
     No usar data-fragment-index: en reveal los fragmentos con índice aparecen ANTES que los sin índice.
     El orden de aparición es el orden del documento. -->

<section class="title" id="portada">

# IA en tu profesión

## Encuentro 1 — Fundamentos

mar 6 oct · 18:30–20:30 · Biblioteca Popular de Suipacha

<p class="subtitle">Seminario de 4 encuentros</p>

NOTES:
[0:00-0:10] Bienvenida. Presentación de un minuto: nombre, a qué te dedicas.
Explicar el formato: 4 martes, 2 horas, siempre con práctica sobre TU caso real.

---

## Quién soy

**Sasha Kielbowicz**

- Estudié Física en la UBA <!-- .element: class="fragment" -->
- Quant Dev en Axioma <!-- .element: class="fragment" -->
- Líder Técnico en Mercado Libre — Tecnología de Finanzas Corporativas <!-- .element: class="fragment" -->
- AI Engineer en AstraZeneca <!-- .element: class="fragment" -->
- Fundé Phorma.sh <!-- .element: class="fragment" -->
- Vivo en Suipacha desde 2025 · trabajo con IA a diario <!-- .element: class="fragment" -->

NOTES:
[0:05-0:08] Después de las presentaciones del grupo. Un renglón por ítem,
sin detalle de empresas salvo que pregunten: la idea es credibilidad en un
vistazo — estudio, industria y el proyecto propio (Phorma.sh es de donde
sale el material de este seminario). Materiales publicados: charlas.saxa.xyz.

---

## El plan de este encuentro

- **Arranque (10')** — cómo la usás hoy, y parejas
- **Ejercicio (5')** — completen la frase
- **El acuerdo (10')** — el asistente · va a la pizarra
- **Fundamentos (15')** — el chat es como un GPS · el material cambió (MDF) · el acceso cambió
- **Contexto (5')** — cuanto más contexto, más fallas
- **Mitos del mercado local (10')** — lo que se dice vs lo que pasa
- **Puesta en común (10')** — la misma pregunta, dos resultados
- **"Suena terrible" (5')** — aprender el instrumento
- **Tu turno (40')** — primer pedido útil sobre tu caso real
- **Cierre (10')** — qué pediste, qué falló, qué corregiste

NOTES:
[0:00-0:10] Presentar el cronograma y marcar que la única regla es: nadie se
va sin algo que pueda usar en su trabajo esta semana.

---

## Arranque: ¿cómo la usás hoy?

Levantá la mano:

- **A** — uso un chat de IA, pero solo para consultas sueltas
- **B** — lo uso en mi trabajo, alguna vez por semana

Ahora armamos parejas: quien más la usa, con quien menos.
<!-- .element: class="fragment" -->

NOTES:
[0:00-0:05] La clasificación de la encuesta previa, ahora en vivo:
cada una cuenta su letra.
Armar las parejas y dejarlas fijas para los ejercicios de todo el seminario.

---

## Ejercicio: completen la frase

<p class="juego">A las 10 de la ...</p>

- Un turno por persona — que siga la frase <!-- .element: class="fragment" -->
- ¿Hay una única continuación correcta? <!-- .element: class="fragment" -->
- Muchas pueden servir — unas son **más probables** que otras <!-- .element: class="fragment" -->

NOTES:
[0:10-0:15] Tres o cuatro turnos, con personas distintas. Si alguien repite
lo que ya se dijo, pedir otra. No explicar todavía por qué: la explicación
viene en el slide del GPS. Dejar flotando la sensación de "hay muchas
continuaciones posibles".

---

## El acuerdo: el asistente

- La IA es una **herramienta que produce texto en serie, sin cansarse**
- **Delegás la redacción**, no el trabajo: no "trabaja por vos"
- El texto que produce es un borrador; **nunca se envía sin tu revisión**
- Revisar no es leerlo todo: es **poder pedir explicación**

**Va a la pizarra — queda todo el seminario.**
<!-- .element: class="fragment" -->

NOTES:
[0:15-0:25] Dibujar el acuerdo en la pizarra: vos ↔ asistente. Todo encuentro
vuelve acá: qué delegás, qué verificás, qué das por bueno vos.
Naur (La programación como construcción de teorías): el modelo no construye
la teoría del problema — vos la tenés o la construís. Escribir código sin
entender ya existía (copiar y pegar de foros, plantillas de otros); lo nuevo
no es eso. Frase de pizarra: **"lo que no se delega: la teoría del problema"**.
Aclarar "competente": compite en fluidez, no en verdad (entra en Fundamentos).
Huntley (legible→explicable): 40 años de informática hechos a la medida de
alguien que lee, escribe y opera; hoy el criterio no es que el borrador se
entienda de una pasada, sino que sea EXPLICABLE: que puedas interrogarlo.
Práctica concreta (probar con la salida mala de El Tornillo):
"¿por qué ese precio? ¿de dónde sacaste el dato?" — pedir explicación es
cómo se revisa un borrador que no se puede leer entero, y es el contrapeso
directo al cuento del asistente complaciente: obligarlo a justificar contra
tus datos. Color del post original: un código ilegible traducido "para mi
hija" al mismo tiempo que se explica — el chat abstrae legibilidad; ejemplo
adaptado a casos de oficios.

---

## El chat es como un GPS

Elijan dos puntos de la ciudad: ¿cuánto tarda el viaje? ¿por dónde va?
<!-- .element: class="fragment" -->

- Nadie recorre la ruta antes de opinar: cada una estima con **lo que vio** <!-- .element: class="fragment" -->
- El chat tampoco la recorre: elige la **ruta más probable** de su entrenamiento <!-- .element: class="fragment" -->
- Está calibrado para **darte una respuesta que te sirva** — sale seguro y de acuerdo <!-- .element: class="fragment" -->
- **Viaje corto**: la estimación sale bien. **Viaje largo**: el error se acumula <!-- .element: class="fragment" -->

Y por eso a veces el texto no corresponde con la realidad: tus precios, tus normas y tus
planillas **no están en su mapa**.
<!-- .element: class="fragment" -->

NOTES:
[0:25-0:30] Unir con el ejercicio: "A las 10 de la..." también era elegir entre
continuaciones probables. Dos o tres estimaciones de la ruta, con personas
distintas; comparar. Wilkinson: "la IA no programa". Romero: cada respuesta
se elige al azar entre millones de rutas; el entrenamiento refuerza las que
llegaron bien — no conoce la ciudad, conoce el historial de calificaciones.
Por eso el GPS manda al lago CON CONFIANZA. La distancia juega el papel del
contexto: a más distancia (más texto), más chance de perder el rumbo —
semilla del slide siguiente. Contrapeso: verificar (el acuerdo) y dar
contexto (E2). Ancla para el ejemplo de El Tornillo.

---

## El material sobre el que trabajamos cambió

Aparecen el **MDF y la melamina** en la carpintería: más homogéneo,
fácil de trabajar — y **menos resistente** que la madera de árbol.
<!-- .element: class="fragment" -->

Con la IA cambió el **material** del que se hace el trabajo de pensar:
<!-- .element: class="fragment" -->

- **Barato** — borradores en serie, ilimitados, sin quejarse
- **Débil** — se deforma si no lo verificás: **todo lo que produce el chat se revisa antes de aprobar**

NOTES:
[0:30-0:35] No es "tinta más barata": es otro material con otra resistencia.
La debilidad del MDF no lo hace inútil — cambia qué construís con él y
qué no. Igual con la IA: qué le delegás y qué das por bueno vos (el acuerdo).
Preguntar al grupo: ¿quién trabaja con MDF o melamina? (oficios locales).
Generalización (en el guion, fuera del slide): igual que el aluminio o el
plástico — sale de una infraestructura gigante, pero después permite
millones de cosas imposibles a mano.

---

## El acceso cambió

- Hace 10 años: para que una computadora resuelva algo de tu trabajo,
  había que programarla — **oficio de unos pocos**
- Hoy el software se **abarató**: si sabés explicar lo que necesitás,
  lo podés construir — aunque nunca hayas programado

*Un sistema de turnos, una planilla de cuotas, la página de tu negocio:
todo eso es software.*
<!-- .element: class="fragment" -->
Por eso este seminario no es de sistemas: **es de tu profesión**.
<!-- .element: class="fragment" -->

NOTES:
[0:35-0:40] Cierre del bloque de fundamentos. Aterrizar software en ejemplos
locales: sistema de turnos del consultorio, planilla de cuotas del crédito,
la página o el catálogo del negocio. Hace 10 años eso salía con
presupuesto de encargo (contratar a un programador) o se arreglaba a mano;
hoy se empieza con un chat y el caso propio. El cambio es de ACCESO:
expresar lo que necesitás ya alcanza para empezar. Puerta al slide de
contexto y después a los mitos.

---

## Cuanto más contexto, más fallas

- No es tu impresión: se midió en 18 modelos — a más texto de entrada,
  más fallas, incluso en tareas simples (Chroma, 2025) <!-- .element: class="fragment" -->
- Como el viaje largo: cada detalle de más suma chance de perder el rumbo <!-- .element: class="fragment" -->

Regla práctica: pedidos cortos, chats nuevos, solo el material que importa.
<!-- .element: class="fragment" -->

NOTES:
[0:40-0:45] Chroma, "Context Rot" (Hong, Troynikov, Huber, jul 2025):
18 modelos; la prueba clásica del "aguja en el pajar" es demasiado simple
y oculta la caída — en tareas realistas la tasa de fallas sube con la longitud.
No espantar: la solución no es no usar contexto (E2 es justamente dar
contexto), es dar el contexto RELEVANTE y no tirar el expediente entero.
Conexión con la distancia del viaje: lo acumulado pesa.

---

## Mitos del mercado local

---

## Mito 1 — "La IA es solo para la gente de sistemas"

Quien más la usa hoy no trabaja en tecnología: son estudios, comercios y
distribuidores de barrio, para el trabajo administrativo que se repite —
presupuestos, resúmenes, conciliaciones, listas de precios.

> No hace falta ser de sistemas: hace falta tener **una tarea que se repita**.

---

## Mito 2 — "La IA hace todo sola"

La IA produce borradores; **ninguno sale sin tu aprobación**.

El pedido fiscal, la escritura o el presupuesto pasan por tus ojos antes
de salir. La responsabilidad profesional no se delega: **quien aprueba el
borrador sos vos**.

---

## Mito 3 — "Es un riesgo que mi negocio no se puede dar"

El riesgo no es la IA: es usar **el chat equivocado para el dato equivocado**.

Regla simple, por ahora: datos personales, fiscales y de clientes,
**afuera de los chats gratuitos**. La tabla completa, en el último encuentro.

---

## Mito 4 — "Primero hay que comprar un software caro"

Para arrancar se usa **lo que ya tenés**: el chat que conocés, tus
planillas, tu lista de precios.

El software es el paso dos — solo si el flujo valió la pena. Eso se mide en el tercer encuentro.

NOTES:
[0:45-0:55] Cada mito con su caso sectorial del material impreso (mitos.md).
El cuento del peritaje de autos entra con el Mito 2 o 3 según el clima del grupo.

---

## Puesta en común: Ferretería El Tornillo

*Caso inventado de barrio — la misma pregunta, dos resultados.*

1. **El pedido (sin contexto):** *"Armate un presupuesto de 20
   metros de caño con codos y pegamento para un baño."*
2. **El pedido (con contexto):** lo mismo, con la lista de precios
   y las condiciones cargadas en el mismo chat

**Al grupo:** ¿qué está mal de la salida mala para El Tornillo?
<!-- .element: class="fragment" -->

NOTES:
[0:55-1:05] Cierre del ejemplo: la diferencia no es que el segundo chat
"piense mejor" — es el contexto. Eso es el encuentro 2. Y la salida buena
tampoco se envía sin revisión: eso es el acuerdo de la pizarra.
Sin wifi: mostrar las capturas impresas (plan B).

---

## "Suena terrible" es parte de aprender

> *Una computadora es como un violín. Pueden imaginar a alguien que prueba
> primero un tocadiscos y después un violín. El segundo, dice, suena
> terrible. Ese es el argumento que hemos escuchado de nuestros humanistas
> y de la mayoría de nuestros científicos de la computación. Los programas,
> dicen, sirven para cosas puntuales, pero no son flexibles. Tampoco lo son
> el violín o la máquina de escribir, hasta que uno aprende a usarlos.*
> — **Minsky**

La primera salida te va a sonar terrible. No es el instrumento:
**todavía no sabés tocarlo**. Para eso son los próximos 40 minutos.
<!-- .element: class="fragment" -->

NOTES:
[1:05-1:08] Minsky como puente a la práctica: la frustración inicial del
taller no es un límite del instrumento, es aprendizaje del instrumento.
Si el grupo viene frustrado por el ejemplo o por la experiencia propia,
esta es la válvula de escape. Puede correrse al cierre si el clima pide
empezar antes a trabajar.

---

## ¿Con qué chat?

Todos gratis, en el navegador, en español:

| Chat | Quién | Dirección |
|:-----|:------|:----------|
| [ChatGPT](https://chatgpt.com/) | OpenAI | [chatgpt.com](https://chatgpt.com/) |
| [Gemini](https://gemini.google.com/) | Google | [gemini.google.com](https://gemini.google.com/) |
| [Claude](https://claude.ai/chat/) | Anthropic | [claude.ai](https://claude.ai/chat/) |
| [Grok](https://grok.com/) | xAI | [grok.com](https://grok.com/) |
| [Qwen](https://chat.qwen.ai/) | Alibaba | [chat.qwen.ai](https://chat.qwen.ai/) |
| [GLM](https://chat.z.ai/) | Z.ai | [chat.z.ai](https://chat.z.ai/) |
| [Le Chat](https://chat.mistral.ai/) | Mistral | [chat.mistral.ai](https://chat.mistral.ai/) |

Para la práctica, cualquiera. Lo que cambia el resultado es el **contexto**, no el chat.

NOTES:
[1:08-1:10] Slide de referencia para el turno práctico: que nadie se quede
sin una ventana abierta. Si el wifi de la biblioteca no alcanza, el dato
del celular anda igual. No hace falta crear cuenta en vivo para nada
obligatorio: quien no abre chat ahora, repite el pedido en casa (plan B
del slide del ejemplo).
Recordar la regla del Mito 3 antes de que empiece la práctica: datos de
clientes y datos fiscales, afuera — para hoy, tareas genéricas (borradores,
listas de precios, resúmenes).

---

## Tu turno: el primer pedido útil

- Elegí **una tarea que se repite** en tu trabajo
- Pedile al chat que la resuelva, **con tu caso real**
- Probalo **en español y en inglés** — compará las dos respuestas
- Anotá **qué falló** en cada intento

40 minutos. Las parejas trabajan juntas.
<!-- .element: class="fragment" -->

NOTES:
[1:10-1:50] Objetivo del producto: un pedido aplicado a un caso real, con la
salida comparada/corregida y anotado qué falló. Pasar por las parejas.
Sin wifi: pedidos y salidas impresos, y cada una lo repite en casa.

---

## Cierre: qué falló, qué corregiste

- ¿Qué pediste?
- ¿Qué falló en la primera respuesta?
- ¿Qué cambiaste?

**Producto de hoy:** tu primer pedido útil, funcionando.
<!-- .element: class="fragment" -->

NOTES:
[1:50-2:00] Pedir a dos o tres personas que cuenten. Reforzar el acuerdo de la
pizarra al cerrar. Anunciar el E2 (mar 13): escribir bien los pedidos —
contexto, formato, iteración.

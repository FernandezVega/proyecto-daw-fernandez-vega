# 01b · Estado del arte (SOTA) de mi proyecto

> **Plantilla.** Se entrega con **H1 el 26-nov-2026**, junto al `01-analisis.md`. Es **obligatorio** y breve: **4-6 páginas**. Aquí estudias qué soluciones, **modelos de negocio** y **herramientas** existen ya para el problema que has elegido, y justificas tus decisiones con ello. Cada apartado indica el criterio de evaluación (CE) que alimenta. Borra los bloques «Guía» al rellenar.

> **Guía.** Calendario: **12-nov** preguntas de búsqueda (apartado 1) · **19-nov** tablas de soluciones y herramientas (apartados 2 y 4) · **26-nov** modelos de negocio, hueco, decisiones, fuentes y entrega (apartados 3, 5-8).
>
> **Reglas.**
>
> - Solo cuenta lo que tiene **enlace y fecha de acceso**.
> - Si usas IA para buscar, **abre cada fuente** y comprueba que existe y dice lo que te cuenta la IA. Puede inventar productos, precios o referencias. Decláralo en la [bitácora de uso de IA](../asistenciaIA/bitacora.md).
> - Usa **solo información pública** de las soluciones que estudias. **Nada** de la empresa de prácticas ni de clientes reales.
> - Compara herramientas con **los mismos criterios**, no por opinión. Salvo razón argumentada, prefiere lo que has visto en el ciclo (Java 21, Spring Boot, SQL).
> - Si algo no lo has podido comprobar, dilo en el apartado 8.

## 1. Problema y preguntas de búsqueda (CE 1c)

*El problema en **una frase**. Después, **3-5 preguntas** que vas a contestar con este documento (por ejemplo: «¿Qué soluciones existen?», «¿Cómo ganan dinero?», «¿Qué tecnologías usan?»). Indica **dónde y cuándo** buscaste (buscadores, tiendas de aplicaciones, repositorios, informes del sector).*

**Problema:** Las empresas que dependen de ser encontradas en internet tienen el problema de que sus clientes ya no las ven ni las citan: sus páginas quedan fuera de Google y de las respuestas de los asistentes de IA, y no saben por qué.

| # | Pregunta | Dónde busqué | Fecha |
|---|---|---|---|
| P1 | ¿Qué soluciones existen ya para analizar el posicionamiento SEO? | En páginas oficiales  de empresas del sector, en IA. [SERANKING](https://seranking.com/es/), [SEMRUSH](https://www.semrush.com) , además de documentación oficial de Google, [SEO-Starter-Guide](https://developers.google.com/search/docs/fundamentals/seo-starter-guide?hl=es)| 2026-11-18
| P2  | ¿Qué precio tienen estos servicios de análisis de posicionamiento? | En las páginas de servicios / productos de las marcas líderes en el sector. Por ejemplo: [Planes y precios SERanking](https://seranking.com/es/subscription.html) | 2026-11-18
| P3 | ¿Qué les falta a estas soluciones para medir también la visibilidad en asistentes de IA (GEO/AEO)? |En blogs especializados, como [SEOINHOUSE](https://www.seoinhouse.es/visibilidad-en-ia-la-cifra-que-el-cliente-nos-pide-no-existe/) , y en IA. | 2026-11-18


## 2. Soluciones existentes (CE 1a, 1c, 2a)

*Tabla de **5-8** soluciones (productos, servicios o proyectos de código abierto) que resuelven total o parcialmente el problema. Incluye alguna **alternativa gratuita o de código abierto** y alguna **no digital** (hoja de cálculo, papel) si existe.*

| Solución | Para quién | Qué hace | Modelo de precio | Enlace y fecha de acceso | Estado |
|---|---|---|---|---|---|
| SE Ranking | Equipos SEO y agencias que gestionan varias webs y clientes | Plataforma SEO todo en uno: posiciones, palabras clave, auditoría, competidores, informes y visibilidad en IA (menciones, AI Overviews, ChatGPT) | Suscripción: Core desde 87,20 €/mes, Growth desde 188,00 €/mes y API desde 25 €/mes; prueba gratis 14 días sin tarjeta | [seranking.com/es](https://seranking.com/es/) — 2026-11-19 | leído |
| Morningscore | Pequeñas empresas que quieren hacer su SEO/GEO o recibir acompañamiento | SEO y GEO: palabras clave, SEO Score, GEO Score sobre 100 prompts, AI Overviews, ChatGPT, salud del sitio con problemas priorizados, backlinks, misiones y plugins para WordPress y Shopify | Suscripción: 49-259 USD/mes (4 planes, según los datos de la página); también orientación 1:1 y gestión del crecimiento; prueba gratis 14 días | [morningscore.io/es](https://morningscore.io/es/) — 2026-11-19 | leído |
| Keyword.com | Agencias SEO en crecimiento, equipos internos y equipos enterprise | Rastreador de posiciones y visibilidad IA: Google, SERP locales, AI Overviews, AI Mode, ChatGPT, Perplexity y Gemini; share of voice, API, MCP e informes en marca blanca | Suscripción por número de keywords: desde 3 $/mes (50 keywords, pago anual; 4 $/mes mensual); visibilidad IA desde 9,80 $/mes por 100 créditos; prueba gratis 14 días | [keyword.com/es](https://keyword.com/es/) — 2026-11-19 | leído |
| Semrush | Empresas, medianas, equipos pequeños, autónomos y agencias | Plataforma SEO y visibilidad en IA (Semrush One): palabras clave, competidores, auditoría técnica, tráfico, contenidos, local, RR. PP. para IA, MCP y API | Suscripción (planes en `/pricing/`); importes: **no lo dice en esta página**. Prueba gratis 7 días | [es.semrush.com](https://es.semrush.com/) — 2026-11-19 | leído |
| Serpstat | Agencias, ecommerce, pequeños negocios, SaaS y medios | Investiga palabras clave, analiza competidores, monitoriza posiciones, audita el sitio, agrupa keywords y ofrece API en Google y Bing (230 países) | Suscripción (planes en `/es/page/pricing-plans/`); importes: **no lo dice en esta página**. Prueba gratis 7 días | [serpstat.com/es](https://serpstat.com/es/) — 2026-11-19 | leído |
| Lighthouse | Desarrolladores y responsables de web que quieren revisar su propia página sin coste | Herramienta de código abierto que audita rendimiento, accesibilidad, SEO y buenas prácticas; se usa en DevTools de Chrome, por línea de comandos, como módulo Node o desde PageSpeed Insights | Gratuito; licencia Apache-2.0 | [developer.chrome.com/docs/lighthouse/overview](https://developer.chrome.com/docs/lighthouse/overview) y [repositorio](https://github.com/GoogleChrome/lighthouse) — 2026-11-19 | leído |

*Figura: comparativa de las soluciones (opcional, un cuadrante o un esquema).*

## 3. Modelos de negocio (CE 1d, 1e)

*Qué **patrones** se repiten en las soluciones del apartado 2 (suscripción, *freemium*, comisión por operación, licencia, publicidad, servicio gratuito o público) y por qué. Describe con un **Business Model Canvas** (opcional; el profesor te da el material) **2-3 casos**. Termina con el modelo que seguiría **tu** proyecto, o qué ahorra o mejora si no es un negocio.*

| Patrón | Soluciones que lo usan | Ventaja | Riesgo |
|---|---|---|---|
| Suscripción por niveles | 5 de las 6: SE Ranking (Core, Growth), Morningscore (Lite a Premium), Keyword.com (por keywords), Semrush y Serpstat (planes) | Ingreso recurrente; el cliente escala según su tamaño | El precio final no es fijo: sube con keywords, usuarios, webs y módulos |
| Prueba gratuita | SE Ranking, Morningscore y Keyword.com (14 días, sin tarjeta); Semrush y Serpstat (7 días) | Entrar sin pagar y mostrar el valor antes de vender | La prueba limita funciones; la página no dice cuántos usuarios convierten |
| Gratuito y código abierto | Lighthouse (gratuito, licencia Apache-2.0) | Coste cero y código auditable; sirve para revisar la propia web | Cubre auditoría técnica, no el seguimiento de posiciones ni los informes; habría que comprobarlo en su documentación |
| Complementos y pago por volumen | SE Ranking (API desde 25 €/mes), Morningscore (créditos de IA por plan), Keyword.com (visibilidad IA desde 9,80 $/mes por 100 créditos), Semrush (módulos de SEO, IA, tráfico…), Serpstat (API) | Pagas por lo que usas; se puede empezar pequeño | El coste depende del volumen real (palabras, prompts, créditos): difícil de estimar |
| Servicio y precio a medida | Morningscore (orientación 1:1 y gestión del crecimiento), Semrush (demo y empresa), SE Ranking (demo y paquete para agencias) | Llega a clientes que no quieren hacerlo ellos | Precio no público: hay que pedirlo; no se puede comparar ni presupuestar sin hablar con cada cliente | 

**Modelo de presencIA:** *freemium*. La primera auditoría de una URL es gratuita —**una por URL, no ilimitada**— para que la empresa vea el informe y su puntuación sin pagar. A partir de ahí, el seguimiento de posiciones, el explorador de keywords, el panel privado y los informes personalizados se cobran con suscripción por niveles y complementos. Ese primer informe gratuito hace de puerta de entrada, en lugar de la prueba de 14 o 7 días que usan las herramientas del apartado 2, que aquí no se ofrece. El precio sigue **pendiente**: depende del tamaño de la empresa y de los servicios contratados, y sin datos de uso no se puede fijar una cifra.

## 4. Herramientas y tecnologías (CE 2a, 2b)

*Para cada decisión técnica importante (lenguaje y *framework*, base de datos, despliegue, autenticación…), compara **2-3 opciones con los mismos criterios**. Marca la que eliges.*

| Decisión | Opción | Madurez | Licencia | Coste | Curva de aprendizaje | Encaje con el ciclo | Elegida |
|---|---|---|---|---|---|---|---|
| Lenguaje y framework | Java + Spring Boot | Activa: la web oficial muestra la versión 4.1.2 ([spring.io](https://spring.io/projects/spring-boot) · 2026-11-19) | Apache-2.0 ([LICENSE](https://github.com/spring-projects/spring-boot/blob/main/LICENSE.txt) · 2026-11-19) | 0 € | Baja: Java es lo que has usado | Sí: es lo que se ha visto en el ciclo | sí |
| Lenguaje y framework | Node.js + Express | Pendiente: no he comprobado su cadencia de versiones | MIT en los dos ([Node.js](https://github.com/nodejs/node/blob/main/LICENSE) y [Express](https://github.com/expressjs/express/blob/master/LICENSE) · 2026-11-19) | 0 € | Alta: JavaScript en servidor no lo has trabajado | No: no es lo del ciclo | no |
| Base de datos | MySQL (Community) | Pendiente: no he comprobado versiones | GPL en la Community; las ediciones Enterprise y Standard son aparte ([mysql.com](https://www.mysql.com/products/community/) · 2026-11-19) | 0 € la Community | Media: SQL ya lo llevas | Sí: SQL en el ciclo | no |
| Base de datos | PostgreSQL | Activa: PostgreSQL 19 publicado ([postgresql.org](https://www.postgresql.org/about/licence/) · 2026-11-19) | PostgreSQL License, «similar a BSD o MIT» ([postgresql.org](https://www.postgresql.org/about/licence/) · 2026-11-19) | 0 € | Media: SQL ya lo llevas | Sí: SQL en el ciclo | sí |
| Despliegue | Docker en un VPS | Docker Desktop se actualiza y las licencias de Docker Engine no cambian ([docs.docker.com](https://docs.docker.com/subscription/desktop-license/) · 2026-11-19) | Docker Desktop: gratis en uso personal, educativo y empresas de menos de 250 empleados y 10 M$; de pago fuera de ahí. Docker Engine sigue siendo de código abierto | Docker: 0 €. El VPS: **pendiente**, falta elegir proveedor | Pendiente: no sé si has usado Docker en el ciclo | Depende: el módulo de despliegue sí entra en el proyecto | sí |
| Despliegue | Hosting compartido | Pendiente: depende del proveedor | No aplica: lo fija el proveedor | **Pendiente**: falta elegir proveedor y plan; no doy una cifra sin mirarla | Baja (opinión): se gestiona con panel | Sí: es la opción habitual del módulo | no |
| Interfaces web | HTML + CSS + JavaScript, sin framework | Pendiente: no hay versión que comprobar, son estándares del navegador | No aplica | 0 € | Baja: es lo que has usado en el ciclo | Sí: «Desarrollo web en entorno cliente (0612)» y «Diseño de interfaces (0615)» | sí |
| Interfaces web | React | Pendiente: no he comprobado su cadencia de versiones | MIT ([LICENSE](https://github.com/facebook/react/blob/main/LICENSE) · 2026-11-19) | 0 € | Media-alta (opinión): añade componentes, estado y una herramienta de compilación | Parcial: el ciclo trabaja JS y DOM, no React | no |
| Interfaces web | Vue | Pendiente: no he comprobado su cadencia de versiones | MIT ([LICENSE](https://github.com/vuejs/core/blob/main/LICENSE) · 2026-11-19) | 0 € | Media (opinión): componentes con plantillas parecidas a HTML | Parcial: mismo motivo | no |
| Autenticación | Spring Security con JWT | Activo: Spring Security es un proyecto de Spring | Apache-2.0 (no he abierto su repositorio; es la licencia de los proyectos Spring) | 0 € | Media-alta (opinión): hay que emitir y validar el token | Sí: Java y Spring | sí |
| Autenticación | Spring Security con sesión y cookies | Activo: igual que la anterior | Apache-2.0 | 0 € | Baja (opinión): lo resuelve el propio framework | Sí: Java y Spring | no |

## 5. Hueco y diferenciación (CE 1e)

*Qué **no cubren** las soluciones del apartado 2 y qué aporta tu proyecto. Es tu **propuesta de valor**, en 3-5 líneas, sin exagerar: si hay soluciones mejores que la tuya para algunos usuarios, dilo.*

Cuatro de las seis soluciones que hemos visto (SE Ranking, Morningscore, Keyword.com y Semrush) incluyen visibilidad en IA; la web de Serpstat no lo menciona y Lighthouse, que es gratis, revisa solo la parte técnica de la página. El hueco no es la función, **es el acceso**: esas plataformas están pensadas para agencias y equipos SEO, se pagan desde el primer mes y el precio sube con keywords, usuarios y créditos.

`presencIA` se dirige a la empresa pequeña que no va a contratar una agencia. Aporta tres cosas: una primera auditoría gratuita (una por URL) para ver el informe antes de pagar; un precio adaptado al tamaño de la empresa; y un trato cercano, con el informe explicado en lenguaje de empresa y no de agencia.

Para una agencia o una empresa grande, Semrush o SE Ranking ofrecen hoy más funciones y están más probadas. La diferencia de `presencIA` es la barrera de entrada, no la potencia.

## 6. Decisiones derivadas (CE 1e, 1f, 2b)

- **Tipo de proyecto:** aplicación web. Ninguna de las seis soluciones del apartado 2 es un producto propio que solo audite y recomiende para una empresa pequeña; las tres que incluyen visibilidad en IA se venden a agencias y equipos SEO. El razonamiento completo está en [`01-analisis.md`](01-analisis.md), apartado 3.
- **Requisitos que salen del estudio:** `RF-01` (auditar y puntuar SEO, GEO y AEO), `RF-03` (explorar palabras clave) y `RF-04` (seguir posiciones) recogen funciones que ya ofrecen SE Ranking, Morningscore, Keyword.com y Serpstat. `RNF-01` y `RNF-03` (una sola pantalla y un informe en lenguaje de empresa) salen del hueco del apartado 5. `REST-02` y `REST-03` recogen el coste del alojamiento y las tecnologías del ciclo. Todos están en [`01-analisis.md`](01-analisis.md), apartado 4.
- **Decisiones técnicas:** Java 21 con Spring Boot para el backend, PostgreSQL como base de datos, HTML, CSS y JavaScript sin framework para la interfaz, Spring Security con JWT para la autenticación y Docker sobre un VPS para el despliegue. La comparación con las alternativas está en el apartado 4 de este documento. **Pendiente:** el registro individual de cada decisión en `decisiones/`, porque esa carpeta todavía no existe.

## 7. Fuentes y calidad (CE 2a)

Cinco fuentes independientes: dos oficiales (INE y ONTSI), un centro de investigación (Pew) y dos privadas que no compiten con las soluciones estudiadas. Google se usa solo para lo que es: la documentación del operador sobre sus propias funciones.

| # | Fuente (enlace) | Tipo | Fecha de acceso | Fiabilidad y por qué |
|---|---|---|---|---|
| F1 | [INE, Encuesta de uso de TIC y comercio electrónico, 1T 2025](https://ine.es/dyngs/Prensa/ETICCE20241T2025.htm) | Oficial, dato primario | 2026-11-23 | Alta: estadística pública con metodología publicada |
| F2 | [ONTSI, Indicadores de uso de IA en España 2025](https://www.ontsi.es/es/publicaciones/indicadores-de-uso-de-inteligencia-artificial-en-espana-2025) | Oficial | 2026-11-19 | Alta: organismo público, aunque el dato se apoya en encuestas propias |
| F3 | [Pew Research Center, clics con y sin resumen de IA (2025-07-22)](https://www.pewresearch.org/short-reads/2025/07/22/google-users-are-less-likely-to-click-on-links-when-an-ai-summary-appears-in-the-results/) | Centro de investigación | 2026-11-19 | Alta: estudio propio con muestra declarada |
| F4 | [BrightLocal, SMB Marketing Report](https://www.brightlocal.com/research/smb-marketing-report/) y [Consumer Search Behavior (2025-04-29)](https://www.brightlocal.com/research/consumer-search-behavior) | Empresa privada del sector | 2026-11-19 | Media: son dos estudios de la **misma editorial**, así que cuentan como **una** fuente independiente, y la empresa vende servicios del sector que estudia |
| F5 | [Google Search Central, AI features](https://developers.google.com/search/docs/appearance/ai-features) | Documentación del operador | 2026-11-19 | Alta para describir qué son las funciones de IA; **baja** como prueba de demanda, porque Google no publica cifras ahí |

## 8. Límites

- **Precios:** Semrush y Serpstat no publican importes en la página que he abierto. Los de SE Ranking, Morningscore y Keyword.com los da su propia web, sin comprobación independiente.
- **Tamaño de las empresas:** ninguna declara plantilla ni facturación. Por eso la columna «Tamaño» del apartado 1 de `01-analisis.md` queda en «no lo dice».
- **BrightLocal:** es una empresa comercial y dos de sus estudios son de la misma editorial. Cuentan como una sola fuente independiente, no como dos.
- **Convocatorias:** no he podido abrir el PDF de SEKUENS/IDEPA, ni los desplegables de requisitos de ENISA, ni el importe del bono del Kit Digital.
- **Coste del despliegue:** el precio del VPS sigue sin cifra; no se ha inventado.
- **Conexión con motores de IA:** no está comprobado que `presencIA` pueda consultar en tiempo real a ChatGPT, Perplexity o Gemini. Está anotado como duda en `00-documentoInicio.md`, apartado 10.

---

## Criterios de evaluación que alimenta este documento (texto literal)

- **1a)** Se han clasificado las empresas del sector por sus características organizativas y el tipo de producto o servicio que ofrecen.
- **1c)** Se han identificado las necesidades más demandadas a las empresas.
- **1d)** Se han valorado las oportunidades de negocio previsibles en el sector.
- **1e)** Se ha identificado el tipo de proyecto requerido para dar respuesta a las demandas previstas.
- **1f)** Se han determinado las características específicas requeridas al proyecto.
- **2a)** Se ha recopilado información relativa a los aspectos que van a ser tratados en el proyecto.
- **2b)** Se ha realizado el estudio de viabilidad técnica del mismo.

> El SOTA **no añade criterios de evaluación**: reúne en un solo sitio lo que 1a-1f y 2a-2b ya piden. La evaluación sigue las listas de cotejo de H1 y H2.

# 01b · Estado del arte (SOTA) de mi proyecto

> **Plantilla.** Se entrega con **H1 el 26-nov-2026**, junto al `01-analisis.md`. Es **obligatorio** y breve: **4-6 páginas**. Aquí estudias qué soluciones, **modelos de negocio** y **herramientas** existen ya para el problema que has elegido, y justificas tus decisiones con ello. Cada apartado indica el criterio de evaluación (CE) que alimenta. Borra los bloques «Guía» al rellenar.

> **Guía.** Calendario: **12-nov** preguntas de búsqueda (apartado 1) · **19-nov** tablas de soluciones y herramientas (apartados 2 y 4) · **26-nov** modelos de negocio, hueco, decisiones, fuentes y entrega (apartados 3, 5-8).
>
> **Reglas.**
>
> - Solo cuenta lo que tiene **enlace y fecha de acceso**.
> - Si usas IA para buscar, **abre cada fuente** y comprueba que existe y dice lo que te cuenta la IA. Puede inventar productos, precios o referencias. Decláralo en [`declaracion-uso-ia.md`](declaracion-uso-ia.md).
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
| Suscripción por niveles | Las 5: SE Ranking (Core, Growth), Morningscore (Lite a Premium), Keyword.com (por keywords), Semrush y Serpstat (planes) | Ingreso recurrente; el cliente escala según su tamaño | El precio final no es fijo: sube con keywords, usuarios, webs y módulos |
| Prueba gratuita y herramientas gratuitas | Las 5: 14 días en SE Ranking, Morningscore y Keyword.com (sin tarjeta); 7 días en Semrush y Serpstat | Entrar sin pagar y mostrar el valor antes de vender | La prueba limita funciones; la página no dice cuántos usuarios convierten |
| Complementos y pago por volumen | SE Ranking (API desde 25 €/mes), Morningscore (créditos de IA por plan), Keyword.com (visibilidad IA desde 9,80 $/mes por 100 créditos), Semrush (módulos de SEO, IA, tráfico…), Serpstat (API) | Pagas por lo que usas; se puede empezar pequeño | El coste depende del volumen real (palabras, prompts, créditos): difícil de estimar |
| Servicio y precio a medida | Morningscore (orientación 1:1 y gestión del crecimiento), Semrush (demo y empresa), SE Ranking (demo y paquete para agencias) | Llega a clientes que no quieren hacerlo ellos | Precio no público: hay que pedirlo; no se puede comparar ni presupuestar sin hablar con cada cliente |

**Modelo de presencIA:** suscripción por niveles con prueba gratuita y complementos, inspirada en las soluciones del apartado 2, pero centrada en empresas pequeñas de ámbito local. El precio se personalizaría según los servicios contratados (auditoría SEO, seguimiento de visibilidad en IA e informes), para que cada empresa pague solo lo que necesita y pueda ampliar después. Al trabajar con un público local también cabe el trato directo y el presupuesto a medida, como en el cuarto patrón. **A día de hoy aún no sé qué precio poner**: dependerá del tamaño de la empresa y de los servicios elegidos, así que no doy una cifra concreta. Esto no elimina el problema de la estimación: sin esos datos no se puede dar un coste único.

## 4. Herramientas y tecnologías (CE 2a, 2b)

*Para cada decisión técnica importante (lenguaje y *framework*, base de datos, despliegue, autenticación…), compara **2-3 opciones con los mismos criterios**. Marca la que eliges.*

| Decisión | Opción | Madurez | Licencia | Coste | Curva de aprendizaje | Encaje con el ciclo | Elegida |
|---|---|---|---|---|---|---|---|
| [RELLENAR: p. ej. base de datos] | | | | | | | |

*Cada decisión importante se convierte en una decisión registrada en [`decisiones/`](decisiones/0000-plantilla.md).*

## 5. Hueco y diferenciación (CE 1e)

*Qué **no cubren** las soluciones del apartado 2 y qué aporta tu proyecto. Es tu **propuesta de valor**, en 3-5 líneas, sin exagerar: si hay soluciones mejores que la tuya para algunos usuarios, dilo.*

## 6. Decisiones derivadas (CE 1e, 1f, 2b)

*Qué consecuencias tiene este estudio en tu proyecto.*

- **Tipo de proyecto elegido** (enlaza con el apartado 3 de [`01-analisis.md`](01-analisis.md)): [RELLENAR]
- **Requisitos que salen del estudio** (con su ID del apartado 4 de `01-analisis.md`): [RELLENAR]
- **Decisiones técnicas** (enlace a cada archivo de `decisiones/`): [RELLENAR]

## 7. Fuentes y calidad (CE 2a)

*Al menos **2 fuentes independientes** (no dos páginas de la misma empresa). Datos oficiales o primarios antes que blogs.*

| # | Fuente (enlace) | Tipo | Fecha de acceso | Fiabilidad (alta / media / baja) y por qué |
|---|---|---|---|---|
| F1 | [RELLENAR] | | | |

## 8. Límites

*Qué **no pudiste comprobar** y qué datos son estimaciones. Una lista corta y honesta es mejor que fingir certeza.*

- [RELLENAR]

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

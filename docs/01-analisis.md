# 01 · Análisis y documentación inicial (RA1)

> **Plantilla.** Se entrega como **H1 el 26-nov-2026**. Cada apartado indica el criterio de evaluación (CE) que evidencia y qué se espera. Borra las notas en cursiva al rellenar.

## 1. Sector y empresas (CE 1a, 1b)
Sector: el del marketing digital y la visibilidad en buscadores. Agrupa a las agencias de publicidad y SEO, a las consultoras de posicionamiento y a las plataformas que analizan cómo aparece una web en Google y en los motores de IA, además de las empresas que hacen ese trabajo con medios propios.

CNAE 7311 · Actividades de las agencias de publicidad · [CNAE-2025 (INE)](https://www.ine.es/daco/daco42/clasificaciones/cnae25/CNAE_2025.pdf) · 2026-11-19 · sin leer

**Importante** `presencIA` no es una agencia. No gestiona campañas ni ejecuta mejoras: audita una URL, puntúa SEO, GEO y AEO y recomienda qué cambiar. Aplicar las mejoras sería un servicio añadido si el proyecto pasara a una empresa real; en su alcance académico, solo audita, genera el informe y recomienda.

*Clasifica **5 o más** empresas del sector por sus características organizativas y el producto o servicio que ofrecen. Describe con detalle **una empresa tipo**: organigrama (un diagrama Mermaid) y funciones de cada departamento.*

| Empresa | Tamaño | Forma | Ámbito | Servicio | Fuente y fecha | Estado |
|---|---|---|---|---|---|---|
| SE Ranking | No lo dice: su web habla de clientes, no de empleados | SER Acquisition Inc. (pie de página) | Internacional: más de 150 países y web en 11 idiomas | Plataforma SEO: posiciones, palabras clave, auditoría y visibilidad en IA | [seranking.com/es](https://seranking.com/es/) · 2026-11-19 | leído |

*Pendiente: completar la tabla con el resto de empresas del apartado 2 de `01b-sota.md` (Morningscore, Keyword.com, Semrush, Serpstat y Lighthouse). De Lighthouse, que no es una empresa sino un proyecto de Google, se dirá «no aplica» en tamaño y forma.*

## 2. Necesidades y oportunidades (CE 1c, 1d)

*Lista **priorizada** de las necesidades más demandadas, con el criterio de priorización y la fuente. Valora las oportunidades de negocio con **al menos un dato cuantitativo** y su fuente.*

**Criterio de priorización:** se ordenan por el número de **fuentes externas** que mencionan la necesidad; las soluciones del apartado 2 de `01b-sota.md` se listan aparte porque muestran oferta, no demanda. En caso de empate manda lo que `presencIA` puede resolver dentro de su alcance (auditoría técnica, informe y recomendaciones).

| # | Necesidad | Soluciones que la ofrecen | Fuentes externas | Nº ext. | Dato cuantitativo | Oportunidad para presencIA |
|---|---|---|---|---|---|---|
| 1 | Saber si aparece en las respuestas de IA | 4: SE Ranking, Morningscore, Keyword.com, Semrush | [ONTSI](https://www.ontsi.es/es/publicaciones/indicadores-de-uso-de-inteligencia-artificial-en-espana-2025) · 2026 · 2026-11-19 · leído<br>[Pew](https://www.pewresearch.org/short-reads/2025/07/22/google-users-are-less-likely-to-click-on-links-when-an-ai-summary-appears-in-the-results/) · 2025-07-22 · leído<br>[BrightLocal SMB 2026](https://www.brightlocal.com/research/smb-marketing-report/) · leído<br>[Google AI features](https://developers.google.com/search/docs/appearance/ai-features) · sin fecha · leído | 4 | 55,2 % de usuarios de internet en España usa IA generativa (ONTSI); clic del 8 % con resumen de IA frente al 15 % sin él (Pew, 2025) | La IA ya resta clics; hay demanda de saber si la empresa aparece |
| 2 | Saber en qué posición aparece en Google | 5: SE Ranking, Morningscore, Keyword.com, Semrush, Serpstat | [BrightLocal Consumer](https://www.brightlocal.com/research/consumer-search-behavior) · 2025-04-29 · leído<br>[BrightLocal SMB 2026](https://www.brightlocal.com/research/smb-marketing-report/) · leído | 2 (misma editorial) | 71 % de consumidores usa Google; solo 22 % de pymes cree que le trae clientes (BrightLocal SMB 2026) | Google sigue siendo el canal principal; la brecha entre confianza y realidad es el hueco |
| 3 | Aparecer en búsquedas locales y Maps | 2: Keyword.com, Semrush | [BrightLocal Consumer](https://www.brightlocal.com/research/consumer-search-behavior) · 2025-04-29 · leído<br>[BrightLocal SMB 2026](https://www.brightlocal.com/research/smb-marketing-report/) · leído | 2 (misma editorial) | 45 % usa Google para buscar local; 15 % Maps (BrightLocal Consumer, 2025) | Lo local es puerta de entrada, pero queda fuera del alcance de presencIA: solo se detectaría, no se gestiona la ficha |
| 4 | Hacerlo sin tiempo ni conocimientos | 1: Morningscore | [BrightLocal SMB 2026](https://www.brightlocal.com/research/smb-marketing-report/) · leído | 1 | 98 % de pymes hace su propio marketing; 28 % lo ve demasiado técnico | No tienen tiempo ni conocimiento: informe claro y una sola URL es el hueco |
| 5 | Detectar fallos técnicos que impiden aparecer | 5: SE Ranking, Morningscore, Semrush, Serpstat, Lighthouse | **Pendiente:** falta una fuente que lo diga; la página de funciones de IA de Google no lo sostiene | 0 | — | Si la web no se rastrea o no es elegible, no aparece; es el núcleo de presencIA |
| 6 | Tener un informe presentable | 2: SE Ranking, Keyword.com | **Pendiente** | 0 | — | El informe es lo que el cliente entiende y lo que justifica pagar |
| 7 | Saber qué palabras clave busca su cliente | 4: SE Ranking, Morningscore, Semrush, Serpstat | **Pendiente** | 0 | — | Sin saber qué busca el cliente, se optimiza a ciegas; está en el alcance |
| 8 | Vigilar a la competencia | 3: SE Ranking, Semrush, Serpstat | **Pendiente** | 0 | — | Da prioridades, pero queda fuera del alcance académico de presencIA |
## 3. Tipo de proyecto elegido (CE 1e)

*Qué proyecto das como respuesta y por qué, frente a otras alternativas.*

**Por qué la aplicación web.** Es la única opción que recoge las seis funcionalidades imprescindibles de `00-documentoInicio.md`: auditoría con puntuación, informe, explorador de keywords, seguimiento de posiciones, login y formulario con email. Además, aplica las decisiones ya tomadas en `01b-sota.md` §4: Java + Spring Boot, PostgreSQL, HTML + CSS + JavaScript, Spring Security con JWT y Docker en un VPS.

**Por qué no las otras dos.** La extensión es más barata y rápida, pero se queda sin zona privada, sin login, sin panel de seguimiento y sin descarga de informes. El script/CLI sirve para generar informes, pero deja fuera el formulario público, el panel en tiempo real y el despliegue web. La aplicación web no es la opción más barata ni la más rápida; es la que cubre el alcance previsto sin dejar funciones imprescindibles fuera.

## 4. Requisitos y restricciones (CE 1f)

*Características que debe cumplir el proyecto, redactadas de forma **verificable** (no «debe ser rápido», sino «responde en menos de 2 s»). Parte de lo que has encontrado en [`01b-sota.md`](01b-sota.md).*

> **Guía.** Numera los requisitos **funcionales** como **RF-01, RF-02…** (qué hace el sistema) y los **no funcionales** como **RNF-01…** (cómo lo hace: rendimiento, seguridad, usabilidad, disponibilidad, accesibilidad). Las **restricciones** (plazo, presupuesto, tecnología obligatoria, normativa) como **REST-01…**. Cada requisito debe tener **una medida o una prueba**. Si aún no sabes cómo lo probarás, escribe «pendiente» y complétalo antes de H3.

| ID | Requisito | Tipo (funcional / no funcional / restricción) | Cómo se verifica |
|---|---|---|---|
| RF-01 | Auditar una URL y mostrar puntuación SEO, GEO y AEO | funcional | Introducir una URL de ejemplo y comprobar que aparecen las tres puntuaciones y las incidencias detectadas |
| RF-02 | Generar el informe en modo privado, público o por enlace | funcional | Al terminar una auditoría, abrir los tres modos y comprobar que el informe se ve en cada uno |
| RF-03 | Explorar keywords con sugerencias, intención y dificultad | funcional | Introducir una keyword de prueba y comprobar que se muestran los tres datos |
| RF-04 | Mostrar el seguimiento de posiciones de una marca | funcional | Registrar una marca con datos de ejemplo y comprobar que su posición aparece en el panel |
| RF-05 | Permitir login en la zona privada | funcional | Iniciar y cerrar sesión con credenciales de prueba y comprobar el acceso a la zona privada |
| RF-06 | Enviar el formulario de información con email de confirmación | funcional | Rellenar el formulario con datos de ejemplo y comprobar que llega el correo de confirmación |
| RNF-01 | La auditoría de una URL termina y muestra el resultado | no funcional | Introducir una URL de ejemplo y comprobar que aparece el informe; el tiempo exacto queda pendiente |
| RNF-02 | La zona privada pide usuario y contraseña | no funcional | Entrar con un usuario de prueba y comprobar que, sin sesión iniciada, no se ve el panel |
| RNF-03 | La auditoría se pide en una sola pantalla y el informe usa lenguaje claro | no funcional | Comprobar que solo hay un campo principal de URL y que una persona sin conocimientos de SEO entiende la puntuación y tres recomendaciones |
| RNF-04 | La aplicación se abre desde un navegador en una dirección pública | no funcional | Abrir la dirección en otro navegador o en modo incógnito y comprobar que carga |
| RNF-05 | Los campos tienen etiqueta y se pueden recorrer con el teclado | no funcional | Rellenar el formulario usando solo la tecla Tab; el nivel concreto de accesibilidad queda pendiente |
| REST-01 | Entrega H1 el 26-nov-2026 (`docs/01-analisis.md` y `01b-sota.md`) | restricción | Comprobar que el análisis y el SOTA están cerrados antes de esa fecha |
| REST-02 | Proyecto académico sin empresa real (`00-documentoInicio.md` §9). El coste del alojamiento sigue pendiente (`01b-sota.md` §4); no se pone una cifra inventada | restricción | Revisar que no aparece ningún importe sin fuente |
| REST-03 | Tecnologías del ciclo: Java, HTML, CSS, JavaScript y SQL (`00-documentoInicio.md` §7); base de datos SQL elegida: PostgreSQL (`01b-sota.md` §4). No añadir otras sin decidirlo antes | restricción | Revisar código y base de datos; comprobar que no aparece una tecnología nueva sin decisión |
| REST-04 | Sin datos personales reales (`00-documentoInicio.md` §9). Repositorio público: ni claves ni contraseñas (`AGENTS.md`) | restricción | Formularios y base de datos con datos de ejemplo; revisar que no hay `.env` ni claves (el `.gitignore` ya excluye `.env`) |
| REST-05 | Alcance: `presencIA` audita, puntúa y recomienda; no ejecuta mejoras (`01-analisis.md` §1, `01b-sota.md` §5) | restricción | Comprobar que el informe propone cambios y que la aplicación no los aplica |
| REST-06 | No se promete conexión en tiempo real con motores de IA: la duda está en `00-documentoInicio.md` §10 y sigue pendiente | restricción | Revisar que el documento no afirma una conexión que no está comprobada |

### Matriz de trazabilidad

*Une cada objetivo con sus requisitos, y estos con lo que los implementa y los comprueba. Se rellena por completo al final del proyecto; en H1 basta con **objetivo y requisito**.*

> **Guía.** Ejemplo ficticio: *OBJ-01 Gestionar citas → RF-02 Crear una cita → CU-03 → `POST /citas` → prueba P-07.* Cada RF y cada RNF de la tabla anterior debe aparecer aquí.

| Objetivo | Requisito | Caso de uso | Pantalla o endpoint | Prueba o indicador |
|---|---|---|---|---|
| OBJ-01 Auditar una URL | RF-01 | pendiente | pendiente | pendiente |
| OBJ-01 Auditar una URL | RNF-01 | pendiente | pendiente | pendiente |
| OBJ-02 Mostrar y compartir el informe | RF-02 | pendiente | pendiente | pendiente |
| OBJ-02 Mostrar y compartir el informe | RNF-03 | pendiente | pendiente | pendiente |
| OBJ-03 Explorar keywords | RF-03 | pendiente | pendiente | pendiente |
| OBJ-04 Seguir posiciones de una marca | RF-04 | pendiente | pendiente | pendiente |
| OBJ-05 Acceder a la zona privada | RF-05 | pendiente | pendiente | pendiente |
| OBJ-05 Acceder a la zona privada | RNF-02 | pendiente | pendiente | pendiente |
| OBJ-06 Solicitar información | RF-06 | pendiente | pendiente | pendiente |
| OBJ-07 Publicar y usar la aplicación | RNF-04 | pendiente | pendiente | pendiente |
| OBJ-07 Publicar y usar la aplicación | RNF-05 | pendiente | pendiente | pendiente |

## 5. Obligaciones fiscales, laborales y de prevención (CE 1g)

**Situación de `presencIA`:** proyecto académico de DAW, sin empresa real ni datos personales reales (`00-documentoInicio.md` §9), sin ingresos, sin personas contratadas y sin centro de trabajo. La tabla separa lo que obliga hoy —nada— de lo que obligaría si el proyecto pasara a ser un negocio real.

| Ámbito | Obligación y norma | Condición en presencIA |
|---|---|---|
| Fiscal · IAE | El hecho imponible es el mero ejercicio de actividades empresariales, profesionales o artísticas, aunque no se ejerzan en local determinado (art. 78.1 del RDL 2/2004). Se considera actividad empresarial la que supone ordenación por cuenta propia de medios para intervenir en la producción o distribución de bienes o servicios (art. 79). | **No aplica:** no hay ordenación de medios con esa finalidad ni actividad económica. Si el proyecto se convirtiera en negocio, habría que darse de alta en el censo. |
| Fiscal · IVA | Grava las entregas de bienes y prestaciones de servicios realizadas por empresarios o profesionales (art. 1.a de la Ley 37/1992). Están sujetas las que se hacen a título oneroso, habitual u ocasional, en el desarrollo de la actividad (art. 4.uno). | **No aplica:** no hay prestaciones a cambio de dinero. Si hubiera clientes y facturas, habría que declararlo. |
| Laboral · Contrato | El Estatuto de los Trabajadores (RDL 2/2015) se aplica a quienes prestan servicios retribuidos por cuenta ajena dentro del ámbito de organización y dirección de otra persona (art. 1.1). El contrato puede ser escrito o de palabra (art. 8.1). | **No aplica:** no hay personas contratadas. Si se contratara, haría falta esa relación retribuida y bajo dirección. |
| Laboral · Seguridad Social | Los empresarios deben solicitar la afiliación y comunicar el alta, la baja y las variaciones en el Régimen General (art. 139.1 de la LGSS, RDL 8/2015) y son responsables de cotizar e ingresar las aportaciones propias y de los trabajadores (art. 142.1). Según el Punto de Acceso General, el alta se pide antes de empezar, con hasta 60 días de antelación, por Sistema RED; bajas y variaciones, en 3 días naturales. | **No aplica ahora.** Si se contratara, el alta sería previa al inicio y habría que cotizar. |
| Prevención · PRL | La Ley 31/1995 tiene por objeto promover la seguridad y la salud de los trabajadores (art. 2.1). El art. 16 exige un plan de prevención y una evaluación inicial de riesgos según la actividad, los puestos y los trabajadores. La guía del INSST señala que esa evaluación es obligación del empresario y debe cubrir inicialmente toda la empresa. | **No aplica:** no hay trabajadores ni puestos de trabajo. Si se contratara, se evaluaría el puesto creado antes de empezar. |
| Protección de datos · RGPD y LOPDGDD | La LOPDGDD adapta el ordenamiento español al Reglamento (UE) 2016/679 y garantiza los derechos digitales (art. 1). Se aplica a cualquier tratamiento total o parcialmente automatizado de datos personales (art. 2.1), y los responsables están sujetos al deber de confidencialidad (art. 5.1). | **No aplica con datos reales:** el proyecto usa datos de ejemplo (`00-documentoInicio.md` §9). Si pasara a producción con registro de usuarios, habría que tener base jurídica para tratar el email, informar a quien se registra y proteger esos datos. |

### Fuentes consultadas

Fecha de acceso: 2026-11-23. Solo fuentes oficiales.

| Fuente | Enlace | Estado |
|---|---|---|
| RDL 2/2004, texto consolidado (última actualización 2026-10-07). Leídos arts. 78 y 79 | [BOE](https://www.boe.es/buscar/act.php?id=BOE-A-2004-4214) | leído |
| Ley 37/1992, texto consolidado (última actualización 2026-10-07). Leídos arts. 1 y 4 | [BOE](https://www.boe.es/buscar/act.php?id=BOE-A-1992-28740) | leído |
| RDL 2/2015, Estatuto de los Trabajadores (última actualización 2026-11-18). Leídos arts. 1 y 8 | [BOE](https://www.boe.es/buscar/act.php?id=BOE-A-2015-11430) | leído |
| RDL 8/2015, Ley General de la Seguridad Social (última actualización 2026-11-11). Leídos arts. 139 y 142 | [BOE](https://www.boe.es/buscar/act.php?id=BOE-A-2015-11724) | leído |
| Ley 31/1995, Prevención de Riesgos Laborales (última actualización 2026-04-09). Leídos arts. 2 y 16 | [BOE](https://www.boe.es/buscar/act.php?id=BOE-A-1995-24292) | leído |
| Ley Orgánica 3/2018, Protección de Datos Personales y garantía de los derechos digitales (última actualización 2025-12-27). Leídos arts. 1, 2 y 5 | [BOE](https://www.boe.es/buscar/act.php?id=BOE-A-2018-16673) | leído |
| Punto de Acceso General, «Alta de empleados» (última actualización 2026-04-07) | [administracion.gob.es](https://administracion.gob.es/tu-espacio-europeo/derechos-obligaciones/empresas/empleados/seguridad-social/alta-empleados) | leído |
| INSST, «Evaluación de riesgos en las empresas» (PDF) | [INSST](https://www.insst.es/documents/d/portal-insst/que-es-y-como-abordar-la-evaluacion-de-riesgos-en-las-empresas) | leído |

*Dos normas más aparecen citadas en la página del Punto de Acceso General: el RDL 84/1996 y la Orden ESS/484/2013. Solo se ha comprobado su fecha de actualización, así que se marcan `sin leer` y no se usan en la tabla.*

## 6. Ayudas y subvenciones (CE 1h)

**Situación:** las ayudas se plantean para la empresa que se constituiría si `presencIA` siguiera, no para el proyecto académico. Hoy no se puede solicitar ninguna porque no existe la sociedad ni la actividad económica, y el proyecto ocupa a una sola persona. Ninguna se ha pedido.

| Ayuda | Organismo y ámbito | Requisitos comprobados | Importe | Plazo y estado |
|---|---|---|---|---|
| Préstamo participativo «Startups y pymes» | ENISA (Ministerio de Industria y Turismo) · nacional | Proyecto empresarial innovador, sin garantías ni avales. El detalle de los requisitos está en un desplegable de la web: **pendiente** de transcribir | De 25.000 a 1.500.000 €; hasta 7 años de amortización con carencia de capital de hasta 2 años; intereses ligados a los resultados; no figura en CIRBE | **Abierta**: línea permanente, sin convocatoria ni fecha de cierre |
| Préstamo participativo «Emprendedoras Digitales» | ENISA · nacional | Pyme con soluciones tecnológicas en la que las mujeres ocupan posiciones relevantes del órgano de administración o del equipo directivo. Mismas condiciones e importes que la línea anterior | De 25.000 a 1.500.000 €, mismas condiciones | **Abierta**: línea permanente |
| Bono Kit Digital | Red.es (Ministerio para la Transformación Digital) · nacional | Pymes, microempresas y autónomos, por segmentos de plantilla. Importe del bono **pendiente** de comprobar | Bono por segmento: **pendiente** | **Cerrada**: el último plazo terminó el 2025-10-31 y en 2026 no hay convocatoria |
| Bono Kit Consulting (asesoramiento digital) | Red.es · nacional | Pymes de 10 a menos de 250 empleados. `presencIA` no llegaría al mínimo de plantilla | 12.000 € de 10 a 49 empleados; 18.000 € de 50 a 99; 24.000 € de 100 a 249 | **Cerrada**: la sede electrónica indica «convocatoria finalizada» |
| NEOTEC | CDTI (Ministerio de Ciencia, Innovación y Universidades) · nacional | Empresa de base tecnológica. Se descartan los modelos basados primordialmente en servicios a terceros sin tecnología propia, así que el encaje de `presencIA` es dudoso | 20.383.300 € de presupuesto total de la convocatoria; ayuda por proyecto: **pendiente** | **Cerrada**: del 2026-04-14 al 2026-05-14. Convocatoria de 2027 no publicada: **pendiente** |
| Línea I · Aceleración de Proyectos | Ayuntamiento de Gijón (Gijón Impulsa) · local | Persona física mayor de edad, empadronada en Gijón y sin actividad económica previa en el mismo epígrafe del IAE; o autónomo dado de alta después del 2025-09-20 con domicilio fiscal y centro de trabajo en Gijón. Obligatorio un plan de empresa tutorizado (12 h) y un curso de formación para emprender (30 h) | Máximo 6.000 €, en dos fases de 3.000 € | **Cerrada en 2026**: del 8 al 27 de abril y del 1 al 20 de septiembre. La convocatoria de 2027 no se ha publicado: **pendiente** |
| Programa de Ayuda a la Transformación Digital 2026 | SEKUENS / IDEPA (Principado de Asturias) · autonómico | **Sin leer**: el PDF de la convocatoria no se pudo abrir. No se afirman requisitos, importes ni plazos | **pendiente** | **pendiente** |

**Conclusión:** la única ayuda abierta hoy es el préstamo de ENISA, y tiene dos matices que conviene no esconder: **no es una subvención** —se devuelve, con intereses ligados a los resultados— y exige una sociedad ya constituida. Las subvenciones a fondo perdido que encajarían por tipo de proyecto —Kit Digital, Kit Consulting y NEOTEC— están cerradas en 2026, y la única local que admite a una persona física sin empresa, la Línea I de Gijón, exige estar empadronada en el municipio y volverá a convocarse, como pronto, en 2027.

**Aviso:** varias webs comerciales anuncian «Kit Digital 2026» o «Kit Consulting 2026» con plazos abiertos. Ninguna de esas convocatorias aparece en las fuentes oficiales consultadas.

### Fuentes consultadas

Fecha de acceso: 2026-11-23.

| Fuente | Enlace | Estado |
|---|---|---|
| ENISA, «Financiación para startups y pymes»: importes y condiciones | [enisa.es](https://www.enisa.es/servicios/financiacion/startups-y-pymes/) | leído |
| ENISA, «Emprendedoras Digitales»: destinatarias e importes | [enisa.es](https://www.enisa.es/servicios/financiacion/emprendedoras-digitales/) | leído |
| Red.es, «Kit Digital cierra las dos últimas convocatorias que quedaban abiertas» (2025-10-31) | [red.es](https://www.red.es/es/actualidad/noticias/kit-digital-cierra-las-dos-ultimas-convocatorias-que-quedaban-abiertas-tras-mas) | leído |
| Acelera pyme, «Kit Consulting»: importes por tramo de plantilla y aviso de convocatoria finalizada | [acelerapyme.gob.es](https://www.acelerapyme.gob.es/kit-consulting) | leído |
| Ministerio de Ciencia, Innovación y Universidades, «Programa NEOTEC 2026»: estado, plazos, presupuesto y criterio de empresa de base tecnológica | [ciencia.gob.es](https://www.ciencia.gob.es/Convocatorias/2026/NEOTEC2026.html) | leído |
| Ayuntamiento de Gijón, bases de los Incentivos Impulsa 2026 (Línea I): requisitos de personas físicas, autónomos y empresas | [gijon.es (PDF)](https://drupal.gijon.es/sites/default/files/2026-03/1.%20Bases%20Acel.%2C%20IA%20y%20Crecim.%202026%20V5%20%28definitivas%29.pdf) | leído |
| Ayuntamiento de Gijón, «Aprobadas en Junta de Gobierno las convocatorias de las líneas de subvenciones Gijón Impulsa 2026» (2026-03-24) | [gijon.es](https://drupal.gijon.es/es/aprobadas-en-junta-de-gobierno-las-convocatorias-de-las-lineas-de-subvenciones-gijon-impulsa-2026) | leído |
| SEKUENS/IDEPA, convocatoria del Programa de Ayuda a la Transformación Digital 2026 (PDF) | [idepa.es (PDF)](https://www.idepa.es/documents/20147/913921/1.10.Convocatoria_ATD_2026.pdf/9e2a6197-2991-39ff-9658-47004603ac67) | sin leer |

## 7. Guion de trabajo (CE 1i)

*Fases, hitos y responsables del proyecto. Puede enlazar al tablero de GitHub Projects.*

## 8. Glosario

Una cosa, un nombre. Cuando una palabra de esta tabla aparezca en otro documento, se escribe así y no de otra forma. Los sinónimos de la última columna no se usan en ningún sitio, ni en la documentación ni en la interfaz.

| Término | Definición en este proyecto | Sinónimos que no se usan |
|---|---|---|
| Auditoría | El proceso completo: `presencIA` recibe una URL, la analiza y emite una puntuación con recomendaciones. Es el servicio que ofrece el proyecto | «análisis», «revisión», «diagnóstico», «estudio» |
| Informe | El resultado de la auditoría: el documento que la empresa lee o descarga, con la puntuación y las recomendaciones. La auditoría es el proceso; el informe, lo que se entrega | «reporte», «resultado», «output» |
| SEO | Conjunto de prácticas para que una página aparezca en los resultados de los buscadores | «posicionamiento web», «posicionamiento orgánico», «SEO tradicional» |
| GEO | Conjunto de prácticas para que una página sea citada en las respuestas de los asistentes de IA generativa | «SEO para IA», «optimización para IA» |
| AEO | Conjunto de prácticas para que la respuesta directa o el resumen que muestra el buscador recoja el contenido de la página | «SEO de respuestas», «optimización de respuestas» |
| Visibilidad en IA | Nombre que usa el proyecto para GEO y AEO en conjunto. Cuando el texto se refiera solo a uno de los dos, se escribe GEO o AEO, no «visibilidad» | «presencia en IA», «visibilidad generativa» |
| Puntuación | Número con el que el informe resume el estado de una URL | «nota», «score», «valoración» |
| Palabras clave | Los términos por los que una persona busca en un buscador | «keywords» (solo se admite en nombres de código o de campo) |
| SERP | La página de resultados que devuelve un buscador para una búsqueda | «resultados de Google», «página de resultados» |
| Rastreo | Recorrer una web página a página para analizarla. Quien lo hace es el rastreador | «crawling», «spider», «bot» |
| URL | La dirección de una página concreta que se audita | «enlace», «link», «dirección» (enlace se reserva para los hipervínculos de las fuentes) |
| Cliente | La empresa cuya web se audita | «usuario», «cuenta» |
| Usuario | La persona que se registra e inicia sesión en la zona privada | «cliente», «miembro» |
| Freemium | Modelo del proyecto: la primera auditoría de una URL es gratuita —una por enlace— y el resto se paga por suscripción | «gratis con límite», «prueba gratuita» |

*Queda una incoherencia pendiente de resolver en `00-documentoInicio.md`: allí se dice «una auditoría gratuita por enlace», y este glosario reserva «enlace» para los hipervínculos. Debería decir «una por URL».*

---

## Criterios de evaluación de este documento (RA1, texto literal)

- **1a)** Se han clasificado las empresas del sector por sus características organizativas y el tipo de producto o servicio que ofrecen.
- **1b)** Se han caracterizado las empresas tipo indicando la estructura organizativa y las funciones de cada departamento.
- **1c)** Se han identificado las necesidades más demandadas a las empresas.
- **1d)** Se han valorado las oportunidades de negocio previsibles en el sector.
- **1e)** Se ha identificado el tipo de proyecto requerido para dar respuesta a las demandas previstas.
- **1f)** Se han determinado las características específicas requeridas al proyecto.
- **1g)** Se han determinado las obligaciones fiscales, laborales y de prevención de riesgos y sus condiciones de aplicación.
- **1h)** Se han identificado posibles ayudas o subvenciones para la incorporación de nuevas tecnologías de producción o de servicio que se proponen.
- **1i)** Se ha elaborado el guión de trabajo que se va a seguir para la elaboración del proyecto.

# Colombia Ancestral

Base documental para investigar y divulgar la arqueología, el poblamiento ancestral, la diversidad cultural y el etnoturismo responsable de Colombia.

## Principios

- Priorizar fuentes primarias, publicaciones académicas y entidades oficiales.
- Separar **verificado**, **preliminar**, **controvertido** y **pendiente de comprobar**.
- No inventar cronologías, sitios, atribuciones culturales, coordenadas ni testimonios.
- No divulgar coordenadas sensibles ni fomentar la extracción, compra o alteración de bienes arqueológicos.
- Verificar permisos de acceso, derechos de autor y condiciones de uso antes de publicar.
- Mantener este proyecto separado de **COLOMBIA FÓSIL**, que trata de geología y paleontología.

## Punto de partida: Quindío

La primera fase documentará las fuentes institucionales y académicas relacionadas con el departamento del Quindío. Las menciones históricas de sitios y los conteos antiguos no se tratarán como inventario actual hasta cotejarlos con los registros vigentes del ICANH y sus informes de soporte.

## Orden cronológico de investigación

La ruta de trabajo inicia con el poblamiento temprano y sus controversias, continúa con las adaptaciones del Holoceno, agricultura y cerámica, sociedades regionales del Cauca Medio/Quindío, grupos nombrados en fuentes históricas, contacto colonial y etnoturismo responsable. Ver [cronología de poblamiento y grupos](docs/cronologia_poblamiento_y_grupos.md) y el [plan de lecturas del Holoceno](docs/plan_lecturas_holoceno_01.md). La cronología marca explícitamente los datos discutidos y no convierte tradiciones arqueológicas en etnias sin evidencia.

## Estructura prevista

- `data/`: tablas de inventario y fuentes, con estado de verificación.
- `docs/`: metodología, diccionario de datos y criterios de seguridad patrimonial.
- `research/quindio/`: fichas de investigación por municipio y tema.
- `scripts/`: herramientas reproducibles para validar y comparar datos, cuando existan fuentes descargables y autorizadas.

## Fichas de evidencia incorporadas

- [Ficha 01 — Cronología de Filandia según PARQUIM (2023)](docs/fichas_evidencia/01_cronologia_filandia_parquim_2023.md): periodización propuesta por los autores, fechas radiocarbónicas reportadas y límites de extrapolación.
- [Ficha 02 — Poblamiento temprano de Colombia: revisión crítica](docs/fichas_evidencia/02_poblamiento_temprano_colombia_revision_critica.md): El Abra, Tibitó, Tequendama y Pubenza 3; distingue fechas reportadas, calibración y controversias.
- [Ficha 03 — Rodríguez (1988), Hoya del Quindío](docs/fichas_evidencia/03_agricultores_prehispanicos_hoya_quindio_rodriguez_1988.md): ficha provisional basada en metadatos y resumen; texto completo pendiente.
- [Ficha 04 — Arqueología y diversidad étnica actual](docs/fichas_evidencia/04_puente_arqueologia_diversidad_etnica_actual.md): marco para usar el Atlas del ICANH y datos del DANE sin confundir tradiciones arqueológicas con pueblos vivos.
- [Ficha 05 — Síntesis crítica del poblamiento temprano](docs/fichas_evidencia/05_sinopsis_poblamiento_temprano_delgado_2017.md): lectura de Miguel Delgado (2017), con límites cronológicos, vacíos regionales y tareas de cotejo primario.
- [Ficha 06 — El Abra: fuente primaria de 1977](docs/fichas_evidencia/06_el_abra_fuente_primaria_1977.md): fecha de carbón vegetal, contexto estratigráfico y cautelas de asociación con artefactos.
- [Ficha 07 — Tibitó: estado de revisión de la fuente primaria](docs/fichas_evidencia/07_tibito_fuente_primaria_estado_lectura.md): datos del resumen institucional; PDF íntegro pendiente por limitación técnica.
- [Ficha 08 — Pubenza: estado de revisión de la fuente primaria](docs/fichas_evidencia/08_pubenza_fuente_primaria_estado_lectura.md): texto OCR completo en reproducción digital no institucional; cotejo del facsímil oficial y procedencia de la muestra pendientes.
- [Ficha 09 — Tibitó: informe preliminar de 1981](docs/fichas_evidencia/09_tibito_informe_preliminar_1981.md): lectura completa del avance publicado en *Boletín Museo del Oro*; distingue este texto del estudio ampliado pendiente.
- [Ficha 10 — Peñones de Bogotá, Magdalena Medio](docs/fichas_evidencia/10_penones_magdalena_medio_fuente_primaria_estado.md): resumen institucional de un estudio radiocarbónico que los autores califican como preliminar; lectura integral pendiente.
- [Ficha 11 — Auditoría de acceso a fuentes primarias](docs/fichas_evidencia/11_auditoria_acceso_fuentes_tibito_pubenza_penones.md): separa registros, resúmenes institucionales y textos íntegros; documenta límites de acceso y tareas de cotejo.
- [Ficha 12 — Pubenza en Correal (1993)](docs/fichas_evidencia/12_pubenza_correal_1993_lectura_texto_disponible.md): lectura del texto OCR completo disponible, cautelas sobre la muestra de carbón y límites de asociación.
- [Ficha 13 — Registro bibliográfico arqueológico del ICANH](docs/fichas_evidencia/13_icanh_registro_bibliografico_siete_zonas.md): recurso oficial de consulta regional; el PDF está localizado, pero su contenido interno aún no se declara leído.

## Matrices comparativas

- [Matriz comparativa 01 — Poblamiento temprano de Colombia](docs/matrices/matriz_comparativa_01_poblamiento_temprano.md): contrasta El Abra, Tibitó, Tequendama, Pubenza 3, El Jordán y El Jazmín; explicita qué está reportado y qué requiere cotejo primario.

## Estados de verificación

- `verificado`: respaldado por una fuente primaria o institucional comprobada.
- `corroborado`: respaldado por más de una fuente fiable, pendiente de comprobar el registro primario.
- `preliminar`: mención en fuente secundaria o referencia aún no cotejada.
- `pendiente`: requiere consulta o evidencia adicional.
- `descartado`: no debe usarse como afirmación; conservar nota de por qué se descartó.
- `metadatos_localizados_contenido_pendiente`: se localizó la ficha bibliográfica, pero falta revisar íntegramente el texto y cotejar sus fuentes.
- `metadatos_y_resumen_verificados`: se comprobaron los metadatos y se consultó el resumen en una fuente institucional; la lectura integral y el cotejo de datos siguen pendientes.

## Nota

Este repositorio comienza como una base de trabajo. Un registro incluido aquí no implica que un lugar esté abierto al público, que sea visitable ni que su localización deba difundirse.

## Aplicación web educativa

- [Propuesta del MVP: museo virtual interactivo](docs/app_web_educativa_mvp.md)

## Prototipo de aplicación web

- **Interfaz interactiva inicial:** [`web/index.html`](web/index.html)
- **Alcance y criterios del MVP:** [`docs/app_web_educativa_mvp.md`](docs/app_web_educativa_mvp.md)

El prototipo es estático y autocontenido; no requiere cuentas, claves, servicios de pago ni bibliotecas externas. Para previsualizarlo localmente, descarga `web/index.html` y ábrelo en un navegador moderno. **No se ha activado GitHub Pages ni se ha publicado el sitio.** Antes de activar un alojamiento público, revisar el contenido, las fuentes, los derechos de uso y la aprobación editorial.

## Estado del MVP web

- [Museo virtual](web/index.html): línea del tiempo, fichas con filtros y cuestionario didáctico.
- [Aula docente](web/aula-docente.html): actividades por nivel y plantilla para analizar evidencias.
- [Accesibilidad, privacidad y uso responsable](web/accesibilidad.html).
- [Validación automática](.github/workflows/validar-web.yml): revisa sintaxis JavaScript incrustada y enlaces locales; no publica el sitio.
- [Publicación manual con control de aprobación](.github/workflows/publicar-web-manual.yml): solo puede iniciar manualmente y requiere marcar explícitamente la confirmación. No se ha ejecutado ni se ha publicado el sitio.

### Probar localmente

Descarga la carpeta `web` y abre `index.html` en un navegador moderno. Los archivos del prototipo son estáticos y no requieren instalación de paquetes ni claves de servicios externos. La validación automática se ejecuta en GitHub Actions después de cambios en los archivos web.

**Estado de publicación:** no publicado. Antes de lanzar, revisar el sitio, fuentes, licencias, accesibilidad y resultados del flujo de validación. La publicación hará el contenido accesible públicamente.

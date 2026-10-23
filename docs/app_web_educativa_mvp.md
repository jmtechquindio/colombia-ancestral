# Aplicación web educativa — COLOMBIA ANCESTRAL

## Propósito

Diseñar una aplicación web educativa, didáctica y adaptable a móviles para explorar la arqueología, el poblamiento humano, la diversidad cultural y el patrimonio de Colombia. La aplicación debe transformar la investigación documentada del repositorio en experiencias comprensibles sin presentar hipótesis como hechos.

## Público

- Niñas, niños y jóvenes.
- Docentes y estudiantes.
- Familias y público general.
- Personas interesadas en patrimonio y turismo cultural responsable.

La primera versión usará lenguaje claro y capas de profundidad: explicación breve, ampliación para curiosos y fuentes para docentes/investigadores.

## Principios editoriales obligatorios

1. Cada afirmación histórica o arqueológica debe tener una fuente rastreable.
2. Etiquetar cada contenido como **verificado**, **preliminar**, **controvertido** o **pendiente de comprobar**.
3. Diferenciar fecha de muestra, fecha del contexto, fecha del objeto y estimación cronológica.
4. Explicar incertidumbres, métodos y límites de las evidencias.
5. No equiparar automáticamente tradiciones materiales arqueológicas con pueblos étnicos históricos o actuales.
6. Para pueblos y comunidades vivas, priorizar fuentes de las propias comunidades y respetar sus nombres, voces, protocolos y derechos.
7. No publicar coordenadas arqueológicas sensibles ni promover excavaciones, guaquería o extracción de objetos.
8. Revisar licencias y permisos antes de reutilizar textos, imágenes, mapas, audios o videos.
9. Para rutas culturales, incluir solo lugares, accesos y servicios confirmados; respetar cierres, permisos, comunidades anfitrionas y conservación.
10. La aplicación no reemplaza a las entidades oficiales ni constituye autorización de acceso a sitios.

## Mapa del producto — MVP

### 1. Inicio: «Viaja por la historia de Colombia»
- Introducción visual.
- Accesos por tiempo, región y tema.
- Actividad breve destacada.
- Indicadores de estado de revisión del contenido.

### 2. Línea de tiempo
- Recorrido cronológico desde el poblamiento temprano hasta sociedades y comunidades actuales.
- Cada etapa indica rango temporal, región, tipo de evidencia, nivel de confianza y fuentes.
- No presentar una cronología nacional única como si todas las regiones tuvieran la misma secuencia.

### 3. Explorador de evidencias
- Fichas de sitios, materiales, contextos y publicaciones.
- Campos: qué se encontró; dónde en términos generales; método; fecha y qué fue fechado; interpretación de los autores; límites; estado de verificación; fuente.
- Evitar coordenadas de localizaciones vulnerables.

### 4. Colombia por regiones
- Mapa educativo por departamento o región, con contenido validado.
- Filtros por periodo, tema y tipo de evidencia.
- No mostrar un punto en el mapa si la precisión o la seguridad de la localización no es adecuada.
- La cartografía debe distinguir lugares de investigación, museos, áreas protegidas y destinos visitables.

### 5. Culturas, pueblos y comunidades
- Separar explícitamente arqueología, historia documental y comunidades actuales.
- Fichas de pueblos actuales construidas con fuentes oficiales y, cuando sea posible, materiales publicados por las propias comunidades.
- No afirmar continuidad étnica directa sin evidencia específica.

### 6. Aprende jugando
- Preguntas de opción múltiple con explicación de cada respuesta.
- Ordenar eventos en una línea de tiempo.
- Relacionar evidencia con preguntas científicas.
- «¿Qué sabemos y qué no sabemos?» para practicar pensamiento crítico.
- Sin puntuaciones que premien respuestas históricas simplistas o no verificadas.

### 7. Aula para docentes
- Guías de clase por edades.
- Actividades breves y objetivos de aprendizaje.
- Glosario, preguntas de discusión y referencias.
- Material descargable solo cuando sus licencias permitan la distribución.

### 8. Patrimonio y etnoturismo responsable
- Recomendaciones de respeto cultural y conservación.
- Solo incluir experiencias y sitios visitables tras verificar acceso, fuente oficial, permisos y relación con la comunidad anfitriona.
- No promover visitas a lugares sensibles, sagrados, cerrados o sin acceso confirmado.

### 9. Fuentes y metodología
- Bibliografía y enlaces directos.
- Fecha de última revisión.
- Cómo se evalúa la evidencia.
- Registro de correcciones y contenidos pendientes.

## Primer paquete de contenidos

Para lanzar con rigor y evitar prometer una cobertura nacional todavía no documentada:

1. **Cómo sabemos lo que sabemos:** introducción al método arqueológico, contexto y datación.
2. **El poblamiento temprano:** El Abra, Tibitó, Tequendama y Pubenza, presentados con las controversias y límites documentales correspondientes.
3. **Holoceno y cambios en las formas de vida:** empezar con Checua, Aguazuque y evidencia de uso de plantas solo cuando se verifiquen los textos completos.
4. **Quindío y Cauca Medio:** PARQUIM/Filandia y secuencias cerámicas con alcance regional claramente delimitado.
5. **Diversidad cultural actual:** incorporar fichas comunitarias solo después de verificar fuentes actuales y representación respetuosa.

No todos los temas anteriores estarán listos al mismo tiempo: cada ficha se publica únicamente al alcanzar el estándar de evidencia definido.

## Diseño y experiencia

- Diseño visual tipo museo interactivo, con navegación sencilla y lectura cómoda.
- Prioridad móvil, diseño adaptable y controles accesibles por teclado.
- Texto alternativo para imágenes, contraste legible y subtítulos/transcripciones para audio y video.
- Animaciones moderadas y opción de reducir movimiento.
- Sin necesidad de crear cuenta para consultar el contenido básico.
- Rendimiento ligero y uso de formatos de imagen optimizados.

## Arquitectura propuesta

MVP estático y de bajo costo:
- Interfaz web adaptable.
- Contenidos almacenados inicialmente en archivos Markdown/JSON versionados en este repositorio.
- Fichas de contenido separadas de los componentes visuales para facilitar revisión, traducción y actualización.
- Cada ficha tendrá identificador, título, periodo, región, resumen, evidencias, estado de verificación, fuentes, derechos/licencia y fecha de revisión.
- Sin base de datos, cuentas, analítica invasiva ni servicios pagos en la primera fase.
- Evaluar funciones de administración o base de datos solo cuando exista una necesidad real.

La tecnología definitiva se elegirá después de una prueba mínima de interfaz y de confirmar el flujo de publicación. No se deben exponer claves ni secretos en el frontend o el repositorio.

## Flujo de publicación de contenidos

1. Investigación y registro de fuente.
2. Extracción de afirmaciones y evidencias.
3. Revisión de fechas, contexto, atribución y límites.
4. Redacción en lenguaje sencillo.
5. Verificación de derechos de texto y multimedia.
6. Revisión editorial.
7. Publicación versionada.
8. Revisión periódica y corrección documentada.

## Fases de trabajo

- **Fase 0 — Fundamentos:** definir modelo de ficha, categorías, estados de verificación y criterios de derechos.
- **Fase 1 — Prototipo navegable:** inicio, línea de tiempo, ficha de evidencia, juego de preguntas y bibliografía con datos de demostración explícitamente marcados.
- **Fase 2 — Primer contenido verificado:** cargar solo fichas revisadas desde el repositorio.
- **Fase 3 — Prueba educativa:** revisar comprensión, accesibilidad y navegación con usuarios; no recopilar datos personales innecesarios.
- **Fase 4 — Ampliación:** regiones, aula docente y contenidos de comunidades actuales.
- **Fase 5 — Etnoturismo responsable:** publicar experiencias únicamente después de verificar fuentes, acceso y participación comunitaria.

## Criterios de aceptación del MVP

- Se ve y funciona en teléfono y escritorio.
- Línea de tiempo, fichas, cuestionario y bibliografía navegan correctamente.
- Toda afirmación factual publicada tiene una fuente identificable.
- Las incertidumbres aparecen de forma visible y comprensible.
- No se muestran coordenadas arqueológicas sensibles.
- No hay imágenes o textos reutilizados sin permiso/licencia compatible.
- No se requiere pago, registro de usuario ni clave privada para consultar el prototipo.
- Existe una guía para agregar y revisar contenido sin romper la interfaz.

## Decisiones pendientes

- Nombre visible: **COLOMBIA ANCESTRAL — Museo virtual interactivo** (provisional).
- Selección final de tecnología y alojamiento gratuito.
- Identidad visual y paleta.
- Definición del primer grupo de edad objetivo; el contenido seguirá siendo comprensible para público general.
- Revisión de fuentes y licencias antes de incorporar recursos multimedia.

## Fuentes institucionales de referencia

- ICANH, preguntas frecuentes sobre patrimonio arqueológico y Atlas Arqueológico de Colombia: https://www.icanh.gov.co/generales/preguntas-frecuentes-3
- ICANH, guía para incorporar y proteger el patrimonio arqueológico en el territorio: https://www.icanh.gov.co/prensa/actualidad-icanh/guia-para-incorporar-y-proteger-el-patrimonio-arqueologico-en-tu-territorio
- ICANH, *Gestión y protección del patrimonio arqueológico para entidades territoriales*: https://publicaciones.icanh.gov.co/index.php/picanh/catalog/book/109

Estas fuentes orientan la protección y divulgación; cada contenido educativo debe citar además la investigación específica que sustenta sus afirmaciones.

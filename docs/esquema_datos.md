# Esquema de datos del inventario

Una fila representa una mención documental de un sitio, hallazgo, colección o lugar de interés; no necesariamente un sitio arqueológico validado en campo.

Campos recomendados:

- `record_id`: identificador interno estable, no código oficial.
- `nombre_reportado`: nombre tal como aparece en la fuente.
- `municipio`, `departamento`: jurisdicción según la fuente y, si difiere, nota de normalización.
- `tipo_registro`: sitio, hallazgo, colección, petroglifo, estructura funeraria, referencia documental u otro.
- `descripcion_fuente`: resumen fiel de lo que afirma la fuente.
- `periodo_o_fecha`: solo cuando la fuente lo respalde; incluir incertidumbre.
- `fuente_id`: clave en el registro de fuentes.
- `pagina_o_seccion`: ubicación exacta del dato.
- `estado_verificacion`: verificado, corroborado, preliminar, pendiente o descartado.
- `tipo_evidencia`: informe primario, artículo académico, inventario histórico, nota institucional, etc.
- `ubicacion_publica_segura`: referencia geográfica generalizada; no incluir coordenadas sensibles.
- `acceso_publico_verificado`: sí, no o desconocido; nunca inferir que es visitable.
- `derechos_y_permisos`: condiciones para usar texto, fotos o material relacionado.
- `notas_y_pendientes`: contradicciones, tareas de verificación y limitaciones.

Los códigos oficiales, si se encuentran, deben guardarse en un campo separado y acompañarse de la entidad emisora y la fuente. No usar códigos citados en fuentes antiguas como identificadores oficiales vigentes sin confirmación.

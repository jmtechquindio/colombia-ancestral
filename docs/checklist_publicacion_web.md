# Lista de preparación para publicar COLOMBIA ANCESTRAL

**Estado: preparación en curso; esta lista no autoriza el despliegue.** GitHub Pages debe permanecer sin activar hasta la aprobación explícita de la persona responsable.

## 1. Evidencia y responsabilidad editorial
- [ ] Cada afirmación histórica o arqueológica relevante enlaza a una fuente identificable.
- [ ] Se distinguen fuentes primarias, síntesis académicas, registros bibliográficos y resúmenes.
- [ ] Las fechas se atribuyen a la muestra concreta; se distingue BP de fechas calibradas.
- [ ] Controversias, límites de asociación y vacíos de acceso aparecen donde corresponda.
- [ ] No se convierten secuencias materiales en identidades étnicas sin evidencia independiente.
- [ ] Los datos pendientes están etiquetados y no se presentan como hechos cerrados.
- [ ] No se publican coordenadas sensibles ni indicaciones que faciliten el saqueo.

## 2. Derechos y privacidad
- [ ] Se comprueban licencias y permisos de textos, fotografías, mapas, ilustraciones, audio y otros medios.
- [ ] Se atribuye cada material reutilizado según la licencia aplicable.
- [ ] No se incorporan datos personales, secretos, tokens, contraseñas ni claves de API.
- [ ] Se revisan enlaces externos y los que abren pestaña nueva usan rel="noopener noreferrer".
- [ ] La explicación de privacidad refleja las funciones reales; no se prometen servicios inexistentes.

## 3. Calidad técnica y accesibilidad
- [ ] GitHub Actions termina en éxito para el commit candidato a publicación.
- [ ] Los enlaces relativos a páginas locales resuelven correctamente.
- [ ] Se revisan sintaxis JavaScript, títulos, idioma, metadatos, etiquetas y nombres accesibles.
- [ ] Prueba manual en escritorio y móvil con al menos dos navegadores.
- [ ] Prueba solo con teclado: foco visible, controles utilizables y ausencia de trampas.
- [ ] Prueba con lector de pantalla si está disponible; no declarar auditoría WCAG completa sin evaluación real.
- [ ] Se revisan zoom al 200 %, contraste, movimiento reducido y pantallas pequeñas.
- [ ] Se revisan la página 404, navegación, filtros, cuestionario y mensajes de estado.
- [ ] Se comprueba que los enlaces externos abren las páginas esperadas.

## 4. Preparación de GitHub Pages
- [ ] Confirmar la rama y carpeta previstas: main y contenido de web/.
- [ ] Revisar que el workflow manual requiere confirm_publication: true.
- [ ] Verificar permisos del workflow y que solo despliegue el contenido de web/.
- [ ] Confirmar que no existe otro workflow de publicación automática.
- [ ] Revisar la configuración de Pages sin activarla.
- [ ] Guardar el commit candidato y el resultado de validación.
- [ ] Obtener aprobación explícita antes de ejecutar el workflow manual o activar Pages.

## 5. Después de la aprobación — no ejecutar todavía
1. La persona responsable confirma que autoriza la publicación pública.
2. Verificar que la aprobación corresponde al commit y al contenido revisados.
3. Ejecutar manualmente el workflow y marcar la confirmación requerida.
4. Esperar el resultado de Actions; no anunciar éxito hasta que el despliegue lo confirme.
5. Probar la URL publicada, enlaces, módulos y vista móvil.
6. Registrar URL, commit desplegado, fecha e incidencias.

## Estado de auditoría

Las comprobaciones automáticas son una primera barrera, no una certificación completa de accesibilidad, seguridad o exactitud científica. La revisión manual de navegación, tecnologías de asistencia, derechos y contenido sigue siendo necesaria.
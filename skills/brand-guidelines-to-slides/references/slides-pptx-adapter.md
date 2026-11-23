# Adaptador de Manus Slides y PPTX

## Límite de esta Skill

Esta Skill prepara decisiones de marca; la Skill oficial `slides` gobierna creación, edición, modos, sintaxis y entrega. Leer sus instrucciones actuales antes de actuar. No copiar su sintaxis completa aquí ni asumir que el motor permanece invariable.

Inspeccionar definiciones reales de herramientas antes de llamar. En el flujo consultado para esta versión, `init_slides` registra el deck, `present` lo entrega y `export` genera un archivo cuando se solicita; no inferir disponibilidad futura de estos campos sin comprobarla.

## Elegir el modo y aplicar el brief

Si el usuario solicita PPTX editable y no elige un modo incompatible, usar PowerPoint nativo cuando esté disponible. Si el usuario pide HTML o Image, respetarlo y explicar las limitaciones reales para editabilidad/exportación. No afirmar que una exportación desde un deck de imágenes produce tablas y texto editables.

Cuando la petición incluya «usar esta marca», trasladar las reglas confirmadas a la entrada de estilo nativa disponible, como `style_request` cuando el esquema la admita. Conservar el brief reutilizable fuera del deck; no confiar en que un archivo adjunto por sí solo configure la herramienta.

Comparar el design brief nativo con la marca aprobada antes de escribir páginas. Si contradice logo, color o tipografía de forma material, detener la autoría y resolverlo por el flujo soportado; no ignorar silenciosamente ninguna restricción ni re-inicializar el mismo deck para corregirla. No editar manifests ni briefs propiedad de las herramientas.

Si se proporciona un `template_id` exacto, seguir el flujo de plantilla de `slides`; no inventarlo ni buscarlo mediante una herramienta que solo acepta IDs. Las restricciones de plantilla pueden impedir cambios de layout; señalar el conflicto con la marca antes de continuar.

## PowerPoint nativo

Leer la referencia `pptx-xml-syntax.md` de la Skill oficial. Para la versión consultada:

- Lienzo autoritativo de 1280×720, coordenadas en px; no utilizar un formato arbitrario en XML.
- Tokens de color y fuente de deck en `design.xml`, escrito primero; páginas registradas después, mediante las herramientas nativas de archivo.
- Familias de fuente: una sola familia Google Fonts por variable, sin una lista CSS de fallbacks. Si la familia corporativa no está admitida, conservarla en la guía y proponer una alternativa técnica explícita para el deck. No afirmar que se puede subir o incrustar una fuente propietaria sin verificar esa capacidad y sus derechos.
- Mantener elementos de texto/forma/tabla/gráfico nativos. Usar la sintaxis actual y los tipos disponibles, sin efectos ni parámetros inventados.
- No generar/editarlas con `python-pptx`, OpenXML, shell o scripts. No modificar `project.json`.

Estas restricciones describen el motor consultado, no los límites generales de PowerPoint. Revisarlas en cada ejecución; no presentar una sustitución técnica como cambio de la identidad original.

## Probar y entregar

Cuando una plantilla de ejemplo esté solicitada, usar contenido neutro completo y trazable, no placeholders que parezcan datos reales. Incluir un layout con texto denso y una tabla o gráfico. Mantener las leyendas «datos sintéticos» si se usan pruebas, y no atribuirlas a la empresa.

Corregir errores de autoría y cumplir `present`. Si se pide `.pptx`, exportar después de presentar y confirmar el archivo retornado. La validación XML no prueba por sí sola legibilidad, fidelidad de marca ni apertura correcta en PowerPoint.

Revisar lo que esté observable: logo, colores aplicados, jerarquía, márgenes, densidad, tablas/gráficos y editabilidad real cuando pueda comprobarse. Diferenciar inspección visual, inspección estructural de objetos y apertura en la aplicación destino. No decir «probado en PowerPoint» si solo se validó el archivo ZIP/XML.

Enlazar el recurso `manus-resource://...` que devuelve Slides y el archivo exportado cuando exista. No entregar solo HTML suelto ni un screenshot como presentación completa.

## Importador de marca

Verificar el formulario específico antes de prometer una entrada importable. La documentación pública consultada describe importación de plantillas `.pptx`; no establece un contrato para cualquier documento de brand guidelines. Si el formulario no es accesible, mantener «importación no verificada». Esto no impide preparar la guía y el brief o usar reglas de marca en un encargo normal de Slides.

Referencias públicas consultadas al diseñar v1.0.0, 18 de octubre de 2026:
- https://manus.im/docs/features/slides
- https://manus.im/blog/manus-ppt-slides

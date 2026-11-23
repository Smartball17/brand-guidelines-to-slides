# Contrato de salida

## Guía operativa

Crear `brand-presentation-guidelines.md` con estas secciones, adaptadas a la marca y sin texto de relleno ni campos sin completar:

1. **Marca, alcance y estado.** Canal, audiencia, idioma, fecha/versión y propósito. Indicar si es guía oficial aportada, adaptación o estudio independiente. No autodenominarla oficial.
2. **Identidad confirmada y límites.** Qué preservar; datos o permisos faltantes.
3. **Color por función.** Valores, pares texto/fondo, acentos y significado de series.
4. **Tipografía.** Familias, pesos, roles, medidas/unidades y disponibilidad/fallbacks.
5. **Logo y recursos visuales.** Variantes, proporción, fondos y derechos pertinentes.
6. **Composición y layouts.** Regla común y familias de diapositivas relevantes.
7. **Gráficos y tablas.** Estilo, densidad, fuentes y elementos editables requeridos.
8. **Ejemplos de uso.** Reglas aplicadas correctamente y errores a evitar.
9. **Aplicación en Slides/PPTX.** Qué se adjunta/selecciona y qué pasos siguen pendientes.
10. **Fuentes, decisiones y comprobaciones.** Regla → clasificación → fuente/localizador → aprobación/pendiente. Separar un anexo privado cuando corresponda.

Cuando no exista información para una sección, escribir la limitación y la consecuencia práctica en lugar de rellenarla con un valor inventado. Mantener la guía completa pero proporcionada al alcance; no fabricar un manual de 50 páginas para una marca con un logo y una web.

## Brief de estilo

Crear `slides-style-brief.md` como una instrucción compacta y autocontenida, normalmente de 200–400 palabras cuando la marca lo permita. Contener:

- identidad y uso; referencia a la versión de la guía;
- reglas prioritarias confirmadas de color, fuentes, logo y composición;
- layouts/estilo de gráficos y tablas necesarios;
- sustituciones técnicas y propuestas no aprobadas, sin presentarlas como mandato;
- restricciones de contenido y editabilidad;
- cómo resolver carencias y qué no inventar.

No incrustar rutas de otro sandbox como si fueran portables. Referir assets por nombres inequívocos del paquete entregado y materializarlos en el entorno de la próxima tarea antes de utilizarlos. No depender de enlaces públicos temporales.

Al generar Slides, pasar las preferencias explícitas de marca a su entrada de estilo disponible; un brief guardado en disco no se aplica solo por existir. Si solo se entrega la guía, explicar al usuario cómo adjuntarla en el siguiente encargo.

## Formato de importación

La guía Markdown y el brief son documentos de trabajo: **no son un esquema nativo de importación verificado**. Si el importador exige PDF, PPTX u otro formato, convertir únicamente al requisito realmente inspeccionado y a la salida solicitada.

Si exige un archivo de guidelines, ese documento explica las reglas. Si exige una plantilla PPTX, el archivo contiene layouts de ejemplo creados mediante Slides, no un texto renombrado con extensión `.pptx`. Una colección de slides tampoco prueba que tenga masters corporativos o que el importador los conserve.

Registrar por separado: archivo aceptado, marca creada/seleccionable, deck generado usando esa marca y revisión de fidelidad. No inventar counters, campos, categorías ni identificadores.

## Cambio y entrega

Si se revisa una guía existente, preservar versión anterior y resumir qué reglas cambian y por qué. Si hay guía y deck, evitar copias contradictorias: señalar su versión compartida y diferencias técnicas conocidas.

Entregar únicamente lo pedido y los archivos mínimos para usarlo. No añadir automáticamente DOCX, PDF, JSON, traducciones, publicación, almacenamiento externo ni otra Skill de marca. Si se pide una presentación/PPTX, entregar el recurso oficial de Slides y exportar el archivo con ese flujo cuando esté solicitado. No describir un artefacto no exportado como archivo ya descargable.

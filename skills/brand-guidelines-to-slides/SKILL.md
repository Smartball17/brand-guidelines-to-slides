---
name: brand-guidelines-to-slides
description: "Convertir la información de una marca existente en guidelines operativas para presentaciones, un brief reutilizable de estilo y, cuando se solicite, una plantilla o presentación PPTX editable mediante Manus Slides. Usar al preparar brand guidelines para Slides, adaptar un manual corporativo a PowerPoint, reconstruir reglas de presentaciones desde fuentes oficiales o crear plantillas de slides de una marca existente. No usar para naming, logos nuevos, rebrands ni presentaciones genéricas sin trabajo de adaptación de marca."
metadata:
  version: "1.0.0"
---

# Brand Guidelines to Slides

Convertir evidencia de una identidad existente en un sistema reproducible de presentaciones. Mantener el método neutral: no incorporar marcas, clientes ni activos privados a esta Skill.

## 1. Fijar el encargo

Identificar marca, fuentes disponibles y resultado pedido: **guidelines**, **preparación para importar**, **plantilla PPTX** o **presentación de contenido**. No generar un deck cuando solo se pidan guidelines. Si faltan marca y fuentes, pedir un nombre/enlace o un manual; no elegir una marca por el usuario.

Distinguir reproducción autorizada de una marca de inspiración para una identidad propia. No hacer pasar una presentación de referencia por material oficial de terceros. Para naming, logo nuevo o rebrand, derivar al método de identidad correspondiente.

Inferir solo lo reversible: idioma del encargo y uso en pantalla. Proponer 16:9 si no hay formato existente; no sustituir un formato o identidad aprobados. Preguntar únicamente por una contradicción o decisión que cambie sustancialmente identidad, permisos o resultado.

## 2. Reunir y clasificar evidencia

Leer primero los materiales aportados y la Skill de marca del proyecto, si existe. Reutilizar identidades recuperables de `brand-identity-builder` sin regenerar logos ni copiar su workflow completo. Usar las Skills de lectura de documentos/imágenes según el archivo.

Si hace falta investigar, leer `deep-research` y consultar fuentes oficiales accesibles. No recorrer indiscriminadamente correo, Drive o repositorios privados bajo el pretexto de «toda la información disponible». Usar únicamente las fuentes y el alcance autorizados; pedir acceso solo al recurso necesario.

Priorizar instrucciones actuales del propietario y manual oficial pertinente, después plantillas aprobadas y finalmente web/publicaciones oficiales. Comparar fecha, mercado, submarca y canal: lo más reciente no siempre reemplaza un manual válido. No convertir el estilo de una web en norma universal de presentaciones.

Leer [criterios de evidencia](references/evidence-and-rights.md). Registrar fuente y localizador para cada decisión: **oficial**, **observada**, **propuesta** o **desconocida**. Una regla oficial no demuestra aprobación del usuario; una regla observada no se vuelve oficial por aceptarla. Resolver conflictos materiales antes de producir la versión final.

Detener la búsqueda cuando haya evidencia suficiente para las decisiones del encargo. Si falta una fuente, logo o licencia, entregar un resultado parcial con el hueco explícito; no fabricar activos, fuentes, códigos HEX ni especificaciones.

## 3. Traducir la marca al lenguaje de slides

Leer [sistema de presentaciones](references/presentation-system.md). Definir reglas concretas para color por función, tipografía, logo, composición, fotografía, gráficos y tablas. Usar adjetivos como orientación, no como sustituto de reglas y ejemplos; no exigir precisión falsa donde solo existe evidencia cualitativa.

Separar la identidad **confirmada** de las adaptaciones **propuestas**. No imponer una estética minimalista ni valores de otra marca. Registrar tamaños con unidades y contexto; no tratar px de un lienzo HTML/XML como pt físicos de PowerPoint.

Crear un conjunto pequeño de layouts reutilizables acorde al encargo. Para una plantilla sin esquema solicitado, proponer portada, separador, contenido, comparación, datos y cierre. Incluir un caso denso y reglas de tablas, no solo portadas bonitas. No copiar contenido comercial, métricas o testimonios de ejemplo como si fueran datos del cliente.

## 4. Preparar los entregables adecuados

Leer [contrato de salida](references/output-contract.md). Producir por defecto:

- `brand-presentation-guidelines.md`: guía operativa completa, trazable y sin secciones vacías.
- `slides-style-brief.md`: instrucciones compactas para aplicar la guía en un nuevo encargo de Slides; no reproducir toda la investigación.

Incluir fuentes y decisiones pendientes en la guía, o en un anexo separado si contiene información sensible. Mantener un solo sistema de decisiones; no crear JSON, CSS, traducciones o una Skill por marca salvo necesidad real y petición explícita.

**Importación de marca:** inspeccionar los campos, formatos y límites reales cuando el encargo lo requiera. No asumir que un PDF de guidelines, una plantilla `.pptx`, un brief y un `template_id` son intercambiables. Si no se puede inspeccionar, entregar la guía/brief como preparación, indicar «importación no verificada» y continuar las partes independientes. No afirmar que el importador admite Markdown ni inventar su esquema. Convertir la guía al formato aceptado solo después de verificarlo y cuando esté incluido en el encargo; usar la Skill documental adecuada.

**PPTX o deck:** leer [adaptador de Slides y PPTX](references/slides-pptx-adapter.md) y la Skill oficial `slides`. Crear o editar presentaciones exclusivamente mediante ese flujo; esta Skill aporta las reglas de marca, no sustituye el motor de Slides. Preferir PowerPoint nativo cuando se pidan elementos editables y no haya una selección de modo incompatible. No generar ni editar decks con scripts, `python-pptx` o HTML independiente. Una petición de formato no autoriza generación de imágenes de pago.

## 5. Validar con evidencia

Comprobar trazabilidad, integridad de assets autorizados, unidades, combinaciones de color, jerarquía, consistencia de layouts y ausencia de secretos/datos innecesarios. Verificar disponibilidad de fuentes y licencias pertinentes; documentar sustituciones, no prometer render idéntico en todos los equipos.

Si se pide una prueba o deck, inspeccionar portada, página densa y gráfico/tabla. Contrastar reglas observables con el resultado; registrar qué pasó, falló o no se pudo comprobar. Usar gráficos/tablas editables cuando se soliciten, nunca una diapositiva aplanada como falsa prueba de editabilidad. No inventar datos para llenar una demo: usar contenido neutro o datos de prueba claramente identificados.

Distinguir **guía preparada**, **deck creado**, **exportación PPTX comprobada**, **importación verificada** y **fidelidad revisada**. Ninguno implica los demás. No declarar accesibilidad certificada, compatibilidad universal ni activación automática de la Skill por una revisión manual.

## 6. Entregar sin ampliar permisos

Enlazar los archivos entregados y el recurso de Slides cuando exista. Resumir reglas confirmadas, adaptaciones propuestas, fuentes faltantes y comprobaciones pendientes. Indicar cómo adjuntar el brief o seleccionar la plantilla realmente importada en el próximo encargo, sin inventar identificadores.

Preferir materiales existentes y trabajo local. Antes de APIs, fuentes, imágenes o servicios facturables, avisar del coste conocido o incierto, ofrecer alternativa sin ese gasto externo y obtener autorización. No comprar, publicar, subir activos privados ni crear automatizaciones recurrentes por defecto. La autorización de guidelines no autoriza GitHub ni Academy. No sobrescribir entregables aprobados sin conservar la versión previa y aclarar el cambio.

## Ejemplos de activación

- «Convierte el manual y la plantilla de mi empresa en guidelines y un brief para Manus Slides».
- «Reconstruye desde esta web oficial reglas de presentaciones y prepara una plantilla PPTX; señala lo que deduzcas».
- No activar para «Inventa un nombre y un logo para una startup» ni para «Haz ocho slides sobre ventas» sin adaptación de marca.

## Dependencias

Método principal: lectura y escritura de archivos. Investigación: `deep-research` y herramientas web cuando sea necesaria. Presentaciones/plantillas: Skill y herramientas `slides`; PPTX nativo según disponibilidad real. PDF/DOCX: Skill documental pertinente solo si se pide esa salida. Las Skills de marca existentes son complementos opcionales. No requerir APIs de pago, credenciales ni scripts propios.

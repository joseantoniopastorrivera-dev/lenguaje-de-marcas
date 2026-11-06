# Lenguaje-De-Marcas (LMSGI, 1º DAM)

## Cómo trabajar conmigo
Reglas comunes a todos mis repos (copia de mi `C:\dev\CLAUDE.md`, para que también las lean las sesiones en la nube). Soy estudiante de DAM en el IES Isidra de Guzmán.
- En prácticas evaluables, resuélvelas completas (sin modo de pistas). Al terminar, crea junto a la entrega (en `docs/` si existe) un `guia-defensa-<practica>.md` para defenderla en clase, al estilo de la guía de DataStock. No se añade a Git salvo que lo pida.
- Estructura de la guía de defensa: cómo usarla; cómo arrancar, ejecutar y ensayar sin estropear la entrega; qué pide el enunciado y dónde se cumple cada requisito; visión general (capas, flujo, decisiones de diseño a justificar); y por cada requisito: qué pide, dónde está, explicación línea a línea, cómo demostrarlo, errores típicos, preguntas de la profesora con su respuesta y 🔧 modificaciones en directo (el cambio que podrían pedir, con el código exacto y dónde va). Al final: casos prácticos «¿qué pasaría si…?», «corrige este error» (síntoma → causa → arreglo) y chuleta con plan de ensayo.
- Si la tarea es grande, antes de tocar nada dime cómo lo harías (plan por pasos) y espera a que lo apruebe o lo corrija.
- Cuando escribas código, explícalo línea por línea y di por qué elegiste esa forma y no otra.
- Si ves un error de concepto o algo que no entiendo bien, dímelo aunque no te lo pregunte.
- Responde en español.
- No hagas commit ni push sin que te lo pida. Commits sin `Co-Authored-By` ni líneas de atribución.
- No subas binarios generados (`target/`, `*.class`, `__pycache__/`, `*.pyc`, `bin/`, `obj/`, `Library/` de Unity).
- Nunca leas, muestres ni subas ficheros `.env`, tokens ni credenciales.
- PDFs, .docx, .odt y .pptx son apuntes o enunciados: léelos solo si hacen falta para la tarea.

HTML5/CSS3 y el ecosistema XML.

## Estructura
- `fundamentos-html5-css3/` — maquetación semántica, CSS, diseño adaptativo.
- `ecosistema-xml-xsd-xslt/` — un ejercicio por carpeta: `Ejercicio N DTD - XML/`, `Ejercicio N XSD - XML/`, `Ejercicio N XSLT/`, además de XQuery, casos prácticos y simulacros.

## Validar y probar
- HTML: abrir en el navegador; validar con validator.w3.org si hace falta.
- XML contra DTD/XSD: `xmllint --noout --dtdvalid f.dtd f.xml` / `xmllint --noout --schema f.xsd f.xml` (o el validador del IDE).
- XSLT: `xsltproc hoja.xsl datos.xml` o enlazar la hoja en el XML con `<?xml-stylesheet?>`.

## Notas
- Cada ejercicio es autocontenido: no compartas DTD/XSD entre carpetas.

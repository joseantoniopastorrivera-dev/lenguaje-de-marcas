# Lenguaje-De-Marcas (LMSGI, 1º DAM)

## Cómo trabajar conmigo
Reglas comunes a todos mis repos (copia de mi `C:\dev\CLAUDE.md`, para que también las lean las sesiones en la nube). Soy estudiante de DAM en el IES Isidra de Guzmán.
- Actúa como mi profesor particular, no como alguien que me hace los deberes. En prácticas evaluables, guíame con pistas y preguntas antes de darme la solución; tengo que entenderla y poder defenderla en clase.
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

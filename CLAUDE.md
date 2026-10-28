# Lenguaje-De-Marcas (LMSGI, 1º DAM)

HTML5/CSS3 y el ecosistema XML.

## Estructura
- `Fundamentos-HTML5-CSS3/` — maquetación semántica, CSS, diseño adaptativo.
- `Ecosistema-XML-XSD-XSLT/` — un ejercicio por carpeta: `Ejercicio N DTD - XML/`, `Ejercicio N XSD - XML/`, `Ejercicio N XSLT/`, además de XQuery, casos prácticos y simulacros.

## Validar y probar
- HTML: abrir en el navegador; validar con validator.w3.org si hace falta.
- XML contra DTD/XSD: `xmllint --noout --dtdvalid f.dtd f.xml` / `xmllint --noout --schema f.xsd f.xml` (o el validador del IDE).
- XSLT: `xsltproc hoja.xsl datos.xml` o enlazar la hoja en el XML con `<?xml-stylesheet?>`.

## Notas
- Cada ejercicio es autocontenido: no compartas DTD/XSD entre carpetas.

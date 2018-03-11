# Clase 2 → Miércoles 14 de marzo

### HTML 

**Algunos apuntes iniciales:**  

- HTML es sigla de HyperText Markup Language. 

- HTML no es un lenguaje de programación. No tiene variables, condicionales, ciclos ni funciones. 

- HTML es un lenguaje descriptivo que ofrece lo necesario para estructurar el contenido de las páginas web.

- HTML5 es su versión más reciente, en ella se incorporan nuevos elementos semánticos, atributos y comportamientos.

#### Elementos

**Los elementos son el bloque constructivo más básico del HTML**. Un elemento HTML generalmente tiene una `<etiqueta de inicio>` y `</una etiqueta de cierre>`, entre las etiquetas hay un contenido, y dentro de la etiqueta de inicio pueden haber atributos.

En línea, pueden encontrar distintas referencias sobre los elementos HTML disponibles. Algunos ejemplos:  

- [Lista de Elementos HTML5](https://developer.mozilla.org/es/docs/HTML/HTML5/HTML5_lista_elementos)
- [HTML5 Cheat Sheet](https://websitesetup.org/HTML5-cheat-sheet.pdf)
- [Referencias de elementos HTML](https://developer.mozilla.org/es/docs/Web/HTML/Elemento)
- [Element Index | HTML5 Doctor](http://html5doctor.com/element-index/)

Para iniciar una página web, tenemos el elemento `<html>…</html>`. Dentro suyo deberíamos encontrar 2 elementos: Uno es `<head>…</head>`, el cual debe incluir información general acerca del documento, incluyendo su título, metadatos, enlaces a scripts y estilos. Otro elemento es `<body>…</body>`, el cual debe incluir el contenido del documento.

```
<html>
  <head>…</head>
  <body>…</body>
</html>
```

A esto deberíamos anteponer un `<!DOCTYPE html>`, que es una instrucción para que el navegador web "sepa" en qué versión de HTML está escrita la página.

```
<!DOCTYPE html>
<html>
  <head>…</head>
  <body>…</body>
</html>
```

- - - - 

[Clase anterior](https://github.com/profesorfaco/dno037-2018-01) | Próxima clase

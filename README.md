# Awesome Civic Tech [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Una lista colaborativa y curada de proyectos de tecnología cívica en México. Para agregar un nuevo proyecto o editar uno existente, consulta las [instrucciones de contribución](CONTRIBUIR.md).

## ¿Cómo funciona este sitio?

El sitio está construido en [Jekyll](https://jekyllrb.com), un generador de sitios estáticos. La lista de proyectos cívicos se encuentran en la carpeta `-docs` a manera de documentos escritos en [Markdown](https://www.markdownguide.org/) que se leen como una colección Jekyll. Cuando se genera el sitio (cada vez que se agrega o cambia un archivo), los proyectos (cada documento) se renderiza usando las plantillas y estilos definidos y se publica bajo la ruta `/[NOMBRE_DEL_ARCHIVO/]`.

## ¿Qué más hay en esta carpeta?

* `_layouts` - las plantillas que controlan la presentación del sitio
* `assets` - hojas de estilo, javascripts y bibliotecas de terceros

## Correr el sitio de manera local

Desde el directorio **`docs/`** :

1. `bundle install`
2. `bundle exec jekyll serve`
3. Abre `localhost:4000` en tu navegador.

<p align="center">
<img src="http://codeandomexico.org/resources/img/codeandomexico.png" width="500" alt="Codeando México"><br>
<a href="http://www.codeandomexico.org/" target="_blank"><img src="https://img.shields.io/badge/website-CodeandoMexico-00D88E.svg"></a>
<a href="http://slack.codeandomexico.org/" target="_blank"><img src="https://img.shields.io/badge/slack-CodeandoMexico-EC0E4F.svg"></a>
</p>


# Awesome Civic Tech

**tl;dr:** Plataforma que alberga una lista curada de tecnología cívica en México.


## Tabla de contenidos

- [Acerca del proyecto](#acerca-del-proyecto)
- [Contribuye](#contribuye)
- [Atribuciones](#atribuciones)


## Acerca del proyecto

Este es un proyecto de la comunidad que busca centralizar todas las tecnologías cívicas que existen en nuestro país. El sitio puedes verlo en el [siguiente enlace](https://codeandomexico.github.io//awesome-civic-tech/).

Si te interesa contribuir al proyecto, echa un vistazo a la siguiente sección.


## Contribuye

¡Cualquier sugerencia o contribución a este repositorio es bien recibida!

Si necesita ayuda, escribe directamente a <equipo@codeandomexico.org> o en nuestro [Slack](http://slack.codeandomexico.org/).

### Añade un evento

1. Crea un fork del repositorio a tu cuenta de GitHub.

2. Clona tu fork del repo:
   ```bash
   git clone https://github.com/<TU-USUARIO>/eventos-globales.git
   cd awesome-civic-tech/
   ```

3. Crea una rama con el nombre de la tecnología cívica que deseas agregar, en este ejemplo supongamos que agregaré la [plantilla](https://github.com/CodeandoMexico/awesome-civic-tech/blob/master/_posts/2020-01-22-plantilla.md) del sitio:
   ```bash
   git checkout -b plantilla  # esto creará una nueva rama de nombre 'plantilla' y se moverá a ella
   ```

4. Crea el archivo que contenga la información del evento. El archivo deberá ser guardado en la carpeta [`_posts`](https://github.com/CodeandoMexico/awesome-civic-tech/tree/master/_posts) con el formato `AAAA-MM-DD-tecnología.md`, donde `AAAA`, `MM` y `DD` corresponden al año, mes y día en que se agrega la tecnología al directorio, respectivamente. Puedes tomar como referencia justamente el archivo [plantilla](https://github.com/CodeandoMexico/awesome-civic-tech/blob/master/_posts/2020-01-22-plantilla.md).

5. Crea un Pull Request (PR) de la rama que has creado a la rama `master` del repositorio original y solicita una revisión a **@ricardomiron**.

**NOTA:** Por favor realiza un PR por tecnología.



### Modifica el sitio

Por favor abre un issue donde menciones los cambios que te gustaría agregar y menciona a **@ricardomiron**. En dado caso, se te asignaría el issue y esperaremos tu PR donde te pediremos solicites una revisión a **@ricardomiron** para revisar y aceptar tus cambios al sitio.

Si deseas correr el sitio de manera local, ejecuta los siguientes pasos:

1. Instala los requerimientos:
   ```bash
   bundle install
   ```

2. Corre el servidor:
   ```bash
   bundle exec jekyll serve
   ```

3. Abre <http://localhost:4000/awesome-civic-tech> en tu navegador.

El comando del paso 2 te permite hacer modificaciones y visualizar los cambios en tiempo real dentro de tu localhost.


## Atribuciones

- Sitio web basado en [Pintereso Jekyll Theme](https://www.wowthemes.net/pintereso-free-bootstrap-jekyll-theme/)
- Gracias a [Richard](https://github.com/ricardomiron) y [Rodo](https://github.com/RodolfoFerro) por las contribuciones iniciales
- `{}` y contenidos con ❤️ por la [comunidad de Codeando México](http://slack.codeandomexico.org/)

---

Este sitio cuenta con una licencia MIT.


## APIs de datos públicos (Apify)

- [Sesiones de concejos municipales MCP (Legistar)](https://apify.com/publicrecords/legistar-meetings-scraper) - Sesiones de concejos municipales, puntos del orden del día y documentos de cualquier ciudad en Legistar, con enlaces a la fuente (Apify).
- [USAspending MCP: contratos y subvenciones federales adjudicados](https://apify.com/publicrecords/usaspending-awards-scraper) - Contratos y subvenciones federales de EE. UU. adjudicados según USAspending, por agencia, beneficiario, NAICS y periodo (Apify).
- [Grants.gov MCP: subvenciones federales abiertas de EE. UU.](https://apify.com/publicrecords/grants-gov-scraper) - Subvenciones federales de EE. UU. abiertas en Grants.gov: agencia, plazo, requisitos y enlace a la fuente (Apify).
- [Contratos federales de EE. UU. MCP: SAM.gov + Grants.gov](https://apify.com/publicrecords/govcon-opportunity-feed) - Nuevos anuncios de contratos y subvenciones federales de EE. UU. de SAM.gov y Grants.gov en un solo feed, con enlaces (Apify).
- [Licitaciones UE TED MCP: anuncios de contratación diarios](https://apify.com/publicrecords/eu-ted-notices-scraper) - Anuncios de contratación pública de la UE desde TED (Tenders Electronic Daily): comprador, CPV, valor, plazo y enlace (Apify).
- [Licitaciones del Reino Unido MCP: Find a Tender y Contracts Finder](https://apify.com/publicrecords/uk-find-a-tender-scraper) - Licitaciones del gobierno británico de Find a Tender y Contracts Finder: comprador, valor, plazo y enlace (Apify).

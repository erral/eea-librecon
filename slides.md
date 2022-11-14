---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: "text-center"
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false
# use UnoCSS
css: unocss
---

# Uso e implicación de una agencia de la UE en el desarrollo de productos de software libre

Librecon 2022 - Bilbo

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---

# $ whoami

- Mikel Larreategi @erralin
- Desarrollador python en CodeSyntax desde 2004

<br />
<img src="/plone_logo.png" />
<br/>
<img src="/django-logo-positive.png" width="200"/>
<br/>
<img src="/Python-logo-notext.svg" />

---

# EEA: European Environment Agency

- Sede en Copenhague, Dinamarca
- Proveer información independiente sobre el medio ambiente
- Ayudar en el desarrollo sostenible
- Dar información relevante a los agentes políticos y público
- 32 países + colaboradores : UE + Noruega + Islandia + Turquía + UK + balcanes

<br/>
<img src="/eealogo-web.png" />

---

# Estrategia web

- Departamento IT: DIS - Data and Information Services
- DIS1: Information Systems and ICT
- DIS2: Data Management
- DIS3: Geospatial Information Services

---

# DIS1: Information Systems and ICT - Web

- La gran mayoría de la presencia y desarrollo web depende de DIS1
- Tiene diversos contratos-marco plurianuales
- Se encarga también de la infraestructura y mantenimiento web

---

# Plone como CMS de referencia

- La EEA eligió Plone hace muchos años como CMS de referencia
- Utiliza Plone en los desarrollos web dependientes de DIS1
- Tiene contratistas que trabajan en esos desarrollos
- Poco desarrollo <em>in-house</em>

<br/>
<img src="/plone_logo.png" />

---

# Liderazgo de DIS1

- Ideas claras: todo tiene que ser reutilizable
- Hay que estar en los lugares de decisión
- Hay que colaborar con la comunidad
- Todo nuestro desarrollo tiene que ser libre: <strong>public money, public code</strong>

---

# Cómo se hace (1)

- Hasta hace dos años:
  - Publicar add-ons
  - Funcionalidades adicionales que no tenía el CMS
  - Funcionalidades vistosas
  - Addons genéricos reutilizables
  - Uno de los más populares: eea.facetednavigation es muy utilizado por la comunidad

---

# Cómo se hace (y 2)

- Desde hace dos años:
  - Plone dio un salto evolutivo
  - Front-end escrito en react (llamado Volto) contra un API que expone el 95% de las funcionalidades del back-end
  - La EEA vio una oportunidad
  - Invirtió su contrato-marco en entrar en el desarrollo del front-end

<br/>
 <img src="/plone_logo.png" /> <br/><img src="/VoltoLogoEra2.png" width="100"/>

---

# Desarrollo de Volto

- Utilizando el contrato marco, entró a desarrollar add-ons
- Promovió las buenas prácticas en el nuevo front-end
- Un miembro del equipo del contratista se convirtió en desarrollador principal de Volto
- El contrato marco sirve para mejorar el front-end
- Volto va a ser el nuevo front-end por defecto en Plone 6 (ya en versión beta 3)

---

# Desarrollo

- Estando en el lugar donde se decide las cosas, se condiciona el desarrollo del software
- Plone es una comunidad abierta una <em>do-cracy</em>, es decir, se hace lo que quieran los desarrolladores
- No hay una empresa que decide qué se desarrolla, es la comunidad la que decide y debate
- Lo que puede hacer una agencia europea es colaborar en la comunidad poniendo desarrolladores
- Promover el software libre
- No solo decir que se usa Wordpress (o cualquier otro)

<!--
No estamos hablando de que solo se usa el software, sino que se desarrolla un producto que es core-business para la agencia y para su presencia web.

De alguna forma "condiciona" el desarrollo, o por lo menos intenta que se desarrolle lo que ella necesita, pero no solo esponsorizando, sino poniendo desarrolladores, a través de contratos de desarrollo para mejorar dicho software

-->

---

# Enseñar y dar a conocer

- No solo es desarrollar
- Es documentar
- Es testear
- Es promover

<!--

Casi todo el equipo de desarrollo que participa en el contrato marco participa en la comunidad Plone, participa en las Conferencias y Sprints, y da charlas para mostrar cómo se utiliza el software en la EEA y cómo se desarrollan las nuevas funcionalidades que han ayudado a desarrollar.

No todo es código, también hay parte de enseñar

-->

---

# Desarrollo en abierto

- https://github.com/eea
- Todo el desarrollo en abierto

<!--

Y esta filosofía de colaborar con la comunidad, lleva a la EEA ha desarrollar en público. Es decir, no solo "publica" el código en GitHub, sino que, el desarrollo se realiza en GitHub y todo el proceso se sigue allí.

-->

---

# Herramientas libres para publicación

- Redmine
- GitHub
- Docker
- Rancher
- Jenkins
- Kubernetes
- Keycloak
- OpenLDAP

<!--

Y no solo hablamos de software web, la infraestructura que utiliza el departamento DIS1 está basado también en software libre, y todos los pipelines de publicación de web se basan en pipelines sobre Jenkins (se está evaluando ahora su paso a GitHub Actions u otras herramientas), y también la infraestructura básica construida sobre Rancher versión 1.6

-->

---

# Conclusiones

- No solo utilizar, colaborar
- No solo hablar, hacer
- No solo hacer, enseñar

<!--

Así, con estas tres premisas: colaborar - hacer - enseñar, creemos que la EEA es una gran parte de la comunidad Plone y Volto en estos momentos, su participación ha sido clave para el éxito de la nueva versión de Plone, la versión 6, y en ello hay que agredecer la visión de Antonio de Marinis, el líder del equipo de DIS1, que ha introducido esta visión tanto en la EEA como en los contratos que gestiona él, y así ha conseguido promover las tecnologías libres, que es de lo que se trata.

-->

---

# Eskerrik asko

<img src="/life-of-brian-stoning.jpg">

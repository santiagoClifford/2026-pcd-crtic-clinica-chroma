# 2026-pcd-crtic-clinica-chroma

11:30 - 2pm en crtic, parque o'higgins, santiago de chile.

# info sobre persona instructora

## en general

- aarón montoya-moraga
- pronombre elle

## pergaminos

- ingeniería civil electricista, pontificia universidad católica de chile
- magíster en arte electrónico, interactive telecommunications program, new york university
- magíster en artes mediales y ciencias, media lab. massachussets institute of technology

## en udp

- profesore asistente
  - dis8644 taller de diseño de máquinas electrónicas, en conjunto con profesor matías serrano
  - dis8645 taller de diseño de máquinas computacionales, en conjunto con profesor matías serrano
  - dis9079 interacciones inalámbricas
  - dis09214 pensamiento computacional

- persona directora, laboratorio de interacción digital
- investigación en pregrado
- <https://github.com/disenoUDP>
- <https://disenoudp.github.io/lid>

## en usach

- estudiante, doctorado de artes y humanidades, instituto de estudios avanzados

## en industria

- persona fundadora de piruetas SpA, estudio de arte electrónico y computacional
  - esculturas paramétricas
  - placas electrónicas
  - distribución de artistas y diseñadores locales
  - <https://instagram.com/piruetas.xyz>
- <https://piruetas.xyz/tienda>

## info sobre diseño udp

diseño universidad diego portales

históricamente teníamos 2 menciones: industrial y gráfico.

esta década abrió la mención de textil e indumentaria, y el año pasado con la malla 9.0 celebrando los 30 años de la escuela, inauguramos una cuarta mención de interacción digital.

hemos sumado académiques para realizar investigación y docencia en pregrado en cursos de electrónica y programación en las siguientes áreas:

- segundo año: dentro de la oferta de talleres, dos de introducción al diseño de interacción digital
- segundo año: dos cursos obligatorios de introducción a la programación y al diseño basado en datos.
- tercer y cuarto año: dentro de la oferta de talleres, cuatro talleres de electrónica, programación, visualización de datos, espacios interactivos
- quinto año: un sección de seminario y de título dedicada a la investigación y desarrollo de interfaces físicas y digitales.

## herramientas computaciones de fuente abierta para arte y diseño

existe ogente nerd artista que quiere programar, solía ser duro porque generalmente los cursos introductorios no estaban orientados a sus intereses, solían ser en escuelas de ingeniería, matemtática o física, y de código orientado a texto y a procesamiento de datos, como sumas, restas, cálculo, etc.

a través de los años han habido muchos esfuerzos en usar la computación como un medio plástico de expresión artística y de diseño.

una pionera que quiero siempre destacar es muriel cooper, una de las fundadoras de mit media lab, donde trabajaba en su visual language workshop, y donde se desarrollaron pioneros experimentos computacionales tipográficos

tras su muerte, el grupo de investigación es refundado con el nombre aesthetics + computation group, por el profesor john maeda, estudiante de muriel cooper. john maeda lanza una herramienta y libro fundacional del rubro: design by numbers, una herramienta de dibujo programático de 100 x 100 pixeles.

dos estudiantes de ese laboratorio y colaboradores de esa herramienta, casey reas y ben fry, desafían los consejos de su mentor john maeda, y lanzan processing en 2001, una herramienta vigente hasta el día de hoy.

Processing es una biblioteca y entorno de programación cuyo lenguaje es Java, que ha sido y sigue siendo muy usado en el desarrollo de apps multiplataforma, permite exportar aplicaciones que funcionan en distintos sistemas operativos en dispositivos de escritorio y móviles.

Casey Reas fue profesor mentor de Hernando Barragán en el Interaction Design Institute de Ivrea en Iatlia donde tomó la filosofía detrás de Processing y la implementó en microcontroladores, lanzando el proyecto Wiring, que se convirtió en la base del proyecto Arduino como lo conocemos hoy. más info aquí <https://arduinohistory.github.io/>.

este año Processing cumple 25 años, y desde hace ya más de una década existe la processing foundation, donde se congregan los esfuerzos de mantener viva esta comunidad, ofreciendo las herramientas de la fundación de forma gratuita, distribuyéndolas como código libre, y apoyando con becas y residencias el desarrollo de prácticas de arte y diseño en torno a la programación.

el año 2013 la artista y programadora Lauren Lee McCarthy ganó una beca de la Processing Foundation, y con ello propuso una respuesta a Processing si fuera lanzada una década después, y esta respuesta fue p5.js, que comparte la filosofía detrás de Processing, pero es una biblioteca de JavaScript que permite hacer proyectos web.

paulatinamente p5.js ha sido adoptado por escuelas de artes y diseño para enseñar programación, y es la herramienta que estamos usando este año inaugural en diseño udp de nuestro primer curso de programación obligatorio de la malla de estudios.

de hecho hoy es el examen de este curso, y por eso lo hicimos coincidir con processing community da 2026, nos emociona mucho estar aquí celebrando este hito, que continúa mañana sábado en la facultad de arquitectura, arte y diseño de la universidad diego portales, donde tendremos muestras de obras mediales, charlas invitadas y conciertos audiovisuales hechos con código.

toda la info en instagram de @lid.udp, y también en <https://disenoudp.github.io/lid>

## clínica de hoy

nuestro desafío hoy es usar código para generar el efecto de chroma, para eso propongo varios aspectos:

- color como fenómeno físico y como percepción humana, y su modelameiento y producción en computación.
- uso de cámara en vivo en  páginas web con p5.js
- manipulación de color en vivo con p5.js
- detección de presencia humana con ml5.js

## herramientas

- <https://p5js.org/>: Lauren Lee McCarthy et al
- <https://ml5js.org/>: Daniel Shiffman et al

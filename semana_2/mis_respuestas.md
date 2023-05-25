# Preguntas de la semana

A continuación encontrarás una seríe de cuestiones que debes responder en un
documento Markdown llamado 'mis_respuestas.md'. Este fichero lo deberás ubicar en el mismo directorio que la
fuente de esta página en tu fork del repositorio del taller. En [la sección "Resolviendo las
preguntas semanales" de la página "Cómo trabajar con este
taller"](../material_suplementario/como_trabajar/como_trabajar.md#resolviendo-las-preguntas-semanales) encontrarás indicaciones sobre
cómo hacerlo.

## Pregunta 1

> ¿Para qué se usa el fichero «setup.py» en una librería de Python? ¿Qué es el fichero «pyproject.toml»?

### Respuesta

Setup.py: Facilita la instalación y distribución de la librería. Contiene los datos necesarios para su distribución como el nombre de la librería,
la versión, descripción, autor, requisitos de instalación. 
Pyproject.toml se utiliza en conjunto con herramientas como "Poetry" para especificar dependencias y configuraciones del proyecto. Contiene 
información relacionada a dependencias, versiones de python compatibles y configuraciones para la gestión del proyecto.


## Pregunta 2

> ¿Para qué se usa el fichero «pyproject.toml» en una librería de Python?

### Respuesta

El fichero "pyproject.toml" contiene varias secciones y claves que definen diferentes aspectos del proyecto. Por ejemplo, contiene secciones como 
"build-system" donde se especifica la versión requerida de la herramienta de construcción. Existe otra sección que se utiliza para configurar 
herramientas específicas del proyecto.  Otras secciones especifican las dependencias del proyecto, así como los paquetes necesarios para el desarrollo 
de pruebas.


## Pregunta 3

> ¿Qué es el lenguaje o el formato de fichero TOML?

### Respuesta

TOML (Tom's Obvious, Minimal Language) es un formato de usado por ficheros como pyproject.toml. Fue creado pensado en la simplicidad y facilidad de uso 
para humanos y computadoras. Es más legible que otros formatos de configuración como JSON o YAML. Algunas características que lo hacen popular son la 
sencillez, estructura jerárquica y la posibilidad de añadir comentarios al código.


## Pregunta 4

> ¿Qué incluirías en tu librería, un fichero «pyproject.toml» o un «setup.py»?

### Respuesta

En una librería de Python, típicamente se incluye el fichero "setup.py" para definir la configuración de distribución e instalación de la librería. 
Aunque el fichero "pyproject.toml" se utiliza para proyectos de Python en general, incluyendo aplicaciones y librerías, el fichero "setup.py" es 
más específico para las librerías y su distribución.


## Pregunta 5

> ¿Qué significan en el contexto del desarrollo de una herramienta computacional el término «Integración
> Continua» (CI, Continuous Integration)?

### Respuesta

Es una forma de trabajo en la que constantemente se combina el trabajo de diferentes desarrolladores en un repositorio compartido. 
Esto implica realizar pruebas constantemente para detectar y resolver problemas de integración  con rapidez y evitar acumulación de 
conflictos o errores que serán más difíciles de resolver en el futuro. Esto puede lograrse a través de un gestor de versiones como GitHub.
 


## Pregunta 6

> ¿Qué significan en el contexto del desarrollo de una herramienta computacional el término «Distribución
> Continua» (CD, Continuous Distribution)?

### Respuesta

Forma de trabajo en la que los desarrolladores se enfocan en entregar versiones de software de forma rápida, confiable y repetible en ciclos 
cortos. Es un proceso automatizado que permite implementar cambios en el código en un entorno de producción con menor esfuerzo y riesgo posible.



## Pregunta 7

> ¿Para qué sirven las «GitHub Actions»?

### Respuesta

Es una característica de GitHub que permiten la automatización de tareas dentro de un repositorio. Se usan comúnmente en para integración y entrega 
continua. Ejecutar tareas personalizadas en respuesta a eventos específicos en el repositorio, como la creación de pull requests, el envío de 
comentarios o la publicación de nuevas versiones y dichas tareas se definen mediante archivos de configuración YAML.



## Pregunta 8

> Menciona 4 herramientas para facilitar el proceso de CI/CD. (Aquí te regalamos la primera: «Travis CI»)

### Respuesta

Jenkins, CircleCI, GitLab CI/CD, AWS CodePipeline. Todas permiten automatizar tareas relacionadas con integración y distribución continua, 
control de versiones, ejecutar pruebas para detectar errores y retroalimentación al desarrollador.



## Pregunta 9

> ¿Qué es «GitHub Pages»?

### Respuesta

GitHub Pages es un servicio de alojamiento gratuito proporcionado por GitHub que permite crear sitios web desde repositorios de GitHub. 
Permite publicar páginas web con contenido estático como documentación o blogs utilizando archivos como HTML, CSS, JavaScript entre otros. 
Los sitios se actualizan automáticamente cada que se realizan cambios en el repositorio. Además, GitHub Pages permite tener una URL 
personalizada para el sitio web.



## Pregunta 10

> ¿Qué es el MolSSI? ¿Puedes encontrar allí orientación para aprender a desarrollar tu librería?

### Respuesta

El MolSSI (Molecular Sciences Software Institute) ofrece recursos y orientación para aprender a desarrollar software en el campo 
de las ciencias moleculares. A través de su sitio web y recursos en línea, proporcionan tutoriales, documentación, cursos y 
talleres para ayudar a los investigadores a adquirir habilidades de desarrollo de software para desarrollar librerías propias.



## Pregunta 11

> ¿Qué es una «Cookiecutter» en el contexto del desarrollo de software? ¿Para qué sirve este repositorio?

### Respuesta

Es una herramienta que facilita la creación de proyectos basados en esqueletos (plantillas) predefinidas, con archivos y directorios 
preconfigurados, configuraciones iniciales y otros elementos comunes listos para usar. El repositorio sirve como "hub" de plantillas 
creadas por la comunidad para diferentes lenguajes de programación y marcos de trabajo. Estas plantillas se pueden utilizar como 
punto de partida para crear proyectos específicos y personalizados de manera rápida y fácil.


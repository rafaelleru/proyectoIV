# Descripción
Proyecto para la asignatura "Infraestructura Virtual" de la Escuela Técnica Superior de Ingenierías Informática y de Telecomunicación.
El proyecto se basa en una cola de trabajos para mantener el orden y prioridad sobre trabajos que se manden a una plataforma. 

# Herramientas
Las herramientas y servicios para desarrollar y desplegar el proyecto serán:

* [Python](https://www.python.org/); como principal lenguaje de programación.
* [hug](http://www.hug.rest/); como framework para desarrollar la API.
* [unittest](https://docs.python.org/3/library/unittest.html); como framework para los test unitarios.
* [Docker](https://www.docker.com/), [Azure](https://azure.microsoft.com/es-es/) o [Heroku](https://www.heroku.com/) y [Travis-CI](https://travis-ci.org); para la integración y el despliege.
* [Elasticsearch](https://www.elastic.co/); para la base de datos. 

# Integración Continua
Ahora mismo cuento con una clase básica ("WorkWaitQueue") para probar el funcionamiento de los test y su integración con [Travis-CI](https://travis-ci.org).
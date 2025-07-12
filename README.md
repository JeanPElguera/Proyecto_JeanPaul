1.Resumen

Este proyecto se centra en el desarrollo de una aplicación de escritorio para la gestión de una armería, utilizando Java y la herramienta WindowsBuilder en Eclipse para la creación de interfaces gráficas. La aplicación incluye funcionalidades avanzadas para la administración de cuentas de usuarios, el manejo de un catálogo de armas dividido en tres categorías, y herramientas administrativas accesibles mediante consola. La base de datos se aloja en la nube a través de MongoDB Atlas, con soporte para consultas locales utilizando MongoDB Compass.

2.Introducción

En este proyecto se desarrollará una aplicación de escritorio para la gestión de una armería, explicando su funcionamiento, las funcionalidades implementadas y las tecnologías utilizadas. Se abordarán las características principales del sistema, cómo se gestionan las cuentas de usuario, el catálogo de armas y las herramientas administrativas disponibles. También se detalla el uso de la base de datos y su interacción con la aplicación.
Se explicará la estructura y funcionamiento de la aplicación, desde la creación de interfaces gráficas hasta la lógica de negocio que permite gestionar los datos almacenados en la nube mediante MongoDB Atlas.

2.1 Descripción del proyecto
La aplicación de escritorio para la gestión de una armería tiene como objetivo facilitar la administración de cuentas de usuarios, el manejo de un catálogo dividido en pistolas, rifles y granadas, y la supervisión avanzada por medio de una consola administrativa.
Se utiliza Eclipse con WindowsBuilder para diseñar las interfaces gráficas, haciendo el sistema intuitivo y funcional. En el backend, se emplea Java para desarrollar la lógica que soporta la gestión de datos y su interacción con la base de datos. La información se almacena en MongoDB Atlas, una solución en la nube que permite alta disponibilidad y seguridad. Además, se realizan consultas locales utilizando MongoDB Compass para facilitar el análisis de datos.
La infraestructura de la aplicación incluye:
Gestión de cuentas con funcionalidades como creación, modificación y eliminación.
Gestión del catálogo, dividido en tres categorías principales de armas: pistolas, rifles y granadas.
Herramientas administrativas avanzadas accesibles mediante una consola, permitiendo la supervisión completa de cuentas, compras y stock.
El proyecto busca proporcionar una solución completa para la administración eficiente de una armería, integrando herramientas modernas y prácticas de desarrollo para lograr un producto funcional y robusto.

3. Planteamiento del problema

La gestión eficiente de una armería enfrenta desafíos como el manejo desorganizado de cuentas de usuarios, el control inadecuado del catálogo de armas y la falta de herramientas centralizadas para supervisar operaciones. Esto puede ocasionar errores en inventarios, registros y administración general. Por ello, es necesario desarrollar una aplicación integral que facilite estas tareas, optimizando procesos y mejorando su eficiencia.

5. Objetivos del proyecto

Los objetivos del proyecto son los siguientes:
Desarrollar una aplicación de escritorio para la gestión integral de una armería, utilizando Java y WindowsBuilder para las interfaces gráficas.
Implementar funcionalidades que permitan la administración de cuentas de usuarios, la gestión de un catálogo de armas y el control avanzado mediante una consola administrativa.
Integrar MongoDB Atlas como base de datos en la nube y MongoDB Compass para consultas locales, garantizando el almacenamiento eficiente y seguro de los datos.

6. Fundamentos teóricos

5.1 Conceptos básicos de gestión de base de datos en una aplicación de gestión
La base de datos es un componente fundamental en cualquier aplicación que maneje grandes cantidades de información estructurada. En el caso de una aplicación de gestión de una armería, como la que se está desarrollando, se utiliza MongoDB como sistema de base de datos NoSQL para almacenar y organizar la información de los clientes, las armas y las compras realizadas. MongoDB es una base de datos orientada a documentos que ofrece flexibilidad y escalabilidad para manejar grandes volúmenes de datos, lo que es ideal para este tipo de aplicaciones.
Modo Administrador por Consola
El administrador tendrá acceso a herramientas avanzadas desde la consola para la gestión tanto de usuarios como del catálogo. Las funcionalidades incluyen:
-Lista de cuentas: Visualizar todas las cuentas registradas.
-Agregar cuenta: Registrar nuevas cuentas directamente desde la consola.
-Consulta cuenta: Mostrar detalles de una cuenta específica, incluyendo las compras realizadas.
-Eliminar cuenta: Eliminar una cuenta ingresando su correo electrónico.
-Mostrar stock: Consultar el stock general de todas las armas disponibles.
-Lista de armas por tipo: Filtrar y mostrar el stock de pistolas, rifles o granadas según su categoría.
-Eliminar arma comprada: Eliminar un arma específica asociada a una cuenta, especificando el correo del usuario.
-Aumentar stock de arma: Incrementar la cantidad de un arma específica en el stock.
-Lista de cuentas con compras: Mostrar las cuentas registradas junto con las compras realizadas.
-Lista de compras realizadas: Consultar un historial general de compras.
-Cantidad de cuentas creadas: Mostrar el número total de cuentas registradas.
-Cantidad de armas compradas: Mostrar la cantidad total de armas adquiridas por los usuarios.
-Modificar cuenta: Actualizar los datos de cualquier cuenta existente.

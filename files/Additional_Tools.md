# Herramientas adicionales

--------------------------------------------------------------------------------


## Alternativas a GitHub

Aunque GitHub hoy en día es la plataforma para administración de proyectos más popular, no es la única, pues existen otras alternativas, cada una con diferentes ventajas y desventajas o con propósitos más particulares. A continuación hablaremos brevemente sobre algunas de ellas.

- [GitLab](https://gitlab.com/): GitLab es una plataforma de desarrollo colaborativo que ofrece alojamiento de repositorios Git, seguimiento de problemas, integración continua y más. Es similar a GitHub en términos de funcionalidades y es ampliamente utilizado en proyectos de software.

- [Bitbucket](https://bitbucket.org/): Bitbucket es otra opción popular que admite tanto Git como Mercurial. Ofrece alojamiento de repositorios privados y públicos, seguimiento de problemas, integración con otras herramientas de desarrollo y colaboración.

- [AWS CodeCommit](https://aws.amazon.com/es/codecommit/): AWS CodeCommit es un servicio de alojamiento de repositorios Git completamente administrado ofrecido por Amazon Web Services (AWS). Proporciona almacenamiento seguro y escalable para tus repositorios de Git en la nube.

- [Perforce Helix Core](https://www.perforce.com/products/helix-core): Es una solución de control de versiones diseñada específicamente para el desarrollo de juegos. Proporciona almacenamiento y seguimiento de cambios de archivos binarios, lo que lo hace ideal para proyectos de videojuegos que contienen muchos activos multimedia.

- [Unity Collaborate](https://docs.unity3d.com/2020.1/Documentation/Manual/UnityCollaborate.html): Es una funcionalidad integrada en el motor de desarrollo de videojuegos Unity. Permite a los desarrolladores trabajar en equipo y colaborar en proyectos de Unity almacenados en la nube. Proporciona control de versiones, seguimiento de cambios y resolución de conflictos.

- [Git LFS (Large File Storage)](https://git-lfs.com/): Es una extensión de Git que permite almacenar y gestionar archivos grandes, como recursos de videojuegos, de manera eficiente. Git LFS funciona junto con plataformas de alojamiento de repositorios como GitHub, GitLab o Bitbucket.

Estas son solo algunas de las alternativas populares a GitHub. Cada una tiene sus propias características y enfoques, por lo que te recomendaría explorarlas y evaluar cuál se ajusta mejor a tus necesidades específicas.


## Interfaces de usuarios (GUI) para Git

En ocasiones, al estar trabajando con varios usuarios y/o con múltiples ramas, será difícil recordar que usuario hizo que modificación y como están conectadas todas las ramas. Por lo que poseer herramientas para una fácil visualización puede ayudar mucho, tanto si estás empezando a aprender a usar Git como si ya tienes una gran destreza al utilizarlos. Existen diferentes opciones, algunas de ellas las presentamos a continuación.

- [GitKraken](https://www.gitkraken.com/): GitKraken es una herramienta de interfaz gráfica para Git que proporciona una experiencia visual para trabajar con repositorios Git. Ofrece una amplia gama de características, como la visualización del historial de commits, la administración de ramas, la resolución de conflictos y la integración con plataformas de alojamiento como GitHub y Bitbucket. Es de las mas completas y populares peeo quiza para alguien sin mucha experiencia pueda resultar compleja.

- [SourceTree](https://www.sourcetreeapp.com/): SourceTree es otra herramienta visual de Git que ofrece una interfaz de usuario fácil de usar. Proporciona una visualización clara del historial de commits, ramas y etiquetas, y permite realizar acciones comunes de Git, como fusionar ramas y gestionar conflictos.

- [Gitg](https://wiki.gnome.org/Apps/Gitg): Muy simular a SourceTree, pues es muy sencilla de utilizar, por lo que es perfecta para usuarios sin mucha experiencia. Teniendo como atractivo principal en esta herramienta que, a diferencia de SourceTree, Gitg sí está disponible en el entorno de sistemas Linux.

- [GitExtensions](https://gitextensions.github.io/): GitExtensions es una herramienta de interfaz gráfica para Git que ofrece una amplia gama de funcionalidades para trabajar con repositorios Git. Proporciona una interfaz intuitiva para realizar operaciones de Git, como la creación de ramas, la resolución de conflictos y la visualización del historial de commits.

- [SmartGit](https://www.syntevo.com/smartgit/): SmartGit es una herramienta multiplataforma para trabajar con repositorios Git. Ofrece una interfaz visual amigable y funcionalidades avanzadas, como la visualización del historial de commits, la resolución de conflictos y la gestión de ramas y etiquetas.


## Pre-commit

La herramienta "pre-commit" es una utilidad que se utiliza en el contexto de Git para ejecutar una serie de comprobaciones o acciones automatizadas antes de que se realice un commit en un repositorio. Su propósito principal es asegurar que los cambios que se están a punto de confirmar cumplan con ciertos estándares o requisitos establecidos por el equipo de desarrollo.

Las funciones y usos de "pre-commit" pueden variar según la configuración y las necesidades específicas del proyecto, pero aquí hay algunos ejemplos comunes de cómo se puede utilizar:

1. Linting de código: "pre-commit" puede ejecutar herramientas de linting (como ESLint, Pylint, RuboCop, entre otras) para verificar el estilo, la calidad y las convenciones de codificación en los archivos modificados. Esto ayuda a mantener un código limpio y coherente en todo el proyecto.

2. Comprobación de errores: Puede ejecutar pruebas unitarias o de integración automatizadas antes del commit para asegurarse de que no se introduzcan errores o se rompa el código existente. Esto garantiza que los cambios realizados no afecten negativamente el funcionamiento del proyecto.

3. Formateo automático: "pre-commit" puede aplicar automáticamente el formateo de código, como el uso consistente de sangrías, espacios en blanco o comillas, según las convenciones establecidas. Esto ayuda a mantener la consistencia y legibilidad del código.

4. Análisis de seguridad: Puede realizar análisis estático de seguridad o ejecutar herramientas de escaneo de vulnerabilidades para identificar posibles problemas de seguridad en el código modificado antes de confirmarlos.

5. Existencia de archivos: En muchas ocasiones, dentro de un archivo hacemos referencia a otros, por ejemplo, dentro de un README colocamos una referencia a una imagen, "pre-commit" permite verificar si dicho archivo existe, de esta forma se mantienen ciertos estándares de calidad.

El uso de "pre-commit" permite automatizar estas tareas y garantizar que se sigan las mejores prácticas y estándares establecidos por el equipo de desarrollo en cada commit. Ayuda a mantener la calidad del código, reducir errores y mejorar la eficiencia del proceso de desarrollo.

--------------------------------------------------------------------------------

|                 ⇦           |        ⌂     |         ⇏        |
|:----------------------------|:------------:|-----------------:|
| [Página anterior][anterior] | [Menu](menu) | Página siguiente |


[anterior]: ../Basic_Commands.md
[menu]: ../README.md
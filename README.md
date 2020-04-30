# Tutorial sobre el sistema Git
Manuel Vargas  
2020-04-30

## Recursos de interés
* Sitio oficial de Git: [Git](https://git-scm.com/).
* Referencia de los comandos de Git: [Git commands](https://git-scm.com/docs/git#_git_commands).
* Tutoriales sobre Git: [The Best Git Tutorials](https://www.freecodecamp.org/news/best-git-tutorial/).
* Tutorial sobre comandos de Git (parte 1): [Git Commands Tutorial - Part 1](https://kolosek.com/git-commands-tutorial-part1/).
* Tutorial sobre comandos de Git (parte 2): [Git Commands Tutorial - Part 2](https://kolosek.com/git-commands-tutorial-part2/).

## Características generales
[Git](https://git-scm.com/) es un sistema de [control de versiones](https://en.wikipedia.org/wiki/Version_control) diseñado para rastrear cambios en el código fuente durante el proceso de desarrollo de software. Sin embargo, puede ser utilizado para llevar el control de los cambios en cualquier conjunto de archivos. Un sistema de control de versiones proporciona, entre otras ventajas, la capacidad de recuperar versiones anteriores de un producto de softwware y la integración de modificaciones efectuadas por varios programadores.

Git fue desarrollado por [Linus Torvalds](https://en.wikipedia.org/wiki/Linus_Torvalds) en 2005 durante del desarrollo del [_kernel_ del sistema operativo Linux](https://en.wikipedia.org/wiki/Linux_kernel). Se caracteriza por ser un [sistema de control de versiones distribuido](https://en.wikipedia.org/wiki/Distributed_version_control), lo que significa que el código fuente puede estar alojado en la estación de trabajo de cualquier miembro del equipo de desarrollo (i.e. no hay un repositorio "central"). Es un proyecto de [software libre](https://en.wikipedia.org/wiki/Free_software) que se comparte mediante una licencia [GNU General Public Licence (GNU GPL)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.html).

El protocolo de Git es utilizado en varios sitios que proveen servicios de alojamiento de software, entre los que están [SourceForge](https://sourceforge.net/), [Bitbucket](https://bitbucket.org/), [GitLab](https://about.gitlab.com/) y [GitHub](https://github.com/).

## Ejemplos de uso de comandos
Git cuenta con varias [interfaces gráficas](https://git-scm.com/downloads/guis). Aquí se ejemplificará su uso mediante [comandos](https://git-scm.com/docs/git#_git_commands).

Para seguir los ejemplos que se presentan a continuación, se recomienda crear un repositorio en GitHub (ej. pruebas-github-01) para propósitos de pruebas, con al menos un archivo (ej. README.md). Al reproducir los comandos en su computadora, recuerde cambiar el nombre de usuario, rutas y otros elementos.

### Configuración
El comando [git config](https://git-scm.com/docs/git-config) se utiliza para especificar opciones generales.
```terminal
# Correo electrónico del usuario
$ git config --global user.email "mfvargas@gmail.com"

# Nombre del usuario
$ git config --global user.name "Manuel Vargas"
```

### Clonación de un repositorio
La clonación de un repositorio se realiza mediante el comando [git clone](https://git-scm.com/docs/git-clone).
```terminal
# Clonación del repositorio de pruebas
$ git clone https://github.com/mfvargas/pruebas-github-01.git
```

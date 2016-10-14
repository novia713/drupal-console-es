# drupal-console-es
DrupalConsole Spanish Language / en Español

# Version en Español

## Uso

El proyecto Drupal console se instala por cada sitio web de Drupal 8 con el lenguaje Inglés por defecto.
Para instalar el paquete de Drupal Console en Español se deben ejecutar las siguientes instrucciones

```
$ composer require drupal/console-es
```

### Instalar Drupal Console

Para instalar la versión adecuada del proyecto Drupal console para su instalación de Drupal, ejecute el siguiente comando de composer

```
$ composer require drupal/console:~1.0 --prefer-dist --optimize-autoloader
```

### Instalar Drupal Console launcher

Con el fin de evitar conflictos entre las diferentes versiones de  Drupal y tener una versión de Drupal Console entre versiones mayores y menores en Drupal, se ha creado un Drupal Console Launcher para facilitar la carga de la consola de comandos de Drupal a disposición de cada Drupal 8 página web
 
Siguiendo estas instrucciones se puede instalar globalmente el Drupal Console Launcher.
```
$ curl https://drupalconsole.com/installer -L -o drupal.phar
# Or 
$ php -r "readfile('https://drupalconsole.com/installer');" > drupal.phar

$mv drupal.phar /usr/local/bin/drupal
$ chmod +x /usr/local/bin/drupal
```

### Contribuir

Si quiere contribuir a esta traducción, es necesario seguir los siguientes pasos

- Hacer un fork de este repositorio.
- Clonar tu repositorio forkeado en tu ambiente local.
- Configurar un repositorio de upstream.

A fin de estar al día con otras contribuciónes se debe configurar una conexión con el repositorio principal mediante el siguiente comando git

```
$ git remote add upstream git@github.com:hechoendrupal/drupal-console-fr.git
```

Para obtener las ultimas contribuciónes antes de empezar, se deben ejecutar los siguientes comandos

```
$ git fetch upstream
$ git merge upstream/master
```

Nótese bien: actualice su copia y ENVÍE sus cambios cada día a su repositorio forkeado si quiere hacer un Pull Request para evitar conflictos con otros colaboradores.

# English Version

## Usage

Drupal Console project it's installed per each Drupal 8 website with English language by default.

To installe Drupal Console package for French language run the following instructions

```
$ composer require drupal/console-es
```

### Install Drupal Console

To install the appropriate version of Drupal Console project for your drupal installation, run the following composer command

```
$ composer require drupal/console:~1.0 --prefer-dist --optimize-autoloader
```

### Install Drupal Console launcher

In order to avoid conflicts between Drupal release and have a Drupal Console version between major and minor releases in Drupal,  a Drupal Console launcher was created. n order to facilitate to load the Drupal Console commands available to each
Drupal 8 website,
 
Following the instruction below you could install the global application for Drupal Console launcher. 

```
$ curl https://drupalconsole.com/installer -L -o drupal.phar
# Or 
$ php -r "readfile('https://drupalconsole.com/installer');" > drupal.phar

$mv drupal.phar /usr/local/bin/drupal
$ chmod +x /usr/local/bin/drupal
```

### Contribute

If you want to contribute to this translation, you need to follow this steps

- Fork this repository following this link [https://github.com/hechoendrupal/drupal-console-es#fork-destination-box](https://github.com/hechoendrupal/drupal-console-es#fork-destination-box)
- Clone your repostory forked in your local machine.
- Set up upstream

In order to be updated with other contribution you must to setup a connected with main repository using the following git command

```
$ git remote add upstream git@github.com:hechoendrupal/drupal-console-fr.git
```

To fetch the latest contribution before to start, you must run the next commands
```
$ git fetch upstream
$ git merge upstream/master
```

N.B: Push your changes to your forked repository in order to create PR per day to avoid any conflicts with other contributors.

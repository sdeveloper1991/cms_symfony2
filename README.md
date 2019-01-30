###  Build a CMS With Symfony 2
**Instructor: samir GUIDERK**

Building your own Content Management System (CMS) can be surprisingly simple. In this course we'll build a feature-packed content management system from scratch using the popular Symfony 2 PHP framework.


### Usage Notes

We’ll have 3 dockers, one for php the will expose the port 9000 to be consumed by nginx and deal with the php files. Another for nginx, called web that will expose the por 81 to the host to be able to access the docker container and the last one db, which will run mysql.

To start the environment you’ll need to run the command:

$ docker-compose build
That will build the containers.

Remember to add your project to the Symfony folder or simply run:

$ docker-compose up
To start the docker network.

Now, all you have to do is open your browser on the address http://localhost:81.

As you can see, it’s not that hard! I hope this guide is useful and makes your developer days easier.


What's inside?
---------------

The Symfony Standard Edition is configured with the following defaults:

  * Twig is the only configured template engine;

  * Doctrine ORM/DBAL is configured;

  * Swiftmailer is configured;

  * Annotations for everything are enabled.

It comes pre-configured with the following bundles:

  * **FrameworkBundle** - The core Symfony framework bundle

  * [**SensioFrameworkExtraBundle**][6] - Adds several enhancements, including
    template and routing annotation capability

  * [**DoctrineBundle**][7] - Adds support for the Doctrine ORM

  * [**TwigBundle**][8] - Adds support for the Twig templating engine

  * [**SecurityBundle**][9] - Adds security by integrating Symfony's security
    component

  * [**SwiftmailerBundle**][10] - Adds support for Swiftmailer, a library for
    sending emails

  * [**MonologBundle**][11] - Adds support for Monolog, a logging library

  * [**AsseticBundle**][12] - Adds support for Assetic, an asset processing
    library

  * **WebProfilerBundle** (in dev/test env) - Adds profiling functionality and
    the web debug toolbar

  * **SensioDistributionBundle** (in dev/test env) - Adds functionality for
    configuring and working with Symfony distributions

  * [**SensioGeneratorBundle**][13] (in dev/test env) - Adds code generation
    capabilities

  * **AcmeDemoBundle** (in dev/test env) - A demo bundle with some example
    code

All libraries and bundles included in the Symfony Standard Edition are
released under the MIT or BSD license.

Enjoy!

[1]:  http://symfony.com/doc/2.5/book/installation.html
[2]:  http://getcomposer.org/
[3]:  http://symfony.com/download
[4]:  http://symfony.com/doc/2.5/quick_tour/the_big_picture.html
[5]:  http://symfony.com/doc/2.5/index.html
[6]:  http://symfony.com/doc/2.5/bundles/SensioFrameworkExtraBundle/index.html
[7]:  http://symfony.com/doc/2.5/book/doctrine.html
[8]:  http://symfony.com/doc/2.5/book/templating.html
[9]:  http://symfony.com/doc/2.5/book/security.html
[10]: http://symfony.com/doc/2.5/cookbook/email.html
[11]: http://symfony.com/doc/2.5/cookbook/logging/monolog.html
[12]: http://symfony.com/doc/2.5/cookbook/assetic/asset_management.html
[13]: http://symfony.com/doc/2.5/bundles/SensioGeneratorBundle/index.html

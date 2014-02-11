StaticDeploy
============

This is a project template for StaticDeploy! StaticDeploy provides a deployment for static
html pages right from your Twig templates, Less files and other resources.

You can use all generated contents without PHP. It's very useful for static information
pages or small landing pages. You can use the power of dynamic web pages and


Getting started
---------------

First of all you'll need to install Composer:

    curl -sS https://getcomposer.org/installer | php

If you have Composer installed, you can just use this command to create
a new StaticDeploy project:

    composer.phar create-project -sdev timonf/static-deploy-template your-project-name

Now you can create your source content at `src` and you may compile it to `output` via:

    php bin/staticdeploy.php compile src output


Additional information
----------------------

All files with underscore at the beginning will be ignored. This is useful, if you want
to include some files such layout, footer, header or other resources.
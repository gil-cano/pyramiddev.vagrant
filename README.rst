PyramidDev.Vagrant
================

This is a kit for setting up a development enviroment for `Pyramid <http://www.pylonsproject.org/>`_ in a hosted virtual machine.

Installation
------------

1. Install `VirtualBox <https://www.virtualbox.org>`_

2. Install `Vagrant <http://www.vagrantup.com>`_

3. Clone the repository::

    $ git clone  https://github.com/gil-cano/pyramiddev.vagrant.git

4. Change directory into the pyramiddev.vagrant directory. Run "vagrant up"::

    $ cd pyramiddev.vagrant
    $ vagrant up

This is going to download a virtual box kit, download and install `Pyramid <http://www.pylonsproject.org/>`_, and set up some convenience scripts.

Using the Vagrant-installed VirtualBox
--------------------------------------

You may now start and stop the virtual machine by issuing command in the same directory::

    $ vagrant suspend

stops the virtual machine, saving an image of its state so that you may later restart with::

    $ vagrant resume

Finally, you may remove the VirtualBox (deleting its image) with the command::

    $ vagrant destroy

How you get a command prompt on your "guest" machine will depend on your host operating system. On Unix workalikes, use the command::


    $ vagrant ssh


References
----------

`Try Pyramid <http://trypyramid.com/>`_

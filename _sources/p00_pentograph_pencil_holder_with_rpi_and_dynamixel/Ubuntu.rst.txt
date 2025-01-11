###################################################
Installation d'Ubuntu sur le Rasberry Pi 5
###################################################

Pour installer **Ubuntu** sur le Rasberry Pi 5, Nous avons à notre disposition une **carte SD** contenant l'OS Rasberry Pi que nous allons utiliser dans un premier temps.

Nous avons aussi du matériel informatique tel qu'un écran, une souris et un clavier pour pouvoir naviguer dans le Rasberry Pi 5.

Nous allons utiliser **rpi imager** pour installer **Ubuntu**. Puisque nous utilisons l'OS RasberryPi, il faut entrer la commande suivante pour pour installer **rpi imager** (Rasberry Pi Imager) :

.. code-block:: bash

    sudo apt install rpi-imager
    sudo rpi-imager

En lançant Rasberry Pi Imager, la fenêtre suivante apparaît :

.. figure:: resources/img/rpi_imager.png
    :width: 50%
    :align: center

Il faut alors choisir la bon appareil (**Rasberry Pi 5**), l'OS que l'on veut installer (**Ubuntu version 24.04**) et l'espace de stockage (**Par défaut**).

.. figure:: resources/img/RPIubuntu.jpg
    :width: 50%
    :align: center

.. figure:: resources/img/RPIADATA.jpg
    :width: 50%
    :align: center

.. note::

    Pour plus de détails, voir cette documentation_.

Après quelques minutes (ou heures en fonction de la connexion), il faut redémarrer. La Rasberry Pi devrait alors booter en **Ubuntu**.

.. note:: 

    Pour que chaque groupe puisse effectuer les manipulations, nous avons essayer de partitionner l'espace de stockage à l'aide de gparted :

    .. code-block:: bash

        sudo apt-get install gparted
        sudo gparted

    Cependant, il s'est avéré après coup que la partition n'a pas fonctionné.

.. figure:: resources/img/partition.jpg
    :width: 50%
    :align: center

.. figure:: resources/img/partition2.jpg
    :width: 50%
    :align: center

.. figure:: resources/img/partition3.jpg
    :width: 50%
    :align: center

.. figure:: resources/img/partition4.jpg
    :width: 50%
    :align: center

.. _documentation: https://www.raspberrypi.com/documentation/computers/getting-started.html#raspberry-pi-imager



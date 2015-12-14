Quick start
===========

Development package install
---------------------------

Host
~~~~

.. code:: bash

  git clone --recursive --depth 1 --branch oxvm_drupal_8 git@github.com:OXID-eSales/pet_project.git ./drupal_vm
  cd drupal_vm
  git clone --depth=1 https://github.com/drupal/drupal drupal
  vagrant up

Browser
~~~~~~~

* You should be able to access the site at http://www.drupal.dev/ and follow
  the instructions to continue the install process:

  * Choose ``Standard`` **profile**
  * For **database parameters** enter:

    * database name: ``drupal``
    * database username: ``drupal``
    * database password: ``drupal``

  * For **site configuration** settings just apply common sense

Release package install
-----------------------

Host
~~~~

.. code:: bash

  git clone --recursive --depth 1 --branch oxvm_drupal_8 git@github.com:OXID-eSales/pet_project.git ./drupal_vm
  cd drupal_vm
  wget http://ftp.drupal.org/files/projects/drupal-8.0.1.tar.gz
  mkdir drupal ; tar zxvf drupal-8.0.1.tar.gz --strip-components=1 -C drupal
  vagrant up

Browser
~~~~~~~

Follow the same instructions for browser as in `Development package install`_.

Introduction
============

.. include:: includes/all.rst

`PostgreSQL`_ is a popular relational open source database. The
debops.postgresql_ role can be used to create and manage PostgreSQL roles
and databases on local or remote PostgreSQL servers.

To manage the PostgreSQL server itself, you will need to use
debops.postgresql_server_ role.

.. _PostgreSQL: http://www.postgresql.org/

Installation
~~~~~~~~~~~~

This role requires at least Ansible ``v1.9.0``. To install it, run:

.. code-block:: console

   ansible-galaxy install debops.postgresql

..
 Local Variables:
 mode: rst
 ispell-local-dictionary: "american"
 End:


.. title: DjangoCMS

:data-transition-duration: 500
:css: css/presentation.css

----

:id: intro

.. image:: images/djangocms_logo.png
    :class: image-centered

.. class:: quote

    "Django" y "CMS"
    
.. note::
    *Qué es Django CMS*. Antes, es necesario explicar las 2 palabras que componen su nombre: Django, y CMS.

----

:id: cms

CMS
===

Content Management System
-------------------------
Adm. de contenidos, para los administradores, editores, participantes y demás usuarios del sitio.

.. note::
    CMS: permite a los editores añadir, editar y gestionar contenido.

----

Django
======

.. class:: quote

    "The web framework for perfectionists with deadlines"
    
.. note::
    Es un framework para el desarrollo web en Python con herramientas para todo.

----

Framework
=========
Estructura conceptual y tecnológica de soporte definido, normalmente módulos concretos y herramientas para el desarrollo.
    
.. note::
    ¿Qué es un framework? Es una estructura con unos métodos establecidos para el desarrollo con unas herramientas.
    
----

Algunas de las herramientas que ofrece Django...
================================================

* Admin
* CRM (models.py)
* Templates
* Sis. vistas genéricas (views.py)
* Middleware
* Sis. de urls (urls.py)
* Sistema de usuarios...

.. note::
    Para quienes no han usado Django, algunas de sus características...

----

DjangoCMS:
==========

Complementa a Django como framework
-----------------------------------

Pero con herramientas para CMS
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. note::
    Complementa el framework de Django con herramientas para CMS.

----

Herramientas que ofrece DjangoCMS
=================================

* Sistema de menús jerárquico y multiidioma.
* Gestión y creación de páginas.
* Borradores y publicación de contenido.
* Sistema de versiones.
* Contenido multiidioma y condicionado por el mismo.
* Gestión de los Apphooks y los plugins (que hablaremos más adelante).

.. note::
    Y ahora las las herramientas que nos incluye DjangoCMS...

----

Una pequeña demostración...
===========================

.. note::
    Y ahora una pequeña demostración para que se vea de qué hablamos...

----

Desarrollo para DjangoCMS
=========================

Tenemos principalmente:

- Apphooks
- Plugins


Además de otras herramientas como:

- Menús
- Wizards
- ...

.. note::
    Y ahora, cómo usar las herramientas de DjangoCMS...

----

Apphooks
========

----

DjangoCMS es
============
respetuoso con Django.
----------------------

No se solapa con el mismo
^^^^^^^^^^^^^^^^^^^^^^^^^

No lo modifica
""""""""""""""

Lo complementa
""""""""""""""

.. note::
    DjangoCMS a diferencia de otros sistema de CMS para Django, lo complementa sin llegar a modificarlo.

----

DjangoCMS
=========

* Usa el admin de Django.
* Mismo sistema de modelos.
* Mismo sistema de urls.
* Mismos views.
* Mismos templates.

.. note::
    Y como hemos visto, DjangoCMS reutiliza los elementos ya existentes de Django.

----

Plugins
=======
Son el equivalente a los widgets de otros CMS.

Bloques que se integran en las páginas y pueden reordenarse.

.. note::
    Al igual que en otros CMS, en DjangoCMS hay bloques, a los que se denomina widgets, que se integran en las páginas, pudiéndose añadir, eliminar, modificar o reordenar cuando se desee.

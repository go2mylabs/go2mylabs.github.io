.. highlight:: php

Lab 1
=====

Ennoncé du TP :

.. code-block:: shell

   $ ls -l


Voici du texte en *italique*, en **gras**, et voici du ``code inline``.


Pour faire un lien inline c'est simple :
lien vers le `blog de FLOZz <https://blog.flozz.fr/>`_

.. warning::

   Never, ever, use this code!


.. note::
   Never, ever, use this code!

.. warning::
   Never, ever, use this code!

.. versionadded:: version

.. versionchanged:: version

.. solution::

   .. code-block:: shell
   
      $ ls -l


.. toggle::

   Here is my toggle-able content!


.. container:: toggle, toggle-hidden

    .. admonition:: Look at that, an image!

        .. image:: https://media.giphy.com/media/mW05nwEyXLP0Y/giphy.gif


.. note::
    :class: dropdown, toggle-shown

    This is my note.


.. note::
    :class: dropdown, toggle-hidden

    This is my note.


.. code-block:: php
   :linenos:

       $GLOBALS['TYPO3_CONF_VARS']['FE']['addRootLineFields'] .= ',tx_realurl_pathsegment';

       // Adjust to your needs
       $domain = 'example.org';
       $rootPageUid = 123;
       $rssFeedPageType = 9818; // pageType of your RSS feed page


The literal blocks are now highlighted as HTML, until a new directive is found.

.. code-block:: html

   <html><head></head>
   <body>This is a text.</body>
   </html>

.. code-block:: yaml

   apiVersion: v1
   kind: Pod
   metadata:
     name: web
     labels:
       app: web
   spec:
     containers:
     - name: nginx
       image: nginx:1.14-alpine


.. code-block:: python
   :emphasize-lines: 3,5

   def some_function():
       interesting = False
       print 'This line is highlighted.'
       print 'This one is not...'
       print '...but this one is.'

.. code-block:: python

   def some_function():
       interesting = False
       print 'This line is highlighted.'
       print 'This one is not...'

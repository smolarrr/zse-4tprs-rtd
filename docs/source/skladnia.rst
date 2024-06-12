Składnia Elementów Dokumentu
============================

Nagłówki Tekstowe
-----------------

Nagłówek poziomu 1
==================

Nagłówek poziomu 2
------------------

Nagłówek poziomu 3
^^^^^^^^^^^^^^^^^^

Nagłówek poziomu 4
""""""""""""""""""


Akapity Tekstowe
----------------

To jest przykładowy akapit tekstowy.

Akapity Informacyjne
--------------------

.. note::
   To jest notatka.

.. tip::
   To jest wskazówka.


Fragmenty Kodu
--------------

Liniowy: ``print("Hello, World!")``

Blokowy:
.. code-block:: python

   def hello_world():
       print("Hello, World!")


Odnośniki
---------

Lokalny: :ref:`local-reference`

Zewnętrzny: `Google <https://www.google.com>`_


Listy
-----

Numerowana:
1. Pierwszy element
2. Drugi element

Wypunktowana:
- Pierwszy element
- Drugi element

Lista definicji:
Termin
   Definicja


Obraz
-----

.. image:: ścieżka/do/obrazu.png
   :alt: Tekst alternatywny
   :width: 200px
   :align: center
   :figclass: center

   Podpis pod obrazkiem


Tabela
------

+-----------+-----------+
| Nagłówek1 | Nagłówek2 |
+===========+===========+
| Komórka1  | Komórka2  |
+-----------+-----------+

.. PythonOOPs documentation master file, created by
   sphinx-quickstart on Tue Jun 21 17:00:29 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to OOPs in Python- a quick guide.
==========================================
(Ref : https://www.analyticsvidhya.com/blog/2020/09/object-oriented-programming/ Accessed on 21st June 2022) . This is a  practise project for documentation and texts here are borrowed from the above references.

*Object Oriented Programming concepts in Python*:
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
#. :ref:`Class`
#. :ref:`Object` 
#. :ref:`Method`
#. :ref:`Inheritance` 
#. :ref:`Encapsulation`
#. :ref:`Polymorphism`
#. :ref:`Data abstraction`

.. _Class:

What is a class?
"""""""""""""""""
Classes are user defined data structures (contrast with primitive data types-Integers,Float,Strings,Boolean) . It is also blueprint for creating many objects each with custom values. Let's begin with creating a car class without any details : 
::
	class Car:
		pass

Now let's add name , color as we expect real world Sedan car to have one through class constructor _init_ :
::
	class Car:
		car_type = "Sedan"          #class attribute - common to all objects.
		def __init__(self, name, color): 
			self.name = name    #instance attribute -each instance may have different value.
			self.color = color  #instance attribute -each instance may have different value.


.. _Object:

Creating a particular instance for a red Honda City.
obj = Car("Honda City","Red")


Object and object instantiation
""""""""""""""""""""""""""""""""

.. _Method:

Class methods
""""""""""""""

.. _Inheritance:

Inheritance in Python Class
""""""""""""""""""""""""""""

.. _Encapsulation:

Encapsulation
""""""""""""""

.. _Polymorphism:

Polymorphism
""""""""""""""

.. _Data abstraction:

Data abstraction
"""""""""""""""""

.. toctree::
   :maxdepth: 2
   :caption: Contents:
   

   

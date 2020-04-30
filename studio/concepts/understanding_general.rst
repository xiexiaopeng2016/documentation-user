==============================
Understanding General Concepts
==============================

| Odoo Studio is a toolbox that allows you to add models or adapt functionalities on top of Odoo’s
  standard behavior without coding knowledge. You can also create custom views and modify existing
  ones without having to get into the XML code.
| Even for experienced developers typing out code requires time. Using Odoo Studio, you can quickly
  get your models up and going and focus on the crucial parts of your application. The result is a
  user-friendly solution that makes customizations and designing new applications easy, with or
  without programming skills.

What is a Module?
-----------------

An Odoo *Module* can contain a number of elements, such as: business objects (models), object views,
data files, web controllers and static web data. An application is a collection of modules.

.. image:: media/new_app.png
   :align: center
   :alt: Overview of the main dashboard emphasizing the option to create a new app in Odoo Studio

What is a Model in Odoo (also called Object)?
---------------------------------------------

A model determines the logical structure of a database and fundamentally determines in which manner
data can be stored, organized, and manipulated. In other words, a model is a table of information
that can be bridged with other tables.

What is a Field?
----------------

Fields compose models (tables). It is where a record (a piece of data) is registered.

What are Relational Fields?
~~~~~~~~~~~~~~~~~~~~~~~~~~~

| Relational Fields provide the option to link the data of one model with the data of another model.
| In Odoo, relational field types are: *One2many*, *Many2one*, *Many2many*.

.. image:: media/relational_fields.png
   :align: center
   :alt: Tables with a visual explanation of related fields for Odoo Studio

| An **One2many** field is a *one-way* direction of selecting *multiple* records from a table.
| Example: a Sales Order can contain multiple Sales Order Lines, which also contain multiple fields
  of information.
| A **Many2one** field is a *one-way* direction of selecting *one* record from a table.
| Example: you can have many product categories, but each product can only belong to one category.
| A **Many2many** field is a *two-way* direction of selecting records from a table.
| Example: multiple tags can be added to a lead’s form.

.. note::
   An *One2many* field must have a *Many2one* related to it.

What is a Menu?
---------------

A menu is a button that executes and action. In Studio, to create menus and rearrange hierarchies,
click on *Edit Menu*. By clicking on *Edit Menu Item* the access rights of that specific menu can be
changed. If groups are added, the menu’s visibility is based on the groups. If no groups are set,
Odoo computes the visibility based on the related object’s read access.

.. image:: media/edit_menu.png
   :align: center
   :alt: Overview of a menu being edit in Odoo Studio




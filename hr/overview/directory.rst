==================
Employee Directory
==================

The Employee Directory  allows you to create and manage all the employees in your Database. From the Directory, you can
create departments and organize your company’s structure.

Configuration
=============

Go to :menuselection:`Employee → Employee Directory`. The employee Directory is the default dashboard for the Employee
Application.

Using the Employee Directory
============================

From the *Employee Directory*, filter your employees by *Company*, *Department*, *Manager* or simply use the search bar
to find a specific employee.

.. image:: media/employee-dashboard.png
   :align: center
   :alt: Employee Directory

.. tip::
   You can search for old employees by setting the filter to “archived”.

From there  you can check employee presence in an instant.


Employee Presence
=================

Employee presence tools help better report employee attendance and take actions for employees who are not present.( Send
a sms / e-mail reminder / put a one day leave ). Different online presence methods can be set up in the settings.

Configuration
-------------

Go to :menuselection:`Employee → Configuration →Settings`

.. image:: media/advanced-settings.png
   :align: center
   :alt: Advanced presence control

Pick the best method to track employee presence by criteria that fit your company.

Presence Control
----------------

Based on attendance: The user is considered "at work" if they're identified in the app “attendances.”

Based on user status in the system: The user is considered “at work” if he is logged in to your database. This user
stays active as long as he’s connected to the database and for a period of 30 min after he disconnects.

Advanced Presence Control
-------------------------

Based on number of emails sent: Define a number of emails to send for the user to be considered present. Once the user
has reached the number of emails he’s present for the rest of the day. If the user does not reach the email goal he will
appear as absent.

Based on IP address: The user is considered "at work" if they're logged in to the database via a specific IP address.
Every IP address that needs to be checked has to be filled in the settings.

Employee Status
---------------

The different control methods will impact the status of each employee.

- **At work** if a user fits one of the criteria defined in the settings (green dot).
- **Absent** if the user is not at work and no time off has been taken (red dot).
- **Off** if a user is on *time off* or if he's out of his time defined in the calendar.

.. image:: media/employee-status.png
   :align: center
   :alt: Employee Status
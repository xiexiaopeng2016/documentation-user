==============================================
Create a quotation using subscription products
==============================================

Selling a digital product or service can give you instant gratification. However, you then have
to work hard for a new customer to make a purchase. It costs time and money. By convincing customers
to sign up for a subscription, you will maximize your income and streamline your cash flow. You can
sell any type of product or service through a subscription business model.

.. raw:: html

   <div align="center" style="color:#AD5E99; font-size: 2rem ;margin: 20px 0"> <b>The only limit is
   your imagination.</b> </div>

Here is a scenario using **Odoo Subscriptions** to create a quotation including subscription
products.

Create your first quotation
===========================

Before creating your first quotation, be sure to check out our documentation on how to create and
manage your own *Subscription templates*:
:doc:`../../subscriptions/configuration/subscription_templates`
and on how to add *Subscription products* to your *Subscription templates*,
:doc:`../../subscriptions/configuration/subscription_products`.

.. important::

   These steps are **mandatory** if you want to make a basic sales flow using
   **Odoo Subscriptions**.

Go to **Odoo Sales** and create a new quotation. Once you have chosen a customer, you can add a
product. Be careful to select a product that you previously configured as a *Subscription product*.

.. image:: media/quotations_1.png
  :align: center
  :alt: View of a quotation form in Odoo Sales

When your quotation is ready, you have the possibility to send it to your customers or to confirm
it. It is better to first *Send by email* the quotation to your customers in order to have their
confirmation and then *Confirm* your quotation in **Odoo Sales**. By clicking on *Customer preview*,
you can have an idea of what your customer will see when receiving your quotation.

.. image:: media/quotations_2.png
  :align: center
  :alt: Customer preview of a quotation form in Odoo Sales

From there, your customers have three choices: *Sign & Pay* the quotation, give you a *Feedback* or
*Reject* the quotation. It appears that your customers are very happy and accept the option
*Sign & Pay*. They will have to validate the order with a signature and by choosing a payment
method. When it is done, you can check out the quotation in **Odoo Sales** and *Confirm* it.

Manage your subscriptions from your SO
======================================

Once confirmed, the quotation becomes a sales order and a new button appears, *Subscriptions*.
Indeed, a subscription will automatically be created.

.. image:: media/quotations_3.png
  :align: center
  :alt: Quotation form in Odoo Sales with a button "Subscriptions"

By clicking on this intelligent button *Subscriptions*, you will see that the status of the
subscription is *In progress*. From there, you will have three options: *Renew*, *Close* or *Upsell*
your subscription. These three options will be detailed in other documentations.

.. image:: media/quotations_4.png
  :align: center
  :alt: Use of the intelligent button "Subscriptions" in Odoo Sales

In the top-right corner you can see the status of the subscription. When a subscription is
new and freshly created from **Odoo Subscriptions**, the status is *Draft*. When a sales order has
been validated, the status is *In progress*. Finally, when a customer decides to close his
subscription, the status becomes *Closed*.

.. seealso::
  - :doc:`../../subscriptions/configuration/subscription_templates`
  - :doc:`../../subscriptions/configuration/subscription_products`

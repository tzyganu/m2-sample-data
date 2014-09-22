Magento2 Sample Data
==============

This is an attempt at a sample data for Magento 2.0 until the official sample data gets out.
It is based on the sample data from Magento CE 1.6.
In fact, you should get the images for the products from the sample data `media` folder.
Copy that folder over the `media` folder inside the `pub` folder of magento 2.0.

The sample data is not fully tested.
If you find something please report the issues <a href="https://github.com/tzyganu/m2-sample-data/issues">here</a> and I'll see what I can do.

How to use
----------
Prior to installing Magento 2,
create a database then import the `m2sample.sql` file in the db you just created.

Then run the install wizard.
In the step where you are required to enter the db connection data, enter the name of the database you just created.
After installation, log in the backend and rebuild the available indexes.

You also need to copy the `pub` folder in this repository over the `pub` folder of magento.


Changelog
------------
2014-09-22

 - Made compatible with alpha-96 - good luck installing that :)

2014-09-03

 - Fixed tax_class_id source model
 - Fixed billing agreements table



.. image:: https://img.shields.io/badge/licence-AGPL--3-blue.svg
    :alt: License: AGPL-3

Sale line price properties based
================================

This module allows to use python formaulas to compute the sale order line
price.

You can configure the 'Price formula' on the product form using python code.

Formula example:
```
area = float(properties['Width']) * float(properties['Length'])
result = area / 2.0
if 'Painting' in properties:
    result = result + 5
```

When changing properties on sale order line, the system will automatically
compute the line price unit.

Credits
=======

Contributors
------------

* Lorenzo Battistini <lorenzo.battistini@agilebg.com>
* Alex Comba <alex.comba@agilebg.com>

Maintainer
----------

.. image:: http://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: http://odoo-community.org

This module is maintained by the OCA.

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

To contribute to this module, please visit http://odoo-community.org.

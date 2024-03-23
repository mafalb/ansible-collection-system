..
  Copyright (c) Markus Falb <markus.falb@mafalb.at>
  GNU General Public License v3.0+
  see LICENSE or https://www.gnu.org/licenses/gpl-3.0.txt

.. _ansible_collections.mafalb.system.docsite.epel_role:

mafalb.system.epel
=========================

An ansible role for installing the EPEL repo.

Basic Usage
-----------

.. code-block:: yaml+jinja

    # Install epel
    - roles:
        - role: mafalb.system.epel
..

.. code-block:: yaml+jinja

    # Install epel-next (regular epel included implicitly)
    - roles:
        - role: mafalb.system.epel
          next: true
..

.. code-block:: yaml+jinja

    # Remove epel and epel-next
    - roles:
        - role: mafalb.system.epel
          epel_state: absent
..

License
-------

Copyright (c) Markus Falb <markus.falb@mafalb.at>

GPL-3.0-or-later

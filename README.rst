Python Pyrex module
====================

|travis|_ |coveralls|_


.. |travis| image:: https://travis-ci.org/pyrex-coin/pyrex-python.svg
.. _travis: https://travis-ci.org/pyrex-coin/pyrex-python


.. |coveralls| image:: https://coveralls.io/repos/github/pyrex-coin/pyrex-python/badge.svg
.. _coveralls: https://coveralls.io/github/pyrex-coin/pyrex-python


A comprehensive Python module for handling Pyrex cryptocurrency.

* release 0.5.3
* open source: https://github.com/pyrex-coin/pyrex-python
* works with Pyrex 0.13.x and `the latest source`_ (at least we try to keep up)
* Python 2.x and 3.x compatible
* comes with `documentation`_

.. _`the latest source`: https://github.com/pyrex-coin/pyrex
.. _`documentation`: http://pyrex-coin.readthedocs.io/en/latest/

Copyrights
----------

Released under the BSD 3-Clause License. See `LICENSE.txt`_.

Copyright (c) 2017-2018 Michał Sałaban <michal@salaban.info> and Contributors: `lalanza808`_, `cryptochangements34`_, `atward`_, `rooterkyberian`_, `brucexiu`_,
`lialsoftlab`_, `moneroexamples`_.

Copyright (c) 2016 The MoneroPy Developers (``monero/base58.py`` and ``monero/ed25519.py`` taken from `MoneroPy`_)

Copyright (c) 2011 thomasv@gitorious (``monero/seed.py`` based on `Electrum`_)

.. _`LICENSE.txt`: LICENSE.txt
.. _`MoneroPy`: https://github.com/bigreddmachine/MoneroPy
.. _`Electrum`: https://github.com/spesmilo/electrum

.. _`lalanza808`: https://github.com/lalanza808
.. _`cryptochangements34`: https://github.com/cryptochangements34
.. _`atward`: https://github.com/atward
.. _`rooterkyberian`: https://github.com/rooterkyberian
.. _`brucexiu`: https://github.com/brucexiu
.. _`lialsoftlab`: https://github.com/lialsoftlab
.. _`moneroexamples`: https://github.com/moneroexamples

Want to help?
-------------

If you find this project useful, please consider a donation to the following address:
``481SgRxo8hwBCY4z6r88JrN5X8JFCJYuJUDuJXGybTwaVKyoJPKoGj3hQRAEGgQTdmV1xH1URdnHkJv6He5WkEbq6iKhr94``


Development
-----------

1. Clone the repo
2. Create virtualenv & activate it

.. code-block:: bash

    python3 -m venv .venv
    source .venv/bin/activate

3. Install dependencies

.. code-block:: bash

    pip install -r requirements.txt -r test_requirements.txt

4. Do your thing

5. Run tests

.. code-block:: bash

    pytest

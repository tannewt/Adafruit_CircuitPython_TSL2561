
Introduction
============

.. image:: https://readthedocs.org/projects/adafruit-circuitpython-tsl2561/badge/?version=latest
    :target: https://circuitpython.readthedocs.io/projects/tsl2561/en/latest/
    :alt: Documentation Status

.. image :: https://badges.gitter.im/adafruit/circuitpython.svg
    :target: https://gitter.im/adafruit/circuitpython?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge
    :alt: Gitter

CircuitPython driver for TSL2561 Light Sensor.

Dependencies
=============
This driver depends on:

* `Adafruit CircuitPython <https://github.com/adafruit/circuitpython>`_
* `Bus Device <https://github.com/adafruit/Adafruit_CircuitPython_BusDevice>`_

Please ensure all dependencies are available on the CircuitPython filesystem.
This is easily achieved by downloading
`the Adafruit library and driver bundle <https://github.com/adafruit/Adafruit_CircuitPython_Bundle>`_.

Usage Example
=============

.. code-block:: python

    >>> import board
    >>> import busio
    >>> i2c = busio.I2C(board.SCL, board.SDA)
    >>> import adafruit_tsl2561
    >>> tsl = adafruit_tsl2561.TSL2561(i2c)
    >>> tsl.lux
    3294.37

Contributing
============

Contributions are welcome! Please read our `Code of Conduct
<https://github.com/adafruit/Adafruit_CircuitPython_CircuitPython_TSL2561/blob/master/CODE_OF_CONDUCT.md>`_
before contributing to help this project stay welcoming.

API Reference
=============

.. toctree::
   :maxdepth: 2

   api


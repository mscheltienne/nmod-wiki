.. include:: ../links.inc

Magstim BiStim²
===============

The `BiStim²`_ is a paired-pulse stimulator combining 2 monophasic stimulators to
deliver paired pulses through 2 separate or through a single coil. The paired pulses can
be delivered with independent stimulation intensities and variable inter-pulse intervals.

Magstim devices share common features that are detailed in the
:ref:`common features section of the guidelines <guidelines:Magstim devices>`.

.. note::

    Contrary to the `Super Rapid² Plus¹`_, the `BiStim²`_ power consumption is handled
    through a single power outlet.

Settings
--------

When both stimulators are connected to the same coil, the stimulator A controls the
intensity of both pulses (and stimulators) and the inter-pulse interval. The pulses
can be set to different intensities.

Mode ε
~~~~~~

When setting the inter-pulse interval to ``0``, then pressing the red button and turning
the nob counter-clockwise, the `BiStim²`_ will enter mode ε. In this mode, the pulse
delivery is controlled by the triggers only. The first trigger will deliver a pulse on
stimulator A, the second trigger will deliver a pulse on stimulator B.

.. warning::

    The `BiStim²`_ stimulators need time to recharge between pulses. Thus, after a pulse
    has been delivered on a stimulator, it is up to the user to ensure no new trigger
    attempts to deliver a pulse on the same stimulator before it is ready. Usually, the
    stimulator requires around 1 second to recharge (depends on the pulse intensity).

    If a trigger is sent to a stimulator that is not ready, the `BiStim²`_ will wait
    until it is recharged before delivering the pulse. Thus, the inter-pulse interval
    will **not** be respected.

Notes
-----

Using both `BiStim²`_ stimulators connected to the same coil with an inter-pulse
interval set to ``0`` is not equivalent to using a single `BiStim²`_ stimulator. This
mode of operation is **not recommended**.

Datasheet
---------

TODO

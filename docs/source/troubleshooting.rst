===============
Troubleshooting
===============

This page lists all common issues regarding the Hack Pack and/or NetPlay sessions. No support is provided for this as it *works on my machine.* 🙂

.. note::
    :ref:`The Hack Pack is no longer developed. What you see is what you get.`

Hack Pack Troubleshooting
-------------------------

Missing or Blank Textures
^^^^^^^^^^^^^^^^^^^^^^^^^

- Verify that you are using the latest Beta instead of a random build.

- Change your graphical settings to a different backend such as Vulkan or OpenGL.

- Ensure LAN adapter is not enabled if you are attempting to access the Debug menu.


Controller not Working
^^^^^^^^^^^^^^^^^^^^^^

Firstly, verify that you have configured your controller correctly within the newly downloaded build. If the issue persists, it's likely related to your controller or other software unrelated to the scope of this guide.


Changing Music crashes Console
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

This feature is only available to the Dolphin Emulator version of the game.


NetPlay Troubleshooting
-----------------------

Desync Issues
^^^^^^^^^^^^^

Desyncs are normal as caused by Fullscreen codes

.. note::
    :ref:`This desync should notify during the start of City Trial, or a higher frame than 1000.`

.. warning::
    :ref:`If players are moving erratically, an actual desync has occurred.`

Ensure MD5 hash and Gecko Codes are the same (except Fullscreen), and that you are not syncing memory cards or codes in the NetPlay settings.


Blank Screen or Seeing Wrong Camera
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

It's probable that the Fullscreen codes might be incorrect. Make sure that your Fullscreen code aligns with the correct port. If you're planning to engage in split-screen play, Deactivate all Fullscreen codes to avoid this complication.


Gameplay Lag
^^^^^^^^^^^^

Make sure you're using a wired connection for optimal performance. Additionally, gradually increase the buffer value until you attain a consistent and stable 60 frames per second (FPS) gameplay experience.


Game Missing
^^^^^^^^^^^^

Use the MD5 matching function in the netplay lobby to ensure a non-corrupt and correct version of the game is being used (hashes must match).
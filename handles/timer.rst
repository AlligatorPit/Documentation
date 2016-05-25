Timer
=====
Can be used to run a function at a certain interval.

It has 2 member variables:

* ``Number Delay`` - The delay in seconds.
* ``Number Counter`` - The current counter value.

Constructor
-----------
When constructing, the timer will immediately start.

The constructor takes 3 arguments:

* ``Number delay`` - The delay in seconds.
* ``Number counter`` - After this many times calling the timer will stop automatically. Set this to 0 for unlimited.
* ``Function func`` - The function to call on timer tick.

Start
-----
Start the timer.

This function takes 2 arguments:

* ``Number delay`` - The delay in seconds.
* ``Number counter`` - After this many times calling the timer will stop automatically. Set this to 0 for unlimited.

Stop
----
Stop the timer.

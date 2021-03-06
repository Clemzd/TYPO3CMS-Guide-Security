.. ==================================================
.. FOR YOUR INFORMATION
.. --------------------------------------------------
.. -*- coding: utf-8 -*- with BOM.

.. include:: ../../Includes.txt


.. _backups-time-plan:

Time plan and retention time
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

In most cases you should create a backup once a day, typically at a
time when the server load is low. Rather than overwriting the backup
from the previous day you should create a new backup and delete older
copies from time to time. Just having a backup from last night is not
sufficient for recovery since it would require that you notice the
need for a restore within 24 hours. Here is an example for a good
backup strategy:

- keep one daily backup for each of the last 7 days

- keep one weekly backup for each of the last 4 weeks

- keep one monthly backup for each of the last 6 months

- keep one yearly backup for each year


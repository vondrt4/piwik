Piwik - Self Hosted Real-Time Web Analytics
===========================================

`Piwik`_ is the leading free software alternative to Google Analytics,
used on more than 320,000 websites. Piwik lets you easily collect and
visualize data from websites, apps & the Internet of Things. It can
generate detailed reports of your website visitors, the search engines
and keywords they used, the language they speak, your popular pages, and
much more. Privacy is built-in.

This appliance includes all the standard features in `TurnKey Core`_,
and on top of that:

- Piwik configurations:
   
   - Installed from upstream source code to /var/www/piwik

- SSL support out of the box.
- `Adminer`_ administration frontend for MySQL (listening on port
  12322 - uses SSL).
- Postfix MTA (bound to localhost) to allow sending of email (e.g.,
  password recovery).
- Webmin modules for configuring Apache2, PHP, MySQL and Postfix.

Credentials *(passwords set at first boot)*
-------------------------------------------

-  Webmin, SSH, MySQL, Adminer: username **root**
-  Piwik: username **admin**

.. _Piwik: http://piwik.org/
.. _TurnKey Core: https://www.turnkeylinux.org/core
.. _Adminer: http://www.adminer.org/

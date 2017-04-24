ServiceMix - Open Source ESB Integration Container
====================================

`ServiceMix`_ is a flexible, open-source integration container that unifies
the features and functionality of Apache ActiveMQ, Camel, CXF, and Karaf 
into a powerful runtime platform you can use to build your own integrations 
solutions. It provides a complete, enterprise ready ESB exclusively powered 
by OSGi.

This appliance includes all the standard features in `TurnKey Core`_,
and on top of that:

- Oracle JDK 8:
   - Oracle JDK 8 installed 

- ServiceMix configurations:
   
   - Installed from upstream release to /opt/apache-servicemix-7.0.0/
   - Configured to startup/shutdown via SystemD
               
- Useful and popular features installed:
   
   - ServiceWrapper: Allows SystemD/SysV integration
   - WebConsole: Installed to allow web access via port 8181

Credentials *(passwords set at first boot)*
-------------------------------------------

-  Webmin, SSH, MySQL, Adminer: username **root**
-  Service Mix username: karaf password: karaf



.. _ServiceMix: http://servicemix.apache.org/
.. _TurnKey Core: https://www.turnkeylinux.org/core

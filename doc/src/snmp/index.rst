SNMP
####

.. note::

	A ntopng Enterprise M license or above is required.

`SNMP (Simple Network Management Protocol) <https://en.wikipedia.org/wiki/Simple_Network_Management_Protocol>`_ is a standard used to collect and monitor network infrastructures.

ntopng has the ability to combine traffic data with SNMP data. This means it periodically pools SNMP devices to fetch information on their status, on the status of their interfaces, and on who's is connected to them and where. It provides an overall visibility of every monitored device, and allowing a drill-down of the monitored data down to every single device interface. Historical charts are available to understand the patterns of traffic across devices and interfaces.

Alerts can be created, for example, when an interface changes its status from up to down, or vice versa.

These blog posts explain in detail how SNMP monitoring in ntopng works, and what are the best practices for its setup:

- https://www.ntop.org/ntopng/advanced-snmp-monitoring-with-ntopng/
- https://www.ntop.org/ntopng/monitoring-network-devices-with-ntopng-and-snmp/

.. toctree::
    :maxdepth: 2

    configuration
    monitoring
    usage
    similarity
    topology
    rules

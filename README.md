<table><tr><td><h1><b>MQ Appliance Network Interface Monitor</b></h1></td><td><h1><b> <a href="https://github.com/sparsons-net/mq-appliance-rest-nic-monitor/releases/download/r1.0/MqaRestNicMonitor_pi.zip"><img src="DownloadButton.png"/></b></h1></td></tr></table>
====================
This IBM Integration Bus (IIB) message flow uses the MQ Appliance's REST API to check the status of two speficied network interfaces on the appliance.  Most likely, these network interfaces would be the two used for MQ traffic.  If both of these network interfaces are down, the flow will suspend the HA group on that appliance, failing the HA queue managers over to the standby appliance.

To get started, click the Download button above to download the project interchange file.  Import that project interchange file into the IIB toolkit.  Open MqaRestNicMonitor.msgflow in a message flow editor and follow the instructions you find there in the yellow note.

This IIB message flow was built and tested on IIB 10.0.0.7 on a Linux IIB runtime and was tested with a virtual MQ Appliance running MQ 9.0.1.0.

See also the GitHub Pages site for this repository: https://sparsons-net.github.io/mq-appliance-rest-nic-monitor/

Thanks for checking it out! 

-- Steve Parsons
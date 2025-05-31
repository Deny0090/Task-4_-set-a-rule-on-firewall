# Task-4_-set-a-rule-on-firewall
In Windows
control panel ->  System and security -> Windows Defender firewall
                   OR
Press Win + R, type wf.msc, and hit Enter to open Windows Defender Firewall with Advanced Security.

Open windows defender Fire wall and click additional settings
There are 2 options:
  1. inbound rules (rules set for incoming traffic)
  2. outbound rules (rules set for outgoing traffic)

I choose options 1  and set a rule for block incoming traffic in ssh port (22)
I test in the command prompt to see there is any connection establishing 
 
A firewall is a gatekeeper for security, controlling traffic into or out of a network using:
  1.rules (allow/block by port, IP, or protocol)
  2.stateful inspection (examines and tracks connections)
  3.default policies (default deny inbound/allow outbound)

It checks through the following packets against rules in order, and if the packets match the rule, the firewall will stop them or permit the packets, based on the first match. For example:

  1.Blocking port 22 would block SSH connections.
  2.Allowing port 80 will allow web traffic.

Firewalls can filter at the network/transport layer (IP/port) or at the application layer (specific programs). 

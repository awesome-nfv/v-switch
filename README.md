#   v-switch

V-switch is an encrypted virtual switch. Following the concept of Tinc (part of it) it creates a virtual interface
which peers with other daemons around the internet. All the machines running the same daemon, with the same encryption key
will have a device configured, which behaves like it was cabled to the same physical switch.  

The aim is to be able to create a LAN across the internet or inside the cloud, where the machine just appears to be connected
each others on layer 2. Adding a new machine to the switch will advertise each other machine seamless, **unlike Tinc**. This is
to be able to use it inside a cloud while autoscaling: no provisioning is needed, there is only one key _per virtual switch_.


Still work in progress, keep following.

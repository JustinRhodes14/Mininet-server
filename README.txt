0.) Authors: Greg Fuerte (grf27) & Justin Rhodes (jgr85)

1.) Regarding the setup, we set up all of the ip addresses for each host using the ip addr add command. In order to figure out how to use this, we used the ip addr help command to better understand how it works. Afterwards, we set up the default routes using the ip route add default command. Once again, we used the ip route help to better understand how this command works. We then added the routes on the router using the ip route add command, to finish setting up the links between each host to the router. Afterwards, in order to test our program, we used ping & traceroute to ensure that all hosts could be reached via the routers various paths. 

2.) There are no known issues with our commands, after running the file, everything ran smoothly, but the traceroutes were periodically slow. This seemed to be due to the nature of virtual machines.

3.) We didn't face many problems for this project, most of our difficulties were setting up the virtual machine and getting the mininet server set up initially. Another issue we faced was ensuring accuracy of the connections, as much of this was very new to us.

4.) We learned how to create a virtual machine, how to set up a mini network, how ping & traceroute can be used to test connectivity, and learned more about how networks work overall.
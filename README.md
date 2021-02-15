# Port Scanner in Python
<hr>

Port scanning is a scanning method for determining which ports on a network device are open, whether it's a server, a router, or a regular machine. A port scanner is just a script or a program that is designed to probe a host for open ports.

Developed own port scanner in Python using socket library. The basic idea behind this simple port scanner is to try to connect to a specific host (website, server or any device connected to Internet/network) through a list of ports, if a successful connection has been established, that means the port is open.

For instance, when you loaded this web page, you have made a connection to this website on port 80, similarly, this script will try to connect to a host but on multiple ports. These kind of tools are useful for hackers and penetration testers, so don't use this tool to a host that you don't have permission to test!
<hr>

## Specific Packages or Modules.

Optionally, you need to install colorama module for fancy printing:

`pip3 install colorama`

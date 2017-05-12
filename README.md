# shakti
#### Bind the shell to any http port | Remote controller | Shell Attached Kindly To Internet

### What?

This is a remote shell. It allow to send <b>unix</b> commands via http.

An interface will be accessible on the defined port. 

This interface allow to send shell commands and will echo the command result on the wanted ports.

Commands can also be sent directly with wget or curl.

### Why?

Allow to control devices in an easy way.

As example, controls a raspberry pi directly via the local network.

There is no authentification. There is no keys to setup. 

### How?

Shell results are converted to html, then served with the php built-in server.

The server act as a daemon, wait for commands, and can open ports on demand. 

### When?

Anytime when an easy remote controller <b>without security</b> is desirable. 

This tool <b>won't replace ssh</b>, but allow to simulate his behavior in an easier way.

If you need security, <i>you are definetly looking on the wrong way</i>.


### Where?

Localhost, private networks. 

Yes! It can works fully on the public web, with just a port forwarding.

Again, <b>this tool is the complete opposite of a secure tool</b>.

### Who?

Nico Krazhtest https://ponyhacks.com


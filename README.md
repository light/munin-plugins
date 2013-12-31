munin-plugins
=============

To install the plugins, clone the repository somewhere, and run as root:

```bash
munin-node-configure --libdir=/absolute/path/to/munin-plugins --shell
```

Then copy/paste the commands related to the plugins you're interested in and restart munin-node.

By default Munin will run the plugins as user nobody:munin so make sure the directory is accessible to this user (i.e. don't put it in /root).

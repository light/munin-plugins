munin-plugins
=============

To install the plugins, clone the repository somewhere, then run as root:

```bash
munin-node-configure --libdir=munin-plugins --shell
```

Then copy/paste the commands related to the plugins you're interested in.

By default Munin will run the plugins as user nobody:munin so make sure the directory is accessible to this user (i.e. don't put it in /root).

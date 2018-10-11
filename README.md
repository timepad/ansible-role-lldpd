#### ansible role for lldpd

Installs and configures lldpd. As simple as that.

##### Params
lldpd doesn't have traditional config file, instead it takes arguments specified in /etc/default/lldpd
This options can be specified in 
```
lldpd_args
```
It's empty by default, meaning it will listen on all interfaces and respond to LLDP.
For a full list of argument please consult [lldpd docs](https://vincentbernat.github.io/lldpd/usage.html)

# Troubleshooting MicroPCF (Pivotal Cloud Foundry)

## Troubleshooting


1.

```
The box you're attempting to add has no available version that
matches the constraints you requested. Please double-check your
settings. Also verify that if you specified version constraints,
that the provider you wish to use is available for these constriants.

Box: micropcf/base
Address: https://atlas.hashicorp.com/micropcf/base
Constraints: 0
Available versions: 0.0.1, 0.1.0, 0.2.0, .... etc
```

1. Ubuntu 14.04 LTS does not install a compatible version of Vagrant by default.  A compatible version can be found on the [Vagrant Downloads](http://www.vagrantup.com/downloads.html) page.
1. Use an Administrator shell to deploy using VMware Workstation on Windows.

1. DNS
`cf api --skip-ssl-validation`
`cf ssh -k`

## What external ports are unavailable to bind as TCP routes?

The following ports are reserved for use by Lattice:

|     |     |     |     |     |
|-----|-----|-----|-----|-----|
|22   |53   |80   |1169 |1234 |
|1700 |2222 |2380 |4001 |4222 |
|4223 |7001 |7777 |8070 |8080 |
|8081 |8082 |8090 |8300 |8301 |
|8302 |8400 |8444 |8500 |8888 |
|8889 |9016 |9999 |17009|17014|
|17110|17111|17222|44445|     |

# Copyright

See [LICENSE](LICENSE) for details.
Copyright (c) 2015 [Pivotal Software, Inc](http://www.pivotal.io/).

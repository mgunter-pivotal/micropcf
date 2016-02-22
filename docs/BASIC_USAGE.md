## Connecting to PCF Dev

### Targeting Your PCF Dev Instance

To begin using PCF Dev, please run:

```
cf api api.local.pcfdev.io --skip-ssl-validation
cf login

Email: admin
Password: admin
```

Your target api domain will be printed when you `vagrant up`. It will most likely be api.local.pcfdev.io. If you're running on AWS it will be a domain ending in .xip.io

### [Using PCF Dev]

See the CF CLI documentation, [here](http://docs.pivotal.io/pivotalcf/devguide/deploy-apps/deploy-app.html)

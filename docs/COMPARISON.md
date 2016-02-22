## PCF Dev Side-By-Side Comparison
|                                                                           | PCF Dev                    | PCF                                   | CF            |
| ---                                                                       | ---                        | ---                                   | ---           |
| Space required                                                            | 15 GB                      | []                                    | []            |
| Memory required                                                           | 1.5 GB                     | []                                    | []            |
| Deployment                                                                | `vagrant up`               | OpsMan                                | `bosh deploy` |
| Estimated time-to-deploy                                                  | 10 Minutes                 | Hour+                                 | Hour+         |
| Out-of-the-Box Services                                                   | Redis<br>MySQL<br>RabbitMQ | Redis<br>MySQL<br>RabbitMQ<br>Gemfire | N/A           |
| Elastic Runtime                                                           | ✓                          | ✓                                     | ✓             |
| Logging/Metrics                                                           | ✓                          | ✓                                     | ✓             |
| Routing                                                                   | ✓                          | ✓                                     | ✓             |
| Compatible with cf cli                                                    | ✓                          | ✓                                     | ✓             |
| Deploy apps with any supported buildpack                                  | ✓                          | ✓                                     | ✓             |
| Supports Multi-Tenancy                                                    | ✓                          | ✓                                     | ✓             |
| Diego Support                                                             | ✓                          | ✓                                     | ✓             |
| Docker Support                                                            | ✓                          | ✓                                     | ✓             |
| DEA Support                                                               |                            | ✓                                     | ✓             |
| User-Provided Services                                                    | ✓                          | ✓                                     | ✓             |
| High Availability                                                         |                            | ✓                                     | ✓             |
| Integration with 3rd party Authorization                                  |                            | ✓                                     | ✓             |
| Bosh Director<br>(i.e. cannot deploy additional Bosh Manifests)           |                            | ✓                                     | ✓             |
| Day Two Lifecycle Operations<br>(e.g. rolling upgrades, security patches) |                            | ✓                                     | ✓             |
| Ops Manager                                                               |                            | ✓                                     |               |
| Apps Manager                                                              |                            | ✓                                     |               |
| Tile Support                                                              |                            | ✓                                     |               |
| Developers have root-level access across cluster                          | ✓                          |                                       |               |
| Pre-provisioned                                                           | ✓                          |                                       |               |
| Deploys without BOSH                                                      | ✓                          |                                       |               |

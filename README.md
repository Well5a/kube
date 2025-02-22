# kube


## Directory structure
| directory / file  | content |
| ----------------- | ------- |
| [./k8/](k8)     | kubernetes deployments for the T2 project | 
| [./docker/](docker)     | docker compose file for the T2 project | 
| [./testsetup/](testsetup)     | kube files for the e2e test service and kube files for ui backend and payment in test mode |
| [./loadprofiles/](loadprofiles)   | load profiles for the Apache jMeter load generator |   
| [./prometheusfiles/](prometheusfiles)| config / rules / alerts for prometheus |   
| [./setenv.sh](setenv.sh)       | export environment variables required do build the T2 store locally |
| [./start.sh](start.sh)       | install kubernetes deployments, including required helm charts |
| [./stop.sh](stop.sh)       | uninstall kubernetes deployments, including the helm charts |

For more information confer the [https://t2-documentation.readthedocs.io/en/latest/](documentation).
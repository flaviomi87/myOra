In order to admit arbitrary execution of docker images in Openshift, we need to relax the permissions for EVERY project we want to allow it.
After login in oc console (use the OOTB login command provided with OCPConsole) just use the command described in  Automation/OC_Service-Account

# SAMPLE OpenShift
This repository contains DockerFiles, scripts and BINARY (to be moved in an external repository) to build and distribute images for PAAS Project.

## Current product available
 - Oracle WebLogic
### Version Available
- 12.2.1.3-dev (with Patch 27117282)
- 12.2.1.3 (with Patch 27117282)
- 12.2.1.3-infra (with Patch 27117282)
- 12.1.3.0
 
## To Do:

- Script the deployment of application
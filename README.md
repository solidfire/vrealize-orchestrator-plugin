# NetApp Solidfire vRealize Orchestrator Plug-in

## Summary

The NetApp SolidFire vRealize Orchestrator Plug-in provides a convenient way to use the SolidFire API to administer your SolidFire storage system with VMware vRealize Orchestrator. Each SolidFire API method is modeled as a workflow in the plug-in, enabling you to combine the inputs and outputs of these  workflows to schedule and automate complex storage administration tasks. The plug-in provides more than 120 workflows and actions for controlling your SolidFire storage system. The NetApp SolidFire vRealize Orchestrator Plug-in integrates with higher level VMware management software, such as VMware vRealize Automation and vCloud Director, to provide storage orchestration across the VMware ecosystem.

### Highlights

- Execute most API commands from the Solidfire API within vRealize Orchestrator
- Guarantee per-VM and per-Datastore QoS

## Tech Specs

The installation of this plug-in requires that the following components have been deployed and configured:
- vRealize Orchestrator Version 7.2
- vCenter Server compatible with vRealize Orchestrator Version 7.2
- Solidfire Cluster running Element OS Version 8.0 or above

### SolidFire & API Support
- Element OS Version 9.0 or above
- All API methods are available except the following:
  - createCluster
  - getBootstrapConfig
  - invokeSFApi
  - setSnmpACL
  - disableSnmp
  - enableSnmp
  - setClusterConfig
  - setConfig
  - setNetworkConfig
  - setSnmpInfo
  - setSnmpTrapInfo

## Support

Please send all requests to: ng-SF-Support@netapp.com

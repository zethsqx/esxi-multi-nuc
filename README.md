# esxi-multi-nuc

## Overview

Stretched VLAN across multiple Intel NUC.   
Openshift deployed across a home based setup with minimal available hardware  
Extra vlan configured for accomodating other usage

## Installation
- Intel NUC
- Mikrotik Switch RB3011UiAS on RouterOS v6.46.3 (stable)
- ESXi 6.7
- OpenShift 4x

## Mikrotik Consideration
- Bridge all ether (eg. ether1_wan, ether2, ether3..)
- Configure such that all ESXi management interface are external IP
- Isolate all VLAN

## Reference  
<img src="images/diagram.png" width="80%" />

## Additional 
Extension of current architecture to multi-cloud 

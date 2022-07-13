# Moving Target Defense Threat Modeling for Cyber-Physical Systems

Cyber-physical systems (CPSs) rely upon the deep integration of computation and physical processes/systems, enabled by the Internet of Things, edge computing, and cloud technologies. Noticeably, cybersecurity is a major concern in CPSs, since attacks may exploit both cyber and physical vulnerabilities and damage significantly physical equipment, compromise operational safety, and impact negatively on product quality and performance. In this context, CPS design should take both security and resilience requirements into account, by identifying the needed measures not only to prevent but also to withstand, recover from, and adapt to adverse conditions and attacks. 

Our Threat Catalogue aims to improve the security and resilience of a CPS deployment by supporting the threat modeling process of a CPS and the identification, based on spotted threats and on the properties of involved assets and data, of the security controls to include within the design to mitigate existing threats and of the MTD techniques to integrate in order to increase resilience.

## MTDThreatCatalogueCPS.xlsx

It comprises a collection of threats related to the assets that compose a CPS. Our Threat Catalogue correlates threats, assets, assets properties, data typology, data sensitivity, [NIST security control](https://csrc.nist.gov/Projects/risk-management/sp800-53-controls/release-search#/families?version=5.1), as well as moving target defense (MTD) techniques. Moreover, it also provides an excel sheet that reports useful information concerning MTD techniques and their implementation.

The catalogue is fully extensible, any suggestions or contributions is really welcomed!

## MTDThreatModelingCPS
We implemented the MTD Threat Catalogue for CPS through the Microsoft Threat Modeling Tool. To automate threat identification as well as security mitigation to adopt, we created a template named *MTDThreatModelingCPS*. Users can use the template to model their application through an intuitive drag-and-drop approach using the assets belonging to a CPS. Beyond selecting the asset, users must also provide high-level information (i.e., asset location, capability, data typology, data sensitivity) associated with the chosen component. Once the system has been modeled, the user will be automatically provided with a collection of threats associated with each asset and the corresponding security countermeasure to enforce.

### Usage
To use our template and start modeling a CPS system, follow the steps reported below:

1.  Download the [Microsoft Threat Modeling Tool](https://docs.microsoft.com/en-gb/azure/security/develop/threat-modeling-tool);
2.  Download the MTDThreatModelingaCPS.tb7 model;
3.  Open the Microsoft Threat Modeling Tool Application;
4.  Browse and select the downloaded model, using the button below *Template For New Models*;
5.  Click on *Create a Model*; 
6.  Start modeling your system;

Click [here](https://docs.microsoft.com/en-us/azure/security/develop/threat-modeling-tool-getting-started) to get started with the Threat Modeling Tool.

### Status

The template is still under development.

### Acknowledgment

We would like to thank the following creators for the icon used in our template:

* <a href="https://www.flaticon.com/free-icons/server" title="server icons">Server icons created by vectorsmarket15 - Flaticon</a>
* <a href="https://www.flaticon.com/free-icons/motion-sensor" title="motion sensor icons">Motion sensor icons created by Freepik - Flaticon</a>
* <a href="https://www.flaticon.com/free-icons/server" title="server icons">Server icons created by Freepik - Flaticon</a>
* <a href="https://www.flaticon.com/free-icons/multi-channel" title="multi channel icons">Multi channel icons created by smashingstocks - Flaticon</a>

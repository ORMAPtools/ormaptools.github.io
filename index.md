---
permalink: /
---
**ORMAP Tools** project will help you 
transition to managing Oregon county parcel data using Parcel Fabric with ArcGIS Pro and (optionally) ArcGIS Enteprise.

All the ORMap Tools repositories are in
[this Github repository](https://github.com/ORMAPTools)
including both potential future projects and legacy work done 5+ years ago for ArcMap.

## Survey

Please fill out this [Conversion Status survey](https://docs.google.com/forms/d/e/1FAIpQLScLnnL2K0-6XgkTuEsw7QQ-Sx-LXNLE1jY4Y5ATNiESmDRE_A/viewform?vc=0&c=0&w=1&flr=0&pli=1&fbzx=5578410564896297533")
to let us know the status for your county.  
This will also give us an updated contact list.


## ORMAP's Tools for cartographers


### Prerequisites

These tools are designed and tested with **ArcGIS Pro 2.9.4**.
They might still work with **ArcGIS Pro 2.8.x** but we're not actively testing there.
Everything is intended to work with Parcel Fabric, either in a FileGeodatabase or Enterprise.
If you are using Enterprise make sure it's the version that matches the version of ArcGIS Pro you are using; Pro 2.9 requires Enterprise 10.9 and Pro 2.8 requires Enterprise 10.8.

(At this time, ArcGIS Pro 3.0.2 is available. It requires Enterprise 11. We're
not ready to go there yet.)
    

### Videos

These videos are available on Youtube in the [ORMAP Tools channel](https://www.youtube.com/channel/UCzm6fVzsVVk8LtuvzdPRmnQ). Subscribe! Like! (or don't; we don't care!)

[![Overview playlist](https://i.ytimg.com/vi/rTX02Jr4_qw/default.jpg)](https://youtube.com/playlist?list=PLOvsczC41I8ZbmCx709fCed38b8ZU4DUf)
Overview: Tutorial series with narration

[![Basic Introduction playlist](https://i.ytimg.com/vi/-og4oB9QDJw/default.jpg)](https://youtube.com/playlist?list=PLOvsczC41I8Ygz1G47wEqrtdLtMXfiXzm)
Basic Introduction: A set of short videos to show how to use different ORMAP tools.

### Parcel Fabric

The ORMAP **Parcel Fabric Template** specifies the format the ORMAP team
has developed, in the form of an Esri File Geodatabase. There is a folder, Documents/
that contains a collection of notes on the design and implementation.
[ORMAP-ParcelFabric-3.0.zip](https://github.com/ORMAPtools/ORMAP-ParcelFabric/archive/refs/tags/3.0.zip) version 3.0, 09/12/2022

**T7-4 Pilot Data**: [T7-4.zip](downloads/T7-4.zip) 
The Polk T7-4 sample data complete with operational data, and all rules and tools. (version 3.0.1, 09/28/2022)
This is a test data set, so that you can try out parcel fabric and the ORMap tools.

### Tools and Rules

**ArcGIS Pro toolbox** + python scripts:  [ORMAPToolsV3.0.1.zip](downloads/ORMAPToolsV3.0.1.zip) (version 3.0.1, 09/28/2022) This zip file is for those who just want the **tools**. In github, [ORMAP-Tools](https://github.com/ORMAPTools/ORMAP-Tools)

**Rules Export**: [RulesExport.zip](https://github.com/ORMAPtools/RuleExports/archive/refs/tags/3.0.1.zip)
Exported rules from T7-4 sample folder for those how just want the **rules**.
In github, find it at [RuleExports](https://github.com/ORMAPTools/RuleExports)

In theory the github versions ***could be*** newer than the zip files, but in practice, we currently upload to github just before doing a new release.

### Addin tools

These are set up as ArcGIS Pro "addins".

* Annotation Tasks [ORMAPTasks6-4-2022.zip](downloads/ORMAPTasks6-4-2022.zip) (added 2022-Jun-04)
* Cartographic Arrow Tools: [ORMAPArrowTools-20220110-0930.esriAddinX](https://github.com/ORMAPtools/ArrowTools/raw/main/ORMAPArrowTools-20220110-0930.esriAddinX)
* Cancelled Numbers Manager: [ORMAPCancelledNumbers.esriAddinX](https://github.com/ORMAPtools/CancelledNumbersManager/raw/main/Install/ORMAPCancelledNumbers.esriAddinX)

## Additional resources

Esri learning guide ["Recommended Esri Training for Oregon Land Records Modernization"](docs/ArcGIS%20Training%20Plan%20For%20ORMAP%20for%20JS_edit.pdf) ***August 2021***  
This includes information on instructor-led courses and E-learning tutorials and videos.

### Publishing parcel fabric

Web page: [Workflow: Prepare and publish parcel fabric
](https://pro.arcgis.com/en/pro-app/latest/help/data/parcel-editing/workflow-publishpf.htm)

Video: [Parcel Fabric: Migrating and administrating parcels with ArcGIS Pro](https://www.esri.com/videos/watch?videoid=zvTSIHKHC54&title=parcel-fabric-migrating-and-administrating-parcels-with-arcgis-pro)  
48 minute mark of this video shows how to publish a parcel fabric  

### Source code for developers

All the code for the ZIP files is available via Github in the [ORMAP-Tools repositories](https://github.com/ORMAPtools).
Each repository has additional documentation.

Python tools (no special build operations required)
* [ORMAPtools/ORMAP-Tools](https://github.com/ORMAPtools/ORMAP-Tools)

Addins, written in C# (will require a compiler to build)
* [ORMAPtools/ArrowTools](https://github.com/ORMAPtools/ArrowTools)
* [ORMAPtools/CancelledNumbersManager](https://github.com/ORMAPtools/CancelledNumbersManager)

The addins are written in the Esri "addin" format, and they are C# .Net projects.
You need Visual Studio to build new versions. (The free Community version works.)

***9/28/2022 03:19PM***
---
permalink: /
---
All the ORMapTools repositories are in
[this Github repository](https://github.com/ORMAPTools)
including both potential future projects and legacy work done 5+ years ago.

This page will introduce you to the "ORMAP Tools" project that will help you 
transition to managing county parcel data using Parcel Fabric with ArcGIS Pro and ArcGIS Enteprise.

## Survey

Please fill out this [Conversion Status survey](https://docs.google.com/forms/d/e/1FAIpQLScLnnL2K0-6XgkTuEsw7QQ-Sx-LXNLE1jY4Y5ATNiESmDRE_A/viewform?vc=0&c=0&w=1&flr=0&pli=1&fbzx=5578410564896297533")
to let us know the status for your county.  
This will also give us an updated contact list.

## Resources

Esri learning guide ["Recommended Esri Training for Oregon Land Records Modernization"](docs/ArcGIS%20Training%20Plan%20For%20ORMAP%20for%20JS_edit.pdf) ***August 2021***  
This includes information on instructor-led courses and E-learning tutorials and videos.

### Publishing parcel fabric

Web page: [Workflow: Prepare and publish parcel fabric
](https://pro.arcgis.com/en/pro-app/latest/help/data/parcel-editing/workflow-publishpf.htm)

Video: [Parcel Fabric: Migrating and administrating parcels with ArcGIS Pro](https://www.esri.com/videos/watch?videoid=zvTSIHKHC54&title=parcel-fabric-migrating-and-administrating-parcels-with-arcgis-pro)  
48 minute mark of this video shows how to publish a parcel fabric  

## Tools for cartographers

**Software version requirements:** 
The tools here are designed and tested with **ArcGIS Pro 2.8**.
Some counties are already moving to **ArcGIS Pro 2.9**
Everything is intended to work with Parcel Fabric, either in a FileGeodatabase or Enterprise.
If you are using Enterprise make sure it's the version that matches the version of ArcGIS Pro you are using; Pro 2.8 requires Enterprise 10.8 and Pro 2.9 requires Enterprise 10.9.
    
### Downloads

#### Videos

These videos are available on Youtube in the "ORMAP Tools" channel.

[![Overview playlist](https://i.ytimg.com/vi/rTX02Jr4_qw/default.jpg)](https://youtube.com/playlist?list=PLOvsczC41I8ZbmCx709fCed38b8ZU4DUf)
Playlist: Tutorial series with narration

[![Basic Introduction playlist](https://i.ytimg.com/vi/-og4oB9QDJw/default.jpg)](https://youtube.com/playlist?list=PLOvsczC41I8Ygz1G47wEqrtdLtMXfiXzm)
Playlist: A set of short videos to show how to use different ORMAP tools.

#### Parcel Fabric

ORMAP Parcel Fabric Template: [ORMAPPF2.02.zip](downloads/ORMAPPF2.02.zip) This is a template file geodatabase that you can populate with your own data. (updated 2022-May-04)

Pilot data: [T7-4V2.03.zip](downloads/T7-4V2.03.zip) Parcel fabric containing sample data from Polk County, all tools including conversion tools
This is a test data set, so that you can try out parcel fabric and the ORMap tools.
(updated 2022-Jun-04)

#### Tools

ArcGIS Pro toolbox + python scripts:  [ORMapToolsV2.01.zip](downloads/ORMAPToolsV2.01.zip)

Addin tools-- These are set up as ArcGIS Pro "addins".

Annotation Tasks [ORMAPTasks6-4-2022.zip](downloads/ORMAPTasks6-4-2022.zip) (added 2022-Jun-04)

Cartographic Arrow Tools: [ORMAPArrowTools-20220110-0930.esriAddinX](https://github.com/ORMAPtools/ArrowTools/raw/main/ORMAPArrowTools-20220110-0930.esriAddinX)

Cancelled Numbers Manager: [ORMAPCancelledNumbers.esriAddinX](https://github.com/ORMAPtools/CancelledNumbersManager/raw/main/Install/ORMAPCancelledNumbers.esriAddinX)

https://raw.githubusercontent.com/ORMAPtools/CancelledNumbersManager/master/Install/ORMAPCancelledNumbers.esriAddinX

## For developers

All the code for the ZIP files is available via Github in the [ORMAP-Tools repositories](https://github.com/ORMAPtools).
Each repository has additional documentation.

[ORMap Toolbox repository](https://github.com/ORMAPtools/ORMAP-Tools)

The toolbox does not require any special build tools (other than ArcGIS Pro!), the code is written in Python and Arcade.

### Addins

[Cartographic Arrow Tools repository](https://github.com/ORMAPtools/ArrowTools)  
[Cancelled Numbers Manager repository](https://github.com/ORMAPtools/CancelledNumbersManager)

The addins are written in the Esri "addin" format, and they are C# .Net projects.
You need Visual Studio to build new versions. (The free Community version works.)

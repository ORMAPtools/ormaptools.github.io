---
permalink: /
---
## Introduction

**ORMAP Tools** project will help you 
transition to managing Oregon county parcel data using Parcel Fabric with ArcGIS Pro and (optionally) ArcGIS Enteprise. It provides a framework to
interoperate easily with Oregon Department of Revenue and with other counties.

[Land Records Modernization & ORMAP Training Strategy](downloads/OR_Land_Records_Strategy_Canvas_final.pdf) -- Basically an
overview of this entire project, all on one page.

All the ORMap Tools repositories are in
[this Github repository](https://github.com/ORMAPTools)
including both potential future projects and legacy work done 5+ years ago for ArcMap.

### Recent Meeting

**9/28/2022**-- ORMAP tools group [Meeting notes](downloads/)  
Recording of the [meeting on YouTube](https://youtu.be/ep14fxZrXxo)

### Survey

Please fill out this [Conversion Status survey](https://docs.google.com/forms/d/e/1FAIpQLScLnnL2K0-6XgkTuEsw7QQ-Sx-LXNLE1jY4Y5ATNiESmDRE_A/viewform?vc=0&c=0&w=1&flr=0&pli=1&fbzx=5578410564896297533")
to let us know the status for your county.  
This will also give us an updated contact list.


## Training materials

Esri learning guide ["Recommended Esri Training for Oregon Land Records Modernization"](docs/ArcGIS%20Training%20Plan%20For%20ORMAP%20for%20JS_edit.pdf) ***August 2021***  
This includes information on instructor-led courses and E-learning tutorials and videos.

Esri ArcGIS Pro doc: [Workflow: Prepare and publish parcel fabric
](https://pro.arcgis.com/en/pro-app/latest/help/data/parcel-editing/workflow-publishpf.htm)


### Videos

These videos are available on Youtube in the [ORMAP Tools channel](https://www.youtube.com/channel/UCzm6fVzsVVk8LtuvzdPRmnQ).


* [ORMAP Tools Overview](https://youtube.com/playlist?list=PLOvsczC41I8ZbmCx709fCed38b8ZU4DUf) -- Tutorial series with narration
* [Basic Introduction](https://youtube.com/playlist?list=PLOvsczC41I8Ygz1G47wEqrtdLtMXfiXzm) -- Short videos to show how to use each ORMAP tool

Esri video: [Parcel Fabric: Migrating and administrating parcels with ArcGIS Pro](https://www.esri.com/videos/watch?videoid=zvTSIHKHC54&title=parcel-fabric-migrating-and-administrating-parcels-with-arcgis-pro)  
(48 minute mark of this video shows how to publish a parcel fabric.)

## Downloads

### Prerequisites

These tools are designed and tested with **ArcGIS Pro 2.9.4**.
They might still work with **ArcGIS Pro 2.8.x** but we're not actively testing there.
Everything is intended to work with Parcel Fabric, either in a FileGeodatabase or Enterprise.
If you are using Enterprise make sure it's the version that matches the version of ArcGIS Pro you are using; Pro 2.9 requires Enterprise 10.9 and Pro 2.8 requires Enterprise 10.8.

(At this time, ArcGIS Pro 3.0.2 is available. It requires Enterprise 11. We're
not ready to go there yet.)
    
### Data

[ORMAP-ParcelFabric-3.0.zip](https://github.com/ORMAPtools/ORMAP-ParcelFabric/archive/refs/tags/3.0.zip) version 3.0, 09/12/2022  
The ORMAP **Parcel Fabric Template** specifies the format the ORMAP team
has developed, in the form of an Esri File Geodatabase. Within the ZIP file, the 
"Documents" folder contains a collection of notes on the design and implementation.

[T7-4.zip](downloads/T7-4.zip) 3.0.1 9/28/2022   
**T7-4 Pilot Data**: The Polk T7-4 sample data complete with operational data, and all rules and tools. This is a test data set, so that you can try out parcel fabric and the ORMap tools.

### Tools

[ORMAPToolsV3.0.1.zip](downloads/ORMAPToolsV3.0.1.zip) 3.0.1, 09/28/2022  
**ArcGIS Pro toolbox**:   This zip file is for those who just want the **tools**.

[RulesExport.zip](https://github.com/ORMAPtools/RuleExports/archive/refs/tags/3.0.1.zip) 3.0.1, 9/28/2022  
Exported rules from T7-4 sample folder for those how just want the **rules**.

### Addin tools

These are set up as ArcGIS Pro "addins".

[ORMAPTasks6-4-2022.zip](downloads/ORMAPTasks6-4-2022.zip) 06/04/2022 -- Annotation Tasks 

[ORMAPArrowTools-20220110-0930.esriAddinX](https://github.com/ORMAPtools/ArrowTools/raw/main/ORMAPArrowTools-20220110-0930.esriAddinX) 01/10/2022  -- Cartographic Arrow Tools

[ORMAPCancelledNumbers.esriAddinX](https://github.com/ORMAPtools/CancelledNumbersManager/raw/main/Install/ORMAPCancelledNumbers.esriAddinX) -- Cancelled Numbers Manager


## For developers

All the source code is available via Github in the [ORMAP-Tools repositories](https://github.com/ORMAPtools).
Each repository has additional documentation.
In theory the github versions ***could be*** newer than the downloadable zip files, but in practice, we currently upload to github just before doing a new release.

Toolbox, including Python code (no special build operations required)
* [ORMAPtools/ORMAP-Tools](https://github.com/ORMAPtools/ORMAP-Tools)

Addins, written in C#. You need Visual Studio to build new versions. (The free Community version works.)

* [ORMAPtools/ArrowTools](https://github.com/ORMAPtools/ArrowTools)
* [ORMAPtools/CancelledNumbersManager](https://github.com/ORMAPtools/CancelledNumbersManager)


***9/29/2022 10:15AM***

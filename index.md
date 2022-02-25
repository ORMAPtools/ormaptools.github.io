---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
# ORMap Tools
   
All the ORMapTools repositories are in
[this Github repository](https://github.com/ORMAPTools")
including both potential future projects and legacy work done 5+ years ago.

This page will introduce you to the current "ORMAP tools" project that will help you 
transition to managing county parcel data using Parcel Fabric with ArcGIS Pro and ArcGIS Enteprise.
        

## State wide status of ORMAP Tools project

Please fill out this Google Docs form to let us know the status for your county. This will also give us an updated contact list.
[Conversion Status survey](https://docs.google.com/forms/d/e/1FAIpQLScLnnL2K0-6XgkTuEsw7QQ-Sx-LXNLE1jY4Y5ATNiESmDRE_A/viewform?vc=0&c=0&w=1&flr=0&pli=1&fbzx=5578410564896297533")

## Resources

Esri learning guide ["Recommended Esri Training for Oregon Land Records Modernization"](ArcGIS%20Training%20Plan%20For%20ORMAP%20for%20JS_edit.pdf) ***August 2021***
This includes information on instructor-led courses and E-learning tutorials and videos.

### Publishing parcel fabric

PDF: <a target="new" href="https://pro.arcgis.com/en/pro-app/latest/help/data/parcel-editing/workflow-publishpf.htm">Workflow: Prepare and publish parcel fabric</a>

Video: <a target="new" href="https://www.esri.com/videos/watch?videoid=zvTSIHKHC54&title=parcel-fabric-migrating-and-administrating-parcels-with-arcgis-pro">Parcel Fabric: Migrating and administrating parcels with ArcGIS Pro</a>
48 minute mark of this video shows how to publish a parcel fabric  

## Tools for cartographers

### Documentation

23-Feb-22 9:30 coming soon

* docs
* videos
    
### Downloads

23-Feb-22 9:30am these are not real links yet. They will all link to ZIP files when I am done.

### Parcel Fabric

ORMAPParcelFabric.zip This is an ORMAP template with a file geodatabase you can populate. 

T74V2.0.zip Pilot data. Parcel fabric containing sample data from Polk County, all tools including conversion tools
This is a test data set, so that you can try out parcel fabric and the ORMap tools.

#### Tools

<a href="https://github.com/ORMAPtools/ORMAP-Tools/archive/refs/heads/main.zip">ORMap Toolbox</a><br />
This is an ArcGIS Pro toolbox.
                        
release information
https://github.com/ORMAPtools/ORMAP-Tools/releases.atom

Addin tools-- These are set up as ArcGIS Pro "addins".

* <a href="https://github.com/ORMAPtools/ArrowTools">Cartographic Arrow Tools</a>
* <a href="https://github.com/ORMAPtools/Cancelled Numbers Manager">CancelledNumbersManager</a>

## For developers

You can download the code for the addin tools, modify it, build your own.
Each repository has documentation on how to build it.

### Toolbox

The "ORMAP toolbox" is provided as an Esri toolbox, and the associated code is written in Python.

<a href="https://github.com/ORMAPtools/ORMAP-Tools">ORMap Toolbox repository</a>

### Addins

These tools are written in the Esri addin format, they are C# .Net projects.
You need Visual Studio to build new versions.

* <a href="https://github.com/ORMAPtools/ArrowTools">Cartographic Arrow Tools</a></li>
* <a href="https://github.com/ORMAPtools/Cancelled Numbers Manager">CancelledNumbersManager</a>
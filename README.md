# ormaptools.github.io

This is Github Pages for ORMAPtools.

Look for it at https://ormaptools.github.io

## Overview

Uses jekyll to generate static pages.
I run jekyll in a Docker container because I don't want to install it on my computer.

## Test and develop

Create boilerplate (for new projects only)

```bash
export REPO="$USERPROFILE/source/repos/wildsong.github.io"
docker run --rm --name=jekyll --volume="$REPO:/srv/jekyll" jekyll/jekyll jekyll new website
```

Run a test server, with hot reload

```bash
export REPO="$USERPROFILE/source/repos/wildsong.github.io"
docker run --rm --name=jekyll \
  --volume="$REPO:/srv/jekyll" \
  --publish 4000:4000 \
  jekyll/jekyll \
  jekyll serve --incremental
```
(Do I want --incremental?)

This will start the service running on port 4000, see http://localhost:4000/


## Resources

## Futher adventures

* Add actual content to index.html
* Styles




From Mark Williams to Everyone 10:56 AM
Doc on publishing a parcel fabric... https://pro.arcgis.com/en/pro-app/latest/help/data/parcel-editing/workflow-publishpf.htm
48 minute mark of this video shows how to publish a parcel fabric  https://www.esri.com/videos/watch?videoid=zvTSIHKHC54&title=parcel-fabric-migrating-and-administrating-parcels-with-arcgis-pro

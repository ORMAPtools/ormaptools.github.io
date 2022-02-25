# ormaptools.github.io

This is Github Pages for ORMAPtools.

Look for it at https://ormaptools.github.io

## Overview

### Site generator comment

Using jekyll is the approved way to generate HTML for Github Pages.
I want to use it because editing HTML by hand is kind of a pain,
and it will let me directly use some other Github features like
embedding project metadata in pages so that it will update automatically.

I tried using Jekyll in Docker but could not get the "livereload" feature working.
Not so far. Maybe tomorrow. In the meantime I installed into a Debian Linux machine.

```bash
sudo apt install ruby-full build-essential
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
gem install jekyll bundler
```

## Test and develop

Start Visual Studio Code, launch test server

```bash
jekyll serve -l
```

## Resources

[Jekyll home page](https://jekyllrb.com/docs/installation/)

## Futher adventures

* Add actual content to index.html
* Work on styles




From Mark Williams to Everyone 10:56 AM
Doc on publishing a parcel fabric... https://pro.arcgis.com/en/pro-app/latest/help/data/parcel-editing/workflow-publishpf.htm
48 minute mark of this video shows how to publish a parcel fabric  https://www.esri.com/videos/watch?videoid=zvTSIHKHC54&title=parcel-fabric-migrating-and-administrating-parcels-with-arcgis-pro

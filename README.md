# README.md
2022-09-28

The github project is the web page. 
Look in https://ormaptools.github.io/

## When Dean shares new files,

1. Unzip them, do any needed polishing.
2. If anything changed, zip them and name them as needed.
3. Check them into github and tag as a new release.
4. Move the old zip files in downloads/ into ARCHIVE/
5. Put the zip files in ormaptools.github.io/downloads.
6. Update the .MD files
7. Commit, Push, Tag, done!

## "1. Unzip" is a gross misstatement.

Actually depending on the file you need to unzip them, move contents
into various repositories and folders, check them into github
and sometimes you need create a new zip, other times github will do that for you.

Good luck future Brian. You should put more detailed notes here.

## How do I "6. Update the .MD files"?

They are just text files in "markdown" format. Use an editor. 
VS Code has a preview mode. 
Look up "github markdown" to learn about it. The github version
is slightly different than generica markdown.

You edit them and then 
in step 7 when they get pushed to github, it will trigger an action
that converts them into HTML files. I am not sure how long it takes
the action to run but it's magical. They just turn into HTML.

## Regarding "7. Commit..." -- Git commands that I forget between releases.

List the current tags on this repo.oH

```bash
git tag -l
```

Tag the current version, then push the tag up to Github

```bash
git commit -m 'doing a new release' -a
git push
git tag -a 3.0.3 -m "Put a reasonable comment here"
git push origin 3.0.3
```

## What about videos?

When we have a Zoom meeting, an MP4 recording needs to be shared to our YouTube channel.

Update the index.md as needed.

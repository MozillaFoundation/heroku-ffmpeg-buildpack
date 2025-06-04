# heroku-ffmpeg-buildpack

## Description
Buildpack to add ffmpeg to a heroku-22 app. Modify bin/compile to change version / source. See related repo (https://github.com/MozillaFoundation/heroku-ffmpeg-static-builds) for compiling / uploading safe sources.

## Release (and deploy to Mozilla Foundation site)
1) Create a new tag / release
2) Provide a link to the ffmpeg source in the tag / release description
3) Update the buildpack URL on heroku to use the new release URL (i.e. https://github.com/MozillaFoundation/heroku-ffmpeg-buildpack.git#ffmpeg-v6.1-latest)
4) Update the foundation site (https://github.com/MozillaFoundation/foundation.mozilla.org) `/app.json` and `/.github/workflows/check-ffmpeg-upstream-version.yml` to track the latest URL version (i.e. 6.1.2)

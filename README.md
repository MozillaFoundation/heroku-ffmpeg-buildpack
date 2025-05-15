# heroku-ffmpeg-buildpack
Buildpack to add ffmpeg to a heroku-22 app. Modify bin/compile to change version / source. See related repo (https://github.com/MozillaFoundation/heroku-ffmpeg-static-builds) for compiling / uploading safe sources.

Create a new tag / release (providing a link to the ffmpeg source in the description) and update the buildpacks on heroku to use it. (i.e. https://github.com/MozillaFoundation/heroku-ffmpeg-buildpack.git#ffmpeg-v6.1-latest)

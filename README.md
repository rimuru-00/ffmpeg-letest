# FFmpeg Buildpack for Heroku

This buildpack compiles FFmpeg from source with full codec and filter support.

## Features

- Compiles latest FFmpeg from official source
- Includes all available codecs and filters
- Optimized for Heroku environment
- Static compilation for better portability
- Full hardware acceleration support where available

## Usage

```bash
# Creating a new Heroku app
heroku create myapp

# Adding this buildpack
heroku buildpacks:add https://github.com/yourusername/ffmpeg-buildpack.git

# Or using with an existing app
heroku buildpacks:add https://github.com/yourusername/ffmpeg-buildpack.git -a myapp

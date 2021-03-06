# kawagoe
scenario-based exercise

# Functions of this repository
- To host the Dockerfile for unvt/kawagoe
- gh-pages from the `docs` directory
- running codes for scenario-based exercise, integrated in Rakefile

# First time installation
```zsh
$ yarn
```

# List of `rake` tasks
```
rake build:localhost  # build style.json for localhost
rake build:pages      # build style.json for gh-pages
rake build:raspi      # build style.json for raspberrypi.local
rake copy:mapbox_gl   # copy files from mapbox-gl-js
rake docker:build     # build unvt/kawagoe on docker
rake docker:run       # run unvt/kawagoe on docker
rake download:1013do  # download disaster orthophoto tiles
rake download:bvmap   # download GSI Maps Vector tiles
rake download:lc      # download landform classification data
rake host             # host the site
rake produce:lc       # produce vector tiles for landform data
rake view:lc          # view landform classification data
```

# Required external repositories
- gh:mapbox/mapbox-gl-js


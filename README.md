# plantuml-hot-reload
A really really simple tool that watchs changes in a plantuml.

# Motivation
It is a pain in the nack perform repetitive tasks. This script will watch changes in file using git diff, then, it will built
the .pu file while feh will be looking for changes in the output image.

# Install
```sh
$ git clone git@github.com:rafaelkendrik/plantuml-watch.git
$ cp plantuml-watch/plantuml-watch.sh /usr/bin/plantuml-watch
$ chmod +x /usr/bin/plantum-watch
```

# Usage
> Make sure you are watching a git file!

```sh
$ plantuml-watch my-file.pu
```
# shed

This could have been a Gist.

Anyway...

Here’s shed.

It’s a bash script that uses readability-cli to download stripped-down
pages and creates a html file with a human-readable filename.

The resulting files are **not styled**. However, you can use CSS styling
by adding a file called `style.css` to the same directory. I use
[SPCSS](https://susam.github.io/spcss/).

## requirements

- node.js
- npm (should come with node, ymmv)
- [readability-cli](https://gitlab.com/gardenappl/readability-cli/-/tree/main)

## install

```
wget https://raw.githubusercontent.com/phantomdiorama/shed/refs/heads/main/shed
chmod +x shed
mv shed /usr/local/bin # or somewhere in $PATH

```

## usage

```
shed [url]  # add [url] to shed
shed list   # list shedded files
```

## alternatives

- [Wget](https://en.m.wikipedia.org/wiki/Wget)
- [Pandoc](https://pandoc.org/)
- [Monolith](https://github.com/Y2Z/monolith)
- [SingleFile](https://github.com/gildas-lormeau/SingleFile)

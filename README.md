# shed

So... here’s shed.

It’s a bash script that uses readability-cli to download stripped-down
pages, links a minimal stylesheet ([SPCSS](https://susam.github.io/spcss/)
by default), and creates a html file with a human-readable filename.

## requirements

- node.js
- npm (should come with node, ymmv)
- [readability-cli](https://gitlab.com/gardenappl/readability-cli/-/tree/main)

## install

```
git clone https://github.com/phantomdiorama/shed.git
cd ~/shed
chmod +x shed
mv shed /usr/local/bin #<--or somewhere in $PATH

```

## usage

```
shed [url]  #<--add [url] to shed
shed list    #<--list shedded files
```

## alternatives

- [Monolith](https://github.com/Y2Z/monolith)
- [SingleFile](https://github.com/gildas-lormeau/SingleFile)
- [Pandoc](https://pandoc.org/)

# acknowledgements

SPCSS is licensed under MIT.

# shed

So... here’s shed.

It’s a bash script that uses readability-cli to download stripped-down
pages, links a minimal stylesheet ([spcss](https://susam.github.io/spcss/)
by default), and creates a html file with human-readable filename.

## requirements

- node.js
- npm (should come with node, ymmv)
- [readability-cli](https://gitlab.com/gardenappl/readability-cli/-/tree/main)

## install

```
cd ~
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

## faq

**Couldn’t this just be a gist:** Yes. Yes it could.
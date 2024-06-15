# shed

> A shed is typically a simple, single-story roofed structure, often used
> for storage, for hobbies, or as a workshop
>
>  -- Wikipedia

I had been keeping my web research as a bunch of pdf files. Mostly because
it was easy--just *print to pdf* in Firefox.

But there were things I didn’t like: the pdf format is unwieldy, large,
difficult to grep and unreadable on mobile. And the files created by
Firefox contained all the guff webpages use to distract you from the
actual content, making them difficult to skim through. Basically, I wanted
something better. Something cleaner.

So here’s Shed.sh.

It’s a bash script that uses readability-cli to download stripped-down
html, and links to a minimal css stylesheet
([spcss](https://susam.github.io/spcss/)).

## requirements

- node.js
- npm (should come with node, ymmv)
- [readability-cli](https://gitlab.com/gardenappl/readability-cli/-/tree/main)

## install

```
cd ~
git clone https://github.com/phantomdiorama/shed.git
cd ~/shed
sudo mv shed ~/.local/bin
sudo chmod +x ~/.local/bin

```

## usage

```
shed [url] <-- add [url] to shed
shed list  <-- list shedded files
```

## faq

**Why not plaintext:** I like being able to easily style the output with
css. And sometimes I want the images. That said, readability-cli can
grab just the page text if you want.

**Couldn’t this just be a gist:** Yes. Yes it could.

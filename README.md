# scala-mill-notes

[mill](https://com-lihaoyi.github.io/mill/)

### Install

```
brew instal mill

or

sudo curl -L https://github.com/lihaoyi/mill/releases/download/0.9.5/0.9.5 > /usr/local/bin/mill && sudo chmod +x /usr/local/bin/mill
```

`mill` only installs itself after being run the first time.

`mill version` to confirm installation.

### Run

```
mill main_class_name.compile

mill main_class_name.run
```

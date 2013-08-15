yeoman-webapp-backbone-diff
===========================

Diff between `yo webapp` and `yo backbone`

## Results ##



## How? ##

```bash
$ npm install -g yo generator-webapp generator-backbone
$ cd $GIST_REPO
$ yo webapp # remember defaults
$ git add . && git commit -m "yo webapp"
$ # rm -rf everything but README and .git/
$ yo backbone # insert defaults
$ git add . && git commit -m "yo backbone"
```
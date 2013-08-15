yeoman-webapp-backbone-diff
===========================

Diff between `yo webapp` and `yo backbone`

```bash
$ npm install -g yo generator-webapp generator-backbone
$ cd $GIST_REPO
$ npm list -g --depth=0 | ack "generator|yo"
├── generator-backbone@0.1.7
├── generator-express@1.0.1
├── generator-microlib@0.2.0
├── generator-mocha@0.1.1
├── generator-webapp@0.2.7
└── yo@1.0.0-rc.1.4
$ yo webapp # remember defaults
$ git add . && git commit -m "yo webapp"
$ # rm -rf everything but README and .git/
$ yo backbone # insert defaults
$ git add . && git commit -m "yo backbone"
```

## Results ##

Read the commit diff [here](https://github.com/tomfuertes/yeoman-webapp-backbone-diff/commit/9c096659534722018eee96714bd54b438f5c1ce8)

### Summary ###

Looks like not much has changed other than [`./app/scripts/main.js`](https://github.com/tomfuertes/yeoman-webapp-backbone-diff/blob/master/app/scripts/main.js).

### Takeaways ###

With a minor `./app/scripts/main.js` refreactor, you should be able to use your `yo webapp` project with the scaffolding of `yo backbone:model Todo`, etc...
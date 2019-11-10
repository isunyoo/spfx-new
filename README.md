Build SharePoint client-side web part (Hello World part 1)

https://docs.microsoft.com/en-us/sharepoint/dev/spfx/web-parts/get-started/build-a-hello-world-web-part

### ScriptLab for MS Office Products

Search Wiki for PowerPoint
https://gist.github.com/cakriwut/e60db14dfb89dc9a4368fe39596a3c4d

Simple Currency Converter for  EXCEL
https://gist.github.com/cakriwut/22eaaea6310e251f3f72b26c3ff51acb

### spfx-new(SharePoint Framework)

This is where you include your WebPart documentation.

### Building the code

```bash
git clone the repo
npm i
npm i -g gulp
gulp
```

This package produces the following:

* lib/* - intermediate-stage commonjs build artifacts
* dist/* - the bundled script, along with other resources
* deploy/* - all resources which should be uploaded to a CDN.

### Build options

gulp clean - TODO
gulp test - TODO
gulp serve - TODO
gulp bundle - TODO
gulp package-solution - TODO

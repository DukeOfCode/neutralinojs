
<div align="center">
  <img src="https://cdn.rawgit.com/neutralinojs/neutralinojs.github.io/b667f2c2/docs/nllogo.png" style="width:300px;"/>
</div>

[![HitCount](http://hits.dwyl.io/neutralinojs/neutralinojs.svg)](http://hits.dwyl.io/neutralinojs/neutralinojs)


NeutralinoJs is a portable and lightweight framework to develop apps with native functions and it allows you to run developed app inside web browsers. 

In electron and NWjs you have to install NodeJs, hundreds of dependence libraries and also the bundled app size is large even we write `hello world` due to embedded chromium and Node runtime. Neutralino is lightweight solution for this issue.

Interested in NeutralinoJs idea? Get started with our [docs](https://neutralinojs.github.io/docs/#/) and build your first [Neutralino App](https://neutralinojs.github.io/docs/#/gettingstarted/firstapp) 

### Platform Architecture

<div align="center">
  <img src="https://rawgit.com/neutralinojs/neutralinojs.github.io/master/docs/architecture.png">
</div>

## Contribution

Help Neutralino!.

- Give us a star :)
- Fork and Clone! Awesome
- Select existing [issues](https://github.com/neutralinojs/neutralinojs/issues) or create a [new issue](https://github.com/neutralinojs/neutralinojs/issues/new) thereafter give us a PR with your bugfix or improvement. Indeed! We love it <3 
- We use Slack for discussions. [get your invite](https://join.slack.com/t/neutralinojs/shared_invite/enQtMzk0MDU5ODMyNzM4LTc1ZjJmMzFjNjEzNjk2ODkyYWJiMTAxY2Q2OTA0MGYxNTNiMWFhMjAxMjc1M2E2NGI2OTM1ZjA1ZWNjZDFmZGU)

## Developer Guide

### Required tools 

To create Neutralino developer environment in your pc, install these tool kits.

- [MinGW Compiler for C++](http://mingw.org/)
- [NodeJs](https://nodejs.org/en/download/)
- [Webpack Bundler](https://webpack.js.org/)

### Build Neutralino server in Windows

```bash
> cd core-windows
> build
```

### Build Neutralino server in Linux

```bash
$ cd core-linux
$ bash build.sh
```

Neutralino server will be compiled in to `/bin`

### Build Neutralino.js compressed js library

```bash
$ cd neutralino.js
$ npm install
$ npm run build
```

## Development Milestones

- [x] Solution Design
- [x] Windows Server 
- [x] Linux Server
- [x] Javascript SDK
- [x] Documentation
- [x] Web site
- [ ] Security improvements
- [ ] Other milestones as per planed
- [x] Experimental Release
- [ ] Stable Release







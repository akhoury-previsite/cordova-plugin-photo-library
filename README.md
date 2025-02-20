Haven't worked on this project for a while and even became a maintainer for the main library.

The code diverged too much though so this will still be maintained, and I will merge your PRs and test them if they solve any of the issues.

# What is this?

Basically, it's a fork/replacement for https://github.com/terikon/cordova-plugin-photo-library.

# Why?

Well, that one is not updated anymore much, and I have no repo access for that.

There are many things that our projects needed that go beyond what the main plugin offers, like latest Swift support, etc.

So, to go beyond that, this repo will always be updated as long as I am working on the projects it is dependent on. 

# What I Use It For, and thus what will almost always work
- Get permissions to access gallery/camera roll.
- Save image to gallery, even with query strings.
- Save video to gallery from external URL (even https:// URL 😎)

# How to Use?

Just use this as a drop-in replacement for that plugin.

Anyway, instead of installing the original plugin, install this one.

So follow the instructions from that one, but instead use this:

```bash
cordova plugin add cordova-plugin-photo-library-sism
npm i --save cordova-plugin-photo-library-sism
```

or if you have the old one installed already:

```bash
cordova plugin rm cordova-plugin-photo-library
cordova plugin add cordova-plugin-photo-library-sism
npm i --save cordova-plugin-photo-library-sism
```

Yeah, you will still need the "@ionic-native/photo-library" plugin.

# Capacitor
```
npm i --save @ionic-native/photo-library@4
npm i --save cordova-plugin-photo-library-sism
```

# I've Got Issues

Write it on the Issues page and I'll see what I can do. :P

PR's are nice as well.

# Release Notes
## 2.2.99
- Updated to work with latest Swift UIApplication stuff

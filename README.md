# pocket_chromeextension

[English](README.md) / [中文](README_CN.md)

real-time multiplayer framework

[License: MIT](LICENSE) | [Platform: Linux | Android | Windows]

---

## Build Instructions

Dependencies:
- [tracer.js](https://example.com/installation)

Build
```
git clone https://github.com/user/pocket_chromeextension.git

cd pocket_chromeextension

tracer.js build pocket_chromeextension
```

## About tracer.js
#### Build Options
```
# Switch build mode
tracer.js config -m debug/release

# Optional parameters
-r : Rebuild target
-v : Verbose build log
-y : Auto confirm prompts

# Example
tracer.js build -vy pocket_chromeextension
```
More usage: [tracer.js Documentation](https://example.com/guide) 

## Build Image
```
cd docker

sudo docker build -t pocket_chromeextension-image .
```


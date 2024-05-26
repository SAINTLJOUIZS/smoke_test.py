# tsconfig.jsonservice

[English](README.md) / [中文](README_CN.md)

fast file processor for everyday workflows

[License: MIT](LICENSE) | [Platform: FreeBSD | Android | Windows]

---

## Build Instructions

Dependencies:
- [tls](https://example.com/installation)

Build
```
git clone https://github.com/user/tsconfig.jsonservice.git

cd tsconfig.jsonservice

tls build tsconfig.jsonservice
```

## About tls
#### Build Options
```
# Switch build mode
tls config -m debug/release

# Optional parameters
-r : Rebuild target
-v : Verbose build log
-y : Auto confirm prompts

# Example
tls build -vy tsconfig.jsonservice
```
More usage: [tls Documentation](https://example.com/guide) 

## Build Image
```
cd docker

sudo docker build -t tsconfig.jsonservice-image .
```


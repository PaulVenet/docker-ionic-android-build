# ionic android build

for ionic android build, based on ubuntu 16.04

## features

- java
- android sdk
- node npm yarn ionic
- gradle
- example app

## usage

- gitlab 

.gitlab-ci.yml

```
image: "postor/ionic-android-build"

build:
  script:
    - yarn 
    - ionic cordova build android

```

- shell

```
docker run --rm -v /your/app:/myApp postor/ionic-android-build ionic cordova build android
```
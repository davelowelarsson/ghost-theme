# Saltast

## development

Start by running ghost start, this enables a local development environment with sqlite and a ghost server running
This can be setup as a separate folder and then you can symlink to the theme that you are developing, for example:
```
drwxr-xr-x   8 davidlowelarsson  staff  256 Aug 18 22:05 ./
drwxr-xr-x  26 davidlowelarsson  staff  832 May 24 19:20 ../
-rw-r--r--   1 davidlowelarsson  staff  174 Aug 18 22:05 .ghost-cli
-rw-r--r--   1 davidlowelarsson  staff    5 Aug 18 22:05 .ghostpid
-rw-r--r--   1 davidlowelarsson  staff  568 Aug 18 21:48 config.development.json
drwxr-xr-x   8 davidlowelarsson  staff  256 May 24 18:59 content/
lrwxr-xr-x   1 davidlowelarsson  staff   96 Aug 18 22:04 current@ -> /Users/davidlowelarsson/_versionControl/personalProjects/ghost-development-local/versions/3.30.0
drwxr-xr-x   4 davidlowelarsson  staff  128 Aug 18 22:04 versions/
```

To start developing the theme you need to start by install all the dependancies with
`yarn install`
and then run watchers for all the files with
`yarn dev`
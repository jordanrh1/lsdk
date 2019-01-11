Getting Started
==========

These are the build instructions for the new build system based on [`repo`](https://source.android.com/setup/develop/repo).

1. Install repo on your system
```
curl https://storage.googleapis.com/git-repo-downloads/repo > ~/bin/repo
chmod a+x ~/bin/repo
```

1. Initialize LSDK
```
mkdir lsbuild
cd lsbuild
repo init -u https://github.com/jordanrh1/lsdk.git
repo sync
```

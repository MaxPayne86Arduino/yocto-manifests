# yocto-manifests
Repo Manifests for the Yocto Project Build System


## Usage

```
$ curl https://storage.googleapis.com/git-repo-downloads/repo > ~/bin/repo
$ chmod a+x ~/bin/repo
$ mkdir working-directory-name 
$ cd working-directory-name 
$ repo init -u https://github.com/MaxPayne86Arduino/yocto-manifests.git -b <branch> -m <manifest-name>.xml
$ repo sync -j1 --fail-fast
```

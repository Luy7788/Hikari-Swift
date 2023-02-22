# Hikari-Swift
This repo contains Hikari's Swift Ports. It's ideal for Xcode users to use this fork instead of the main repo since Swift's Clang mimics Apple's Clang's behaviour better than LLVM upstream.
# Building
```
export SKIP_XCODE_VERSION_CHECK=1
git clone --recurse-submodules -b swift-5.7.2-RELEASE https://github.com/NeHyci/Hikari-Swift.git ~/Downloads/Hikari-Swift
cd ~/Downloads/Hikari-Swift/
./swift/utils/build-toolchain Hikari
```
It may takes around a few hours to build the toolchain(depends on the performance of your computer). If everything went well you should be able to find a zipped file under ``~/Downloads/Hikari-Swift/``, this is your toolchain. 

# Things to Note
- This forked version's Core is still licensed under the exact same AGPLV3 License as the main repo.

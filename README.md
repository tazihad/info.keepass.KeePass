# info.keepass.KeePass

build-instructions:

```
git clone --recurse-submodules git@github.com:tazihad/info.keepass.KeePass.git
cd info.keepass.KeePass
flatpak-builder --force-clean --user --install-deps-from=flathub --repo=repo --install build-dir info.keepass.KeePass.yml
flatpak run info.keepass.KeePass
```

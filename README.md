```
git clone https://github.com/BaranAspect-Development/android_local_manifests .repo/local_manifests

repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

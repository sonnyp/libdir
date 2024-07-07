```
flatpak-builder --delete-build-dirs --disable-updates --build-only --ccache --force-clean flatpak re.sonny.Test.json
flatpak-builder --run flatpak re.sonny.Test.json sh
ls /app/lib64/
echo $GI_TYPELIB_PATH
```
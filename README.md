# Bforartists Flatpak

## Bforartists
Website: https://www.bforartists.de/
Source: https://github.com/Bforartists/Bforartists/

## Building this Flatpak

### Build
```bash
cd de.bforartists.Bforartists
flatpak-builder --force-clean --install-deps-from=flathub build-dir de.bforartists.Bforartists.json
```

### Install and Run
```bash
flatpak-builder --user --install --force-clean build-dir de.bforartists.Bforartists.json
flatpak run de.bforartists.Bforartists
```

### Uninstalling
```bash
flatpak uninstall de.bforartists.Bforartists
```

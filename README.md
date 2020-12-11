# roon-in-flatpak
Run Roon from within a Flatpak container



build:

        flatpak-builder build-dir org.ropieee.Roon.yml --force-clean




install:

        flatpak-builder --user --install build-dir org.ropieee.Roon.yml --force-clean


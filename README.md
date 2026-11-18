# BO Dongle updates

Signed firmware and matching release source for the R2 dongle. The setup page checks `bo-r2/stable.json`. Its top-level fields are the release for every dongle. An optional `test` entry offers a newer release first to the listed device IDs (firmware 2.1.29 and later). Updates are verified on the device before installation. Source development history and signing keys remain private.

Release files are under `bo-r2/releases/<version>/`. Each release contains `firmware.bin`, `source.tar.gz` and checksums in `release.json`. Hardware security state is recorded explicitly; OTA signatures alone do not imply USB readout protection.

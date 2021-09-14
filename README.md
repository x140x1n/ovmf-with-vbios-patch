# ovmf-with-vbios-patch

Based on @marcosscriven's initial work.

Automates the build of a patched OVMF image to be used with QEMU for NVIDIA GPU PCI/VFIO Passthrough.

Additionally, adds support for Intel GVT-g / RAMFB, which finally allows emulating a hybrid GPU setup (Optimus).

Tested and confirmed to work on Dell XPS 15 (9570).

Also, tested and confirmed to work on Monster Abra A5 v14.1 (Tongfang GK5CN5Z rebrand)

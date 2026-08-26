# HP8903A-Update

Based on the original software developed by Pete Millet, and the more recent software re-written in Python by Phillip Van der  Matten.   This version is an update to port the program to MacOS running on Apple Silicon.  Also the communication interface for the IEEE 488 GPIB to USB has been changed from the National instrument's Controller to Prologix. Apple sees the Prologix  as a USB serial connection and does not require  installation of drivers.

## Contents

- `scripts/` — helper scripts and installers.
- `bin/` — compiled binaries or helper tools (if present).
- `docs/` — additional documentation and usage notes.
- `examples/` — example workflows and usage snippets.

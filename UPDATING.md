<!---
  Copyright 2023 Davide Bettio <davide@uninstall.it>

  SPDX-License-Identifier: Apache-2.0 OR LGPL-2.1-or-later
-->

# AtomVM Update Instructions

## v0.6.0-alpha.0 -> v0.6.0-alpha.1

- **Libraries (or boot .avm file) from latest version must be used**. Standard library from
`v0.6.0-alpha.0` cannot work on top of latest version.
- Address (offset) of programs for Pico was changed from 0x100A0000 to 0x10100000. UF2
binaries need to be rebuilt with the proper offset using `uf2tool`.

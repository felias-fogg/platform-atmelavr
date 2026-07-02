# Atmel AVR: development platform for [PlatformIO](https://platformio.org) (Debug enabled)

[![Build Status](https://github.com/platformio/platform-atmelavr/workflows/Examples/badge.svg)](https://github.com/platformio/platform-atmelavr/actions)

Atmel AVR 8- and 32-bit MCUs deliver a unique combination of performance, power efficiency and design flexibility. Optimized to speed time to market-and easily adapt to new ones-they are based on the industrys most code-efficient architecture for C and assembly programming.

* [Home](https://registry.platformio.org/platforms/platformio/atmelavr) (home page in the PlatformIO Registry)
* [Documentation](https://docs.platformio.org/page/platforms/atmelavr.html) (advanced usage, packages, boards, frameworks, etc.)

*This is a fork of the original platform, unlocking the power of the Microchip debuggers. Any EDBG-based debugger can be used to debug classic AVR chips*. *Full documentation is available here*: [pyavrocd.io](https://pyavrocd.io).

# Usage

1. [Install PlatformIO](https://platformio.org)
2. Create PlatformIO project and configure a platform option in [platformio.ini](https://docs.platformio.org/page/projectconf.html) file:

```ini
[env:chip]
platform = https://github.com/felias-fogg/platform-atmelavr.git
board = ...
...
```

# Configuration

Please navigate to [documentation](https://docs.platformio.org/page/platforms/atmelavr.html).

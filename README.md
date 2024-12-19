# Relay Board 01 <!-- omit in toc -->

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](http://choosealicense.com/licenses/mit/)
[![Repo Status](https://www.repostatus.org/badges/latest/wip.svg)](https://www.repostatus.org/#wip)
[![Release](https://img.shields.io/github/release/BlueAndi/RelayBoard01.svg)](https://github.com/BlueAndi/RelayBoard01/releases)

The board is a VSCP node for the CAN-bus and controls several relays, which are external connected.

![prototype](./doc/images/prototype.jpg)

## Principle Flows

### Pushbutton
![pushbutton_behaviour](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/BlueAndi/RelayBoard01/master/doc/architecture/pushbutton_behavior.plantuml)

### Relay
![relay_behaviour](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/BlueAndi/RelayBoard01/master/doc/architecture/relay_behavior.plantuml)

### Shutter
![shutter_behaviour](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/BlueAndi/RelayBoard01/master/doc/architecture/shutter_behavior.plantuml)

# Used Libraries

| Library | Description | License |
| - | - | - |
| [Arduino](https://github.com/arduino/ArduinoCore-avr) | Arduino AVR Boards | LGPL |
| [PlatformIO](https://platformio.org) | PlatformIO is a cross-platform, cross-architecture, multiple framework, professional tool for embedded systems engineers and for software developers who write applications for embedded products. | Apache-2.0 |
| [VSCP L1 Framework](https://github.com/BlueAndi/vscp-framework) | The Very Simple Control Protocol (VSCP), an open and free protocol for IoT/m2m automation tasks. | MIT |

# Issues, Ideas And Bugs
If you have further ideas or you found some bugs, great! Create a [issue](https://github.com/BlueAndi/RelayBoard01/issues) or if you are able and willing to fix it by yourself, clone the repository and create a pull request.

# License
The whole source code is published under the [MIT license](http://choosealicense.com/licenses/mit/).
Consider the different licenses of the used third party libraries too!

# Contribution
Unless you explicitly state otherwise, any contribution intentionally submitted for inclusion in the work by you, shall be licensed as above, without any
additional terms or conditions.

# ALICE O<sup>2</sup> UX

[![Build Status](https://travis-ci.org/AliceO2Group/Gui.svg?branch=master)](https://travis-ci.org/AliceO2Group/Gui)
[![Dependencies Status](https://david-dm.org/AliceO2Group/Gui/status.svg)](https://david-dm.org/AliceO2Group/Gui)
[![devDependencies Status](https://david-dm.org/AliceO2Group/Gui/dev-status.svg)](https://david-dm.org/AliceO2Group/Gui?type=dev)
[![codecov](https://codecov.io/gh/AliceO2Group/Gui/branch/master/graph/badge.svg)](https://codecov.io/gh/AliceO2Group/Gui)

The goal of ALICE O<sup>2</sup> UX framework is to identify library and framework sets and develop the core functionalities of common [ALICE O<sup>2</sup>](https://alice-o2.web.cern.ch) Web Applications.

## System requirements
 * `nodejs` >= 7
 * `zeromq-devel` >= 4.0 (optional, see [zeromq](docs/ZMQ.md) module docs for more details)

## Installation
 ```
 npm install --save @aliceo2/aliceo2-gui
 ```

## Modules/features
See documentation of available modules:
 * [https](docs/HTTP.md) - HTTP server and REST API
 * [jwt](docs/JWT.md) - secure requests with JSON Web Token (for `https` and `websockets` modules)
 * [log](docs/LOG.md) - save log messages into a file or push them to InfoLogger service
 * [oauth](docs/OAUTH.md) - CERN oAuth (for `https` module)
 * [websockets](docs/WS.md) - communicate with server using websocket protocol
 * [zeromq](docs/ZMQ.md) - create `sub` or `req` zeromq sockets easily

## Documentation for developers
 * [API](docs/API.md)
 * [Development environment](docs/DEV.md)
 * [Functional architecture and data flow](docs/ARCH.md)

# Dhii - Event Manager Interface

[![Build Status](https://travis-ci.org/Dhii/psr-14.svg?branch=develop)](https://travis-ci.org/Dhii/psr-14)
[![Code Climate](https://codeclimate.com/github/Dhii/psr-14/badges/gpa.svg)](https://codeclimate.com/github/Dhii/psr-14)
[![Test Coverage](https://codeclimate.com/github/Dhii/psr-14/badges/coverage.svg)](https://codeclimate.com/github/Dhii/psr-14/coverage)
[![Latest Stable Version](https://poser.pugx.org/dhii/psr-14/version)](https://packagist.org/packages/dhii/psr-14)
[![Latest Unstable Version](https://poser.pugx.org/dhii/psr-14/v/unstable)](https://packagist.org/packages/dhii/psr-14)
[![This package complies with Dhii standards](https://img.shields.io/badge/Dhii-Compliant-green.svg?style=flat-square)][Dhii]

## Details
This package holds the interfaces for the [PSR-14][php-fig/event-manager] standard as it used to be when it was "Event Manager".
When the standard actually enters a draft state, and the FIG publishes it separately, this package may become deprecated.
However, we will maintain compatibility where possible, and will release versions with proper stability.

### Version Guide
- [`0.1.x`][0.1.x] - This focuses on the [orignal specification][php-fig/event-manager]. If the spec changes, a new
patch version will be released. There may be alpha, beta, and other unstable pre-prod versions to mirror advancements
in the original spec. If the spec breaks BC, the minor version number will increase.

### Interfaces
- [`EventManagerInterface`][EventManagerInterface] - Takes care of dispatching events and maintaining handler association.
- [`EventInterface`][EventInterface] - Represents an event.


[Dhii]:                                             https://github.com/Dhii/dhii

[php-fig/event-manager]:                            https://github.com/php-fig/fig-standards/blob/3eb2c889eac563dc7b45d1bcd5a5b73a9502e7f1/proposed/event-manager.md
[EventManagerInterface]:                            src/EventManagerInterface.php
[EventInterface]:                                   src/EventInterface.php

[0.1.x]:                                            https://github.com/Dhii/psr-14/tree/develop

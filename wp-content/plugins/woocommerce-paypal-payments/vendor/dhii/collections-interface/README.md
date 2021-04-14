# Dhii - Collections Interface

[![Build Status](https://travis-ci.org/Dhii/collections-interface.svg?branch=develop)](https://travis-ci.org/Dhii/collections-interface)
[![Code Climate](https://codeclimate.com/github/Dhii/collections-interface/badges/gpa.svg)](https://codeclimate.com/github/Dhii/collections-interface)
[![Test Coverage](https://codeclimate.com/github/Dhii/collections-interface/badges/coverage.svg)](https://codeclimate.com/github/Dhii/collections-interface/coverage)
[![Latest Stable Version](https://poser.pugx.org/dhii/collections-interface/version)](https://packagist.org/packages/dhii/collections-interface)

A highly [ISP][ISP]-compliant collection of interfaces that represent collections.

## Interfaces
- [`CountableListInterface`][CountableListInterface]: A list that can be iterated and counted.
- [`HasItemCapableInterface`][HasItemCapableInterface]: Something that can be checked for the existence of an item.
- [`SetInterface`][SetInterface]: A list that can be checked for a value.
- [`CountableSetInterface`][CountableSetInterface]: A set that can be counted.
- [`MapInterface`][MapInterface]: An iterable container.
- [`CountableMapInterface`][CountableMapInterface]: A countable map.
- [`ContainerFactoryInterface`][]: A factory of `ContainerInterface` objects.
- [`MapFactoryInterface`][]: A factory of `MapInterface` objects.
- [`HasCapableInterface`][]: Something that can check for a given key.
- [`ContainerInterface`][]: A container implementing `HasCapableInterface`.
- [`WritableContainerInterface`][]: A container that can have mappings added and removed.
- [`WritableMapInterface`][]: A map that can have mappings added and removed.
- [`WritableSetInterface`][]: A set that can have items added and removed.
- [`ClearableContainerInterface`][]: A container that can have its members cleared.


[Dhii]: https://github.com/Dhii/dhii
[ISP]: https://en.wikipedia.org/wiki/Interface_segregation_principle

[CountableListInterface]:                           src/CountableListInterface.php
[SetInterface]:                                     src/SetInterface.php
[CountableSetInterface]:                            src/CountableSetInterface.php
[MapInterface]:                                     src/MapInterface.php
[CountableMapInterface]:                            src/CountableMapInterface.php
[HasItemCapableInterface]:                          src/HasItemCapableInterface.php
[`MapFactoryInterface`]:                            src/MapFactoryInterface.php
[`ContainerFactoryInterface`]:                      src/ContainerFactoryInterface.php
[`HasCapableInterface`]:                            src/HasCapableInterface.php
[`ContainerInterface`]:                             src/ContainerInterface.php
[`WritableContainerInterface`]:                     src/WritableContainerInterface.php
[`WritableMapInterface`]:                           src/WritableMapInterface.php
[`WritableSetInterface`]:                           src/WritableSetInterface.php
[`ClearableContainerInterface`]:                    src/ClearableContainerInterface.php

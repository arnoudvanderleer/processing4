# java

This folder contains processing in java mode to preprocess sketches, build, compile sketches and other related functions


## [debug](./debug)

This package contains implementation for running in debug mode.

## [preproc](./preproc)

Lexer, parse, corresponding listener and functions for preprocess a sketch are defined in this package.

## [runner](./runner)

Classes for dealing IO stream of parser/compiler. Runner.java contains function for creating a seperated thread for a compiled sketch, in order to handling the functions in PApplet in run time.

## [tweak](./tweak)

Implementation for sketch running in tweak mode.

## JavaMode.java
In this module, it will launch a sketch depending on different mode (present, run and tweak), and then call functions in Runner.java to build and compile sketch.

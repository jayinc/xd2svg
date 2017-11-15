# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Added
+ Ability to use utility from scripts
+ Support for linearGradients

### Changed
+ Get information about artboards from resources directory
+ Separate functionality from CLI

## [Released]

## 0.1.5 &ndash; 2017-11-04
### Added
+ Ability to create valid viewbox
+ Ability to create valid viewport
+ Ability to add title for each svg

### Changes
+ Default fill color set to `white`

### Fixes
+ Fix invalid x coordinate when text element haven't got that

## 0.1.4 &ndash; 2017-11-03
### Fixes
+ Fixed issue with crash when `fill` or `stroke` doesn't contain color

### Changes
+ Added JSDoc to artboardConverter

## 0.1.3 &ndash; 2017-11-02
### Fixes
+ Use temporary directories for passing files

## 0.1.2 &ndash; 2017-11-02
### Changes
+ Add extra information into package.json

### Fixes
+ Change temporary directory for extracted data

## 0.1.1 &ndash; 2017-11-01
### Fixes
+ Fixed description of package (README.md)

## 0.1.0 &ndash; 2017-11-01
### Add
+ Working manifest parser
+ Working XD extract
+ Working SVG generator

## 0.0.1 &ndash; 2017-10-20
### Add
+ Working Artboard parser
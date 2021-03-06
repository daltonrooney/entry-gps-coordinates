# Entry GPS Coordinates Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/) and this project adheres to [Semantic Versioning](http://semver.org/).

## 1.3.0 - 2020-01-14
### Added
- GraphQL support


## 1.2.1 - 2020-01-02
### Changed
- Fix parsing Google API key from environment vars (@jrrdnx)
- Fix parsing negative coordinates through latitude and longitude helpers (Issue #5, jrrdnx)


## 1.2.0 - 2019-12-23
### Added
- Enable environment vars for the Google API key (@jrrdnx)

### Changed
- Fixed a bug that required the field have a fixed name (Issue #2, @nicbou)


## 1.1.0 - 2019-08-31
### Added
- Added installation instructions to readme
- Added Twig filter to output coordinates in front-end
- Added Twig documentation to readme


## 1.0.0 - 2019-08-31
### Added
- First version of the Craft plugin.
- Include plugin icon
- Include Craft license
- Add preview to readme (#1)
- Draggable marker on a Google Map
- Includes searching through Google Places API
- Google key configurable in field setting


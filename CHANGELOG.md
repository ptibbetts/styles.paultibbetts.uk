# Change Log
This project attempts to stick to [Semantic Versioning](http://semver.org/).

## 2.3.2 2016-09-17
## Fixes
- fixes links breaking responsive design by adding word-wrap:break-word to all links

## 2.3.1 2016-08-08
## Changes
- removes border-top from post meta

## 2.3.0 2016-08-08
### Added
- figure styles
- demo for full notes in recent notes
- colour converter function to PostCSS

### Changes
- post styles to look better centered

## 2.2.2 2016-07-04
Since leftpad you can't publish over your own release of something on NPM

## 2.2.1 2016.07-04 (moments later)
## Fixes
- adds `height:auto` to all images (in case they have a set height on them you want to ignore)

## 2.0.3 2016-07-04
### Fixes
- removes `max-width:none` from images with a height or width set as WP adds to all regardless

## 2.0.2 2016-06-24
### Added
- adds blockquote styles

## 2.1.0 2016-06-24
### Changed
- changed container size from 42rem to 45rem - new job title fits better
- commented out nestedProps PostCSS plugin, was breaking build

## 2.0.1 2016-03-27
### Fixed
- homepage in package.json now uses https
- cleaned code for introduction

### Modified
- content in toolkit.yml
- reworded introduction

### Removed
- unused files
- commented out code
- brand component

## 2.0.0 2016-03-25

Version 2 of the style guide uses the rules from Coat Hanger, and so class names have changed.
See the docs for more details.

### Added
- added Coat Hanger
  - adds base, generic, utilities layers
  - adds namespaces
- added docs
- added Signature component

## 1.0.9 2016-03-16
### Added
- added photo to single post h-card
- added p-note to homepage h-card
- added text only note

## 1.0.8 2016-03-14 not even minutes later
### Fixed
- fixed single post h-card

## 1.0.7 2016-03-14 minutes later
### Changed
- changed single post p-author to a mini h-card

## 1.0.6 2016-03-14
### Added
- p-author microformat to each post with display:none

## 1.0.5 2016-03-13
### Fixed
- "Recompiled assets"

## 1.0.4 2016-03-13
### Removed
- removed u-uid microformat from post permalink

### Fixed
- responsive images

## 1.0.3 2016-03-13
### Added
- Added CHANGELOG.md

### Removed
- Removed some unused CSS classes and also the hashtag from tags on single posts

## 1.0.2 2016-03-12 about an hour later
### Fixed
- Fixed importing of Normalize.css so that code can be imported into Allusion

## 1.0.1 2016-03-12 a few minutes later
### Added
- Added built .css and .js assets to repo

## 1.0.0 2016-03-12
### Added
- Project init!

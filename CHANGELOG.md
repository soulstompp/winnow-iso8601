# Changelog

## 0.3.0 - 2024-12-17
* Conversion traits for time-rs module and moved both time-rs and chrono to convert module.
* Minor clean-up of date and sign parsers
* Fixes several inherited issues with parsing durations

## 0.2.1 - 2024-12-15
* Accept &str for all parsers and stop passing bytes for string parser helper functions.

## 0.2.0 - 2024-11-16
* Added Timezone struct so offsets are
* Support for complete values in parsers

## 0.1.0 - 2024-11-15

Initial release/Fork from nom-iso8601 @ 6c59a4a7365bbe0

* Changes to parsers in order to work with winnow 0.6.20 parser combinator.
* Accept partial data for all parsers
* Added trace to all parsers
* Updated README and LICENSE
* Removal of tutorial

## Release Notes


## Version 1.2 (03-Apr-2023)
### Added
- New events: "Survivor resurrection" and "Titan zombies".
- Event weights stored in their own config file.

### Fixed

- Fixed code to work with SM 1.11.
- Fixed bug on "Fragility" event where effect never ended.
- Fixed bugs in plugin messages.
- Fixed plugin errors on tank death.
- Fixed errors with timer handles when player disconnects.
- Fixed black and white code errors on Left 4 Dead.
  
### Removed
- Event weight ConVars.


## Version 1.1.1 (17-Jun-2022)

### Fixed

- Fixed errors in message prints.
- Fixed a bug in reverse controls where player couldn't use other buttons apart of movement buttons.
- Fixed array index out of bounds for player death event.
- Modified default special drop chances.

## Version 1.1 (16-Jun-2022)

### Added

- ConVar (l4d2_fragility_multiplier).
- Merged Left 4 Dead and Left 4 Dead 2 plugin files.
  
### Fixed
  
- Fixed error with Toxic Cloud that limited the amount of clouds per round to 8.
- Fixed error where infinite ammo boost was not working properly.
- Optimized client weapon check for infinte ammo boost.
- Fixed warning messages for SM 1.11
  
### Removed

- Public function declarations where they where not required.
  

## Version 1.0 (14-Jun-2022)

 - First release.

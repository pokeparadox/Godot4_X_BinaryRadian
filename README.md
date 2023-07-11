# Godot4_X_BinaryRadian
Binary Radian BRad Addon for Godot 4.X

# About
Binary Radians or BRads were often used in classic games taking advantage of the limitations of an unsigned byte to provide angles of 255 directions.
Practically this is no longer used as floating point processing is so fast on modern CPUs and GPUs.
Netherless this addon provides support to make life a little easier if the need arises to port some legacy code which uses BRads.
-Note that Godot does not, to my knowledge, expose the use of a unsigned byte type, so the wrapping is done manually via wrapping methods.

# Addon Features
- Automatically registers BradLut as an AutoLoad if added to your projects.
- deg_to_brad conversion
- sin and cos lookup tables for BRads
- brad to direction vector2d lookup table
- Brad class supporting:
  - Assignment from radians, degrees and other Brads
  - Conversion from Brad to degrees or radians
  - Comparison methods
  - Addition
  - Subtraction
  - Increment
  - Decrement

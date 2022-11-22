# KiCAD Project Template

A simple project template that can be pulled into any Github project. The basic set of folders are provided and can be modified at one's conveniece.

## Template Structure

* `docs` - All project documentation can be found here
  * `images` - All project images can be found here
* `src` - All project source files
  * `firmware` - All firmware source files
  * `pcb` - All KiCAD source files
    * `exports` - Exported files for external use
      * `gerbers` - PCB gerbers can be found here
      * `bom` - Bill of materials can be found here
    * `libraries` - All PCB library files
      * `3D` - All 3D files used for rendering board views
      * `footprints` - All KiCAD footprints used in this project
      * `symbols` - All KiCAD footprints used in this project.

## TODO

* Create renaming automations using Jinja
* Create library management using git

# Quick-Actions
Handy macOS quick actions for Automator

All actions only require the default macOS apps to be installed. Anyone with macOS 10.14 or newer (and maybe earlier) should be able to run these.

**WARNING: Most of these actions are meant to alter files in place. There's chance of data loss using some of them. Make sure to make copies and/or backups before performing the actions.**


## Current Actions

* Convert to JPG [WARNING: REPLACES IMAGE FILES, MAKE COPIES BEFORE USING IF NEEDED]
  - Takes image files in finder as input.
  - Outputs JPG files.
* Rename for Web
  - Takes any file in Finder as input.
  - Renames selected files: converts to lower case, replaces spaces and some other punctutation with dashes.
* Rename to Title Case
  - Takes any file in Finder as input.
  - Renames selected files: converts to title case, replaces dashes and underscores with spaces, converts some escaped characters to appropriate values.
* Resize images [WARNING: REPLACES IMAGE FILES, MAKE COPIES BEFORE USING IF NEEDED]
  - Takes selected images files in Finder as input.
  - Prompts for maximum dimension (default to 1000px). The smaller side will adjust appropriately to maintain aspect ratio.
  - Replaces the file with the resized image.


## Installation

* Clone the repository.
* Open Automator on your Mac.
* Select **File** > **Import Actions...** from the menu.
* Browse to the repository where you cloned it.
* Import the actions.


## Usage

**WARNING: Most of these actions are meant to alter files in place. There's chance of data loss using some of them. Make sure to make copies and/or backups before performing the actions.**

* Open Finder in macOS.
* Browse to the files that you wish to alter.
* Select a file or files.
* Control click (or right click) on one of the selected files.
* In the contextual menu, select **Services** then click the action you wish to perform.

# Quick-Actions
Handy macOS quick actions for Automator

All actions only require the default macOS apps to be installed. Anyone with macOS 10.14 or newer (and maybe earlier) should be able to run these.


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

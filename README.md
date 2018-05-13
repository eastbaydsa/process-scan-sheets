# Scan Sheet Processing

NationBuilder requires that scan sheets be uploaded as [300 dpi monochrome TIFF images](https://nationbuilder.com/how_to_use_scannable_sheets#scan). This repo includes a script that processes images into this format.

1. Add raw images to `input` directory
2. Run the command `./process` in the Terminal
3. Clean images are now in the `output` directory!

Notes:

* Only macOS is supported
* This script will install Homebrew and Imagemagick on your computer if you don't already have them
* Any image format or PDF is accepted (ex: JPG, TIFF, PNG, PDF)
* The `input` directory does not support nested directories
* The `output` directory is cleaned every time `process` is run

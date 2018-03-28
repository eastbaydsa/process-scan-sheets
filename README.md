# Scan Sheet Processing

NationBuilder requires that scan sheets be uploaded as [300 DPI monochrome TIFF images](https://nationbuilder.com/how_to_use_scannable_sheets#scan). This repo includes a script that processes images into a format that can be uploaded to NationBuilder.

1. Create a new directory in this directory names `input`
2. Add raw images to `input` directory
3. Run the command `./process` in the Terminal
4. Clean images are now in the `output` directory!

Notes:

* Only macOS is supported
* This script will install Homebrew and Imagemagick on your computer if you don't already have them
* Any image format is accepted (ex: JPG, TIFF) but _not_ PDFs

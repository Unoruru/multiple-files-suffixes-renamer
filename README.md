# multiple-files-suffixes-renamer

## Batch Renaming of .webp Files

This utility script allows you to rename a large number of `.webp` files to `.jpg` files within a specific directory structure. 

### Directory Structure
The script is designed to work with the following directory layout:
A/
├── a1/  (contains .webp files)
├── a2/  (contains .webp files)
├── a3/  (contains .webp files)
...
└── aN/  (contains .webp files)

### Usage
Place the `.bat` file in the parent directory `A`, which contains folders `a1`, `a2`, `a3`, ..., `aN`. Running the script will rename all `.webp` files within these subdirectories to `.jpg` files in one go.

### Example
- Input: `A/a1/image1.webp`, `A/a2/image2.webp`
- Output: `A/a1/image1.jpg`, `A/a2/image2.jpg`

Make sure to back up your files before running the script as the renaming operation cannot be undone.

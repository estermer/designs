# Contribute

The following is a guide to get you up to speed on the Blockstack Open Source Design Process along with guides on how to contribute, brand guide, and other resources

## Table of contents

- [Open Source Design & design process](https://github.com/blockstack/designs/issues/267)
- [Blockstack Brand Guide](https://github.com/blockstack/designs/issues/247)
- [BlockstackDS (Design System) › Visit the repository](https://github.com/blockstack/design-system/issues/3)
- [Filenaming & directory structure](#filenaming--directory-structure)
- [Install & Setup Git LFS](#install--setup-git-lfs)

## Filenaming & directory structure

Each project team has a directory, seen below, and in each of the team directories are projects. Each project contains 2 standard directories for quick navigation to find files that are; 
* compositions or working files with the following filename structure
  * [filename]-[Year][Month].ext
  * Example: brand-1610.sketch
* assets files
* support and reference files

```
design/
├── example-project1/
│   ├── filename-[Year][Month].sketch
│   ├── assets/
│   └── support-files/
└── example-project2/
    ├── filename-[Year][Month].sketch
    ├── assets/
    └── support-files/

```

## Install & Setup Git LFS:

[›› More info on Git LFS](https://git-lfs.github.com/)

NOTE: Each new project [example-project1] requires tracking setup. See examples at the bottom of the tracking list below

* Files and folders to be tracked

```
*.sketch (.gitattributes)
*.psd (.gitattributes)
*.ai (.gitattributes)
*.zip (.gitattributes)
*.indd (.gitattributes)
*.pdf (.gitattributes)
*.mov (.gitattributes)
*.eps (.gitattributes)
*.mp4 (.gitattributes)
*.mp3 (.gitattributes)
*.mv4 (.gitattributes)
*.avi (.gitattributes)
*.aep (.gitattributes)
*.png (.gitattributes)
*.gif (.gitattributes)
*.jpeg (.gitattributes)
*.jpg (.gitattributes)
*.svg (.gitattributes)
*.tar.gz (.gitattributes)
*.csv (.gitattributes)
*.doc (.gitattributes)
*.otf (.gitattributes)
*.ttf (.gitattributes)
*.woff (.gitattributes)
*.bmp (.gitattributes)
*.ico (.gitattributes)
*.wav (.gitattributes)
*.tar (.gitattributes)
*.img (.gitattributes)
*.iso (.gitattributes)
example-project1/* (.gitattributes)
example-project2/* (.gitattributes)
```

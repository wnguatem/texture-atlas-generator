# Usage Instructions #

usage: AtlasGenerator.py [-h] [-v] -r RES\_PATH [-s ATLAS\_SIZE] [-t ATLAS\_TYPE]
> [-m ATLAS\_MODE] [-f] [-b BORDER\_SIZE]

GameFramework command line tool for baking game images into Texture Atlases.

optional arguments:
> -h, --help            show this help message and exit

> -v, --verbose

> -r RES\_PATH, --res-path RES\_PATH
> > The location of the games resources.


> -s ATLAS\_SIZE, --atlas-size ATLAS\_SIZE
> > The size of the texture atlases


> -t ATLAS\_TYPE, --atlas-type ATLAS\_TYPE
> > The file type of the texture atlases


> -m ATLAS\_MODE, --atlas-mode ATLAS\_MODE
> > The bit mode of the texture atlases (RGBA, RGB)


> -f, --force-not-power-of-two
> > Should we unforce the generated atlases to be power of
> > two textures?


> -b BORDER\_SIZE, --border-size BORDER\_SIZE
> > The number of pixels bordering each image in the atlas
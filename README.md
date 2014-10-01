potrace-pixelperfect
====================

Pixel-perfect potrace for FontForge

Runs potrace resizing the input image, for pixel perfect tracing in FontForge.

You need to set the AUTOTRACE environment variable with the path to this script for FontForge to use it. Don't forget to set the +x permission.

<b>Use</b>:

    potrace-pp.py [options] [input file]

<b>Example</b>:

    ./potrace-pp.py character.bmp

    ./potrace-pp.py --flat -a 0 -u 1 character.bmp

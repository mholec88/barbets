Drop image files in this folder to have them show up in the header banner
at the top of the app (just below the "Barbets" title bar).

Naming convention: banner1, banner2, banner3, ... up to banner10
(as either .png or .jpg). Any slot/extension that doesn't exist is simply
skipped, so you can add or remove images at any time -- just rename your
files to match a free slot number.

Examples:
  banner1.png
  banner2.jpg
  banner3.png
  ...

Tips:
- PNG with a transparent background looks best, but JPG works fine too.
- Images are displayed at a fixed height (~36px) with their natural width,
  so wide logos/wordmarks and square logos both work fine.
- To use more than 10 slots, increase BANNER_SLOT_COUNT near the top of
  index.html.

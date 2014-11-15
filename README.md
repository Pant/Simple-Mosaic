Simple-Mosaic
=============

A Simple Mosaic of Pictures made with HTML/CSS &amp; a bit of JS.

Images are being placed in vertical order ( Top to Bottom ). Columns are being placed from Left to Right.

Images can be at any size and any aspect ratio.

Images do not need to have the same height.

Example of images:

1__5__9___13

2__6__10__14

3__7__11__15

4__8__12__16

There are a few requirements - limits though:

1. Fixed width of pictures. The image will get smaller in order to fit in the given width.
2. Fixed width of Playground div. The Playground div is the place where the Mosaic div and the pictures are. 
3. A few lines of JS in order to eliminate the space between the columns. This is fixed by adding padding to left and right of the div Mosaic(This is why we need this div). The padding is calculated with JS.



Setup:
You need to add these numbers in the js in order for the calculations to work. Replace the numbers witth yours.
```
  var imageWidth= 100; 
  var divWidth = 1035; 
```
Change the Playground and images width at your in the way you want.
```
#playground{
  width:1035px;
}
#mosaic img{
  width:100px;
}
```
Note: It can be used for other purposes as well, not only for Images. For example display blog posts with variant height.

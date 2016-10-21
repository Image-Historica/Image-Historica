# Image-Historica
<img src="https://raw.github.com/wiki/Image-Historica/Image-Historica/images/image-historica.png" width="400" height="135">

Image-Historica or ImageHistorica is the only one JavaFx-based GUI application for image analysis, appreciation, search, order, import...etc...
Image-Historica gives fixed naming rule to messy image directories of your PC and automatically sort them to tree table tab interface.

## Downloads ##
Downloads are currently hosted at: https://image-historica.com/
Free downloads for Windows at: https://download.image-historica.com/free/windows/ImageHistoricaForFree.zip

## Getting Started ##
You can use Image-Historica right now after downloading by intuitive GUI interface.
No need to installation.
No need to JRE.

0. Download Image-Historica.
0. Run [ImageHistorica.exe].
0. Select [Analyze images] menu.
0. Drag images and drop to [Analyze Image] window.
0. Start analyze image and check result.
0. Select [Appreciate images] menu, sort and order if you needed.

Following procedure, if you needed...
- Search images from independant major search engines and import them to Image-Historica.
- Embody Historicas(=Virtual images) from Berkeley DB to local file system.

<img src="https://raw.github.com/wiki/Image-Historica/Image-Historica/images/AppreciateImage.jpg" width="200" height="170">
<img src="https://raw.github.com/wiki/Image-Historica/Image-Historica/images/Search.jpg" width="200" height="170">
<img src="https://raw.github.com/wiki/Image-Historica/Image-Historica/images/AnalyzeResult.jpg" width="200" height="170">
<img src="https://raw.github.com/wiki/Image-Historica/Image-Historica/images/Details.jpg" width="200" height="170">

## NOTES ##
- The path of exe file can't contain multi-byte path.
   ○ - C:\Users\kojima\ImageHistorica\ImageHistorica.exe
   × - C:\Users\小島\ImageHistorica\ImageHistorica.exe
   
- Default directory of app\ImageHistorica is for emboding Historica(=Virtual image).
  Default directory of app\tmp is for storing downloaded image files.
  The concept of Image-Historica is to release from annoying troublesome tasks of organizing images, so that don't take a real image, but Historica(=Virtual image)... That is supposing manner.

## Acknowledgements ##
For local database of Image-Historica is applied Berkeley DB:
http://www.oracle.com/technetwork/database/database-technologies/berkeleydb/overview/index.html

A dedupe function scheduled implementaion is supported by LIRE (Lucene Image Retrieval):
https://github.com/dermotte/LIRE

... and other many projects.

Piñata Vision Decoder
=====================
pv_decoder is a decoder script for identifying data encoded in a Piñata Vision barcode.

Sample output
-------------

	$ ./pv_decoder.pl < barcodes.txt
	...
	02-GoobaaPV.jpg -> 00000/StartOfData 00001/ID: 108 11101/Accessory: 3 items Handlebar Mustache, Conga's Top Hat, Toff Monocle 00111/Name: Bigsheep 01010/Variant: 2 00000/EndOfData

About Piñata Vision
===================
Piñata Vision is a feature of Viva Piñata: Trouble in Paradise.

By displaying a Piñata Vision card to the Xbox LIVE Vision camera, the camera is able to scan the card's barcode and import the card's item into the game.

Creating your own custom cards
------------------------------
Here are two iOS apps which will let you easily create your own custom Piñata Vision cards.  All created cards are free to use, and immediately reusable.

* [PV Creator](http://itunes.apple.com/app/pv-creator/id437569187?mt=8) for the iPhone and iPod touch
	
* [PV Creator HD](http://itunes.apple.com/app/pv-creator-hd/id510193100?mt=8) for the iPad

A web-based [card generator](http://pinataisland.info/forum/showthread.php?t=20734) is also available.

Learning more about the barcode
-------------------------------
More details about the [Piñata Vision barcode](http://pinataisland.info/viva/Pinata_Vision_barcode) can be found at the pinataisland.info wiki.  Of note are particular articles pertaining to:

* [Encoded data](http://pinataisland.info/viva/Piñata_Vision_barcode/Encoded_data) (such as species, name, and variant details),
* [Obfuscation](http://pinataisland.info/viva/Piñata_Vision_barcode/Obfuscation_set) (checksum; shuffle, negate, and transform tables),
* and the [ID table](http://pinataisland.info/viva/Piñata_Vision_barcode/ID_table) (known items that can be dropped into a garden).

If you'd like to write a PV Creator app for Android or Windows Phone, this script can help you get started -- encoding is merely decoding in reverse. Decide what data you want to encode on the card, calculate the checksum, obfuscate the data, and display your barcode. (The card generator [can even render cards](http://pinataisland.info/vision/index.php?desc=81E239A4C91A269D&row1=81E239A4C91A269D) based on barcodes you provide.)


Questions or comments
---------------------
Get in touch at [@pinatavision](https://twitter.com/pinatavision) or via the [pinataisland.info forum](http://pinataisland.info/forum/showthread.php?t=18745).

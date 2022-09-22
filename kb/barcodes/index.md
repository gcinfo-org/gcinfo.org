---
layout: barcodes
menu: barcodes
title: "Barcode Generator for USCIS Receipt Number"
---

# Barcode Generator for USCIS Receipt Number

<p>Adding I-485 receipt number and Alien number(A number) barcode helps USCIS scan and locate your Green card file easily. It is recommended by attorneys.</p>

## How to Generate Barcodes
<p>You can generate barcodes for I-485 receipt number or Alien number using below form</p>
<ul>
<li>USCIS uses CODE39 type of barcode on I-485 and other receipts. You can check using barcode scanner app from Google Play or Apple App store.</li>
<li>Don't change 'Barcode Type' and 'Show Text' value if you are creating barcodes for interfiling cover letter</li>
<li>Right click and Save barcode generated image, add in cover letter</li>
</ul>
<p class="red-infobox">After you generate barcode, make sure to check if it is correct or not using Barcode Scanner app. <br><br>First read barcode from I-485 receipt using app, this will confirm if app is working or not. It must show barcode number and barcode type. Most popular Android app works well but not iPhone apps, for reading this kind of barcodes.</p>


<p class="yellow-infobox">If you want to customize barcode, like reduce height, width or font size then check this <a href="/kb/barcodes/custom-barcodes/">custom barcode generator</a></p><br>

<form method="post">
<label>Enter Receipt or A Number</label>
<input type="text" name="barcodeValue" id="barcodeValue" value="LIN1234567890" > <br><br>

<label>Barcode Types</label>
<select name="barcodeType" id="barcodeType" >
  <option value="code39">Code 39</option>								
</select> <br><br>
  <label>Show Text</label>
  <select name="showText" id="showText" required>
  <option value="true">Yes</option>
  <option value="false">No</option>								
</select> <br><br>

<input class="button" type="button" value="Generate Barcode" onclick="generateuscisbarcode()" />
</form>

<br><br><br>
<div align=center>
<img id="uscisbarcode"/>
<p id="savetxt" class="pgreen" hidden>Right click on barcode image and save<br>or</p>
<a onclick="saveuscisbarcode()" id="dwnuscisbarcode" href='mybarcode.png' download hidden>Download Barcode Image</a>
</div>




<h1>QR Conference System</h1>
<img align="right" width="250" height="400" src="https://i.ibb.co/bQChvMy/Ekran-g-r-nt-s-2022-06-04-011948-1.png">
<p align="left"> 
  QR code scanning system used at <a href="https://www.linkedin.com/events/technoz6935059638434308097/">Techno Z</a> event
</p>
<h1>Debugging</h1>
Debug: npm run start<br>
Dev: npm run dev<br>
Test: npm test
<h1>Project structure</h1>

๐ฆqr-conference-system  
 โ โฃ ๐plugins  
 โ โ โฃ ๐photon  
 โ โ โ โฃ ๐css  
 โ โ โ โ โ ๐photon.min.css  
 โ โ โ โ ๐fonts  
 โ โ โ โ โฃ ๐photon-entypo.eot  
 โ โ โ โ โฃ ๐photon-entypo.svg  
 โ โ โ โ โฃ ๐photon-entypo.ttf  
 โ โ โ โ โ ๐photon-entypo.woff  
 โ โ โ ๐qr-reader  
 โ โ โ โ ๐html5-qrcode.min.js  
 โ โฃ ๐ui  
 โ โ โ ๐main.html  
 โ โฃ ๐.gitattributes  
 โ โฃ ๐.gitignore  
 โ โฃ ๐index.js  
 โ โฃ ๐package-lock.json  
 โ โ ๐preload.js  
 โฃ ๐test  
 โ โฃ ๐excel  
 โ โ โ ๐save-excel-file.test.js  
 โ โ ๐json  
 โ โ โฃ ๐qr-to-serializer.test.js  
 โ โ โ ๐save-json-file.test.js  
 โฃ ๐usecases  
 โ โฃ ๐excel  
 โ โ โ ๐save-excel-file.js  
 โ โ ๐json  
 โ โ โฃ ๐qr-to-serializer.js  
 โ โ โ ๐save-json-file.js  
 โฃ ๐package.json  
 โ ๐Readme.md
<h1>Usage</h1>
<p>When you scan the QR code, the information read is saved in the excel table. If the quality of your webcam is bad, you can try <a href="https://play.google.com/store/apps/details?id=com.dev47apps.droidcam&hl=tr&gl=US">droidcam</a> as an alternative.</p>
<img  src="https://i.ibb.co/WchxZJ4/Ekran-g-r-nt-s-2022-06-04-011525.png">
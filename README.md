<div align="center">
    <a align="center" width="100%">
        <img width="100px" src="https://raw.githubusercontent.com/zenstorage/Reddit-NSFW-Unblur/main/assets/icon.png">
    </a>
    <h1 align="center">Reddit NSFW Unblur</h1>
    <img width="50%" src="https://raw.githubusercontent.com/zenstorage/Reddit-NSFW-Unblur/main/assets/before-addon.png"><img width="50%" src="https://raw.githubusercontent.com/zenstorage/Reddit-NSFW-Unblur/main/assets/after-addon.png">
</div>
<h2>Installation</h2>
<h2>Browser Extension</h2>
<p>Only for Firefox</p>
<p>
    <a href="https://addons.mozilla.org/pt-BR/firefox/addon/reddit-nsfw-spoiler-unblur/">
    Firefox Addon
    </a>
</p>
<h2>Userscript</h2>
<p>First install a userscript manager:</p>
<h4>Firefox:</h4>
<blockquote>
    <a href="https://addons.mozilla.org/pt-BR/firefox/addon/tampermonkey/" >
    Tampermonkey
    </a>
    <br>
    <a href="https://addons.mozilla.org/pt-BR/firefox/addon/violentmonkey/" >
    Violentmonkey
    </a>
    <br>
    <a href="https://addons.mozilla.org/pt-BR/firefox/addon/firemonkey/" >
    Firemonkey
    </a>
</blockquote>
<h4>Chrome:</h4>
<blockquote>
    <a href="https://chromewebstore.google.com/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo" >
    Tampermonkey
    </a>
    <br>
    <a href="https://chromewebstore.google.com/detail/violentmonkey/jinjaccalgkegednnccohejagnlnfdag" >
    Violentmonkey
    </a>
</blockquote>
<p>Then install userscript:</p>
<a href="https://greasyfork.org/scripts/485608">Reddit NSFW Unblur</a>
<h2>Alternative Methods</h2>
<h4>uBlock Origin</h4>
<p>Add to my filters:</p>
<pre>reddit.com##.prompt
||www.redditstatic.com/shreddit/pt-BR/xpromo-nsfw-blocking-modal*.js$all,domain=reddit.com</pre>
<h4>Request Control</h4>
<p>Add to extension this rule:<a href="https://pastebin.com/2x2NuzUp"> request-control-rules.json</a></p>
<img src="https://i.imgur.com/2oVX1dD.png">
<h2>Related to Reddit</h2>
<h4>Show original images on Reddit</h4>
<p>Using Request Control, create a rule e use this config:</p>
<img src="https://i.imgur.com/88YYMgW.png">
<p>Using Redirector, create a rule e use this config:</p>
<blockquote>Tip: if you want open original image, instead image with reddit layout, leave Main window checked</blockquote>
<img src="https://i.imgur.com/36MNlQg.png">
<p>Using ModHeader, create a rule e use this config:</p>
<blockquote>Tip: if you don't want show original images in posts, replace <code>image/*</code> with <code>image/webp</code></blockquote>
<img src="https://i.imgur.com/FmvA6Mp.png">
<h4>Userstyle</h4>
<blockquote>    
    <a href="https://userstyles.world/style/9384/minimal-reddit">Minimal Reddit</a>
</blockquote>
<h4>Userscript</h4>
<blockquote><a href="https://greasyfork.org/pt-BR/scripts/478969-reddit-replace-player-with-videojs">Reddit Replace Player with VideoJS</a></blockquote>
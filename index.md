---
layout: libdoc/page-split
title: The Sasse Library
---
![](/assets/SASSE_Library_Splash.png)

Welcome to the SASSE Documentation!

SASSE is a Toon, Anime, NPR Asset Library for Blender 4+

Scroll through a sample of the assets included in the library on the right, or use the Sidebar on the left to navigate directly to the assets you want to see.

The Introduction covers what SASSE is, what is does, and why it was created.

The User Guide contains info on how to install and use the library in Blender.

Below that are the categories that you can find in the Asset Browser in Blender:
- Assets
- Effects
- Linework
- Materials
- Node Groups

And, finally, the FAQ section, covering thanks, acknowledgements, frequently asked questions, and everything else!

Thank you for visiting the SASSE docs!

```html
<nav    class="top"
        scroll-btween="nav_1"
        data-detector="detector-w1" 
        data-top="|0:20 to 30:0 to 100:0|px">
    <a  href="{{site.url}}{{site.baseurl}}/#playground-example" target="_parent">Code of this playground</a>
</nav>
<article>
    <p>
        <span scroll-btween="w1" 
                data-detector="detector-w1" 
                data-opacity="|0:1 to 98:1 to 100:0|" 
                data-transform="scale(|0:1 to 98:1 to 100:2|)" 
                data-letter-spacing="|0:-0.05 to 100:0|em">Scroll down</span>
        <span scroll-btween="w2" 
                data-detector="detector-w2" 
                data-opacity="|0:0 to 2:1 to 98:1 to 100:0|" 
                data-transform="scale(|0:0 to 2:1 to 98:1 to 100:2|)" 
                data-letter-spacing="|0:-0.1 to 100:0|em">This is a</span>
        <span scroll-btween="w3" 
                data-detector="detector-w3" 
                data-opacity="|0:0 to 2:1 to 98:1 to 100:0|" 
                data-transform="scale(|0:0 to 2:1 to 98:1 to 100:2|)" 
                data-letter-spacing="|0:-0.1 to 100:0|em">playground</span>
        <span scroll-btween="w4" 
                data-detector="detector-w4" 
                data-opacity="|0:0 to 2:1 to 98:1 to 100:0|" 
                data-transform="scale(|0:0 to 2:1 to 98:1 to 100:2|)" 
                data-letter-spacing="|0:-0.1 to 100:0|em">example</span>
        <span scroll-btween="w5" 
                data-detector="detector-w5" 
                data-opacity="|0:0 to 2:1 to 98:1 to 100:0|" 
                data-transform="scale(|0:0 to 2:1 to 98:1 to 100:2|)" 
                data-letter-spacing="|0:-0.1 to 100:0|em">with its</span>
        <span scroll-btween="w6" 
                data-detector="detector-w6" 
                data-opacity="|0:0 to 2:1 to 98:1 to 100:0|" 
                data-transform="scale(|0:0 to 2:1 to 98:1 to 100:2|)" 
                data-letter-spacing="|0:-0.1 to 100:0|em">own settings</span>
    </p>
</article>
<div id="detector-w1" class="detector">&nbsp;</div>
<div id="detector-w2" class="detector">&nbsp;</div>
<div id="detector-w3" class="detector">&nbsp;</div>
<div id="detector-w4" class="detector">&nbsp;</div>
<div id="detector-w5" class="detector">&nbsp;</div>
<div id="detector-w6" class="detector">&nbsp;</div>
<nav class="bottom">
    <a  href="https://olivier3lanc.github.io/Scroll-Btween" target="_blank">This demo uses ScrollBtween</a>
</nav>  
<style>
@import url('https://fonts.googleapis.com/css2?family=Kufam:wght@600&display=swap');
html {
    position: relative;
}
html::before {
    content: '';
    pointer-events: none;
    display: block;
    position: absolute;
    top: 20px;
    left: 20px;
    width: calc(100% - 40px);
    height: calc(100% - 40px);
    border: 1px solid white;
}
body {
    color: #FFF;
    font-family: 'Kufam', sans-serif;
    background: radial-gradient(circle at 50% 50%, #ffb56b, #f39060, #e16b5c, #ca485c, #ac255e, #870160, #5b0060, #1f005c);
}
nav.top {
    position: fixed;
    top: 20px;
    right: 20px;
    z-index: 1;
}
nav.bottom {
    position: absolute;
    bottom: 20px;
    right: 20px;
    z-index: 1;
}
nav a {
    display: inline-flex;
    padding: 1em;
    color: white;
    font-size: 14px;
    font-family: monospace;
}
article {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
}
p {
    font-size: 10vmin;
    letter-spacing: -0.1em;
    line-height: 1em;
    text-align: center;
    white-space: nowrap;
    position: relative;
    top: 50%;
    left: 50%;
    transform: translateX(-50%) translateY(-50%);
}
p > span {
    position: absolute;
    top: 0;
    left: 0;
    display: block;
    width: 100%;
    opacity: 0;
    margin: -1em 0em 0em 0em;
}
.detector { margin-top: 95vh; margin-bottom: 95vh; }
</style>
```
{:.playground title="Optional title"}

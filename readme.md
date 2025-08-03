# Marquee In Tab

Here’s a little demo showing how to make your page title scroll like a marquee in the browser tab with just a bit of JavaScript. It’s just for fun and won’t mess with your SEO since search engines only look at the original text in the &lt;title&gt; tag.

## Usage

- This requires VERY little JavaScript. Go ahead and copy the code below, and then put it in a &lt;script&gt; tag on your webpage.

const base = "Yay!  An animated tab!!!  This is great!!!";
let text = base + "     ";

setInterval(() => {

  text = text.slice(1) + text[0];
  document.title = text;
}, 300);

## Live Demo

-Check out a live demo of this at https://marquee-in-tab.neocities.org/

## Misc

-This site was styled using WaterCSS https://watercss.kognise.dev/

-This repo was inspired by https://syntheticfruits.neocities.org/ because I noticed it in their browser tab on their site
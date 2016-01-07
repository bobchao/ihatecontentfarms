Porting ihatecontentfarms to Firefox using WebExtensions.
Still WIP, nothing works right now.

# Prerequisites

<pre><code>
  npm install
  npm install gulp
</code></pre>

and https://developer.mozilla.org/en-US/Add-ons/WebExtensions/Prerequisites 

# After anything changed

<pre><code>
  gulp
  cd build/chrome
  zip -r ../ihatecontentfarms.xpi *
</code></pre>

Then drag the .xpi to Firefox. Check Tools > Browser Console if anything wrong.

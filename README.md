Porting ihatecontentfarms to Firefox using WebExtensions.
Still WIP, nothing works right now.

# Prerequisites

  npm install
  npm install gulp

and https://developer.mozilla.org/en-US/Add-ons/WebExtensions/Prerequisites 

# After anything changed

  gulp
  cd build/chrome
  zip -r ../ihatecontentfarms.xpi *

Then drag the .xpi to Firefox. Check Tools > Browser Console if anything wrong.
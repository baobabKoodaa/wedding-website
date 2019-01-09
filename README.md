# Wedding Website
A beautiful, feature rich, device friendly wedding website.  
_See [link](https://link) for a demo, or clone this repo locally and run index.html. Use invite code `271117` to RSVP._

# Highlights
1. Slick and fully __responsive__ design.
2. __RSVP feature__ which directly uploads data to a Google sheet.
3. __Receive email alerts__ when someone RSVPs.
4. __Add to Calendar__ feature which supports four different calendars.
5. Start and run the website __completely free__. No hosting, backend server, or database required as you can
use [GitHub pages](https://pages.github.com/) to host and Google sheets (with the help of Google scripts) to store rsvp data.

# If you fork this
Have fun! You have permission to use the source code (within license terms). License does not apply to images. You may not use the images from this repo.
_You need npm and gulp. Run `$ npm install` to install dependencies. If you run into problems, try to delete node_modules and run it again (folder is included in repo for hosting reasons).
_Whenever you modify files in sass folder, you need to minify etc. by running `$ gulp`._
_Set up Google sheet for RSVP feature according to [this article](https://github.com/dwyl/learn-to-send-email-via-google-script-html-no-server).

# Credits
Hello, my name is Atte. I didn't start this from scratch; I started by forking [Ram Patra's excellent wedding website](https://github.com/rampatra/wedding-website).
Majority of the design and functionality should be credited to him.
_Here is a list of changes:
1. Changed Google Map embedding so that it doesn't require API access, Google Cloud Platform account and an attached credit card. Unlimited free usage now.
2. Changed scaling of top image so that it fills the entire screen (slightly overfills the height on mobile for some reason).
3. Removed embedded video, uber button, social media trackers
4. Our own content, photos, etc. Minor design changes, like mobile friendly line breaks, added tooltip, etc.


# Wedding Website
A beautiful, feature rich, device friendly wedding website.  
See [https://attejamarianne.fi](https://attejamarianne.fi) for a demo, or clone this repo locally and run index.html.

# Highlights
- Slick and fully __responsive__ design.
- __RSVP feature__ which directly uploads data to a Google sheet and emails you.
- __Add to Calendar__ feature which supports four different calendars.
- Start and run the website __completely free__. No hosting, backend server, or database required as you can
use [GitHub pages](https://pages.github.com/) to host and Google sheets (with the help of Google scripts) to store rsvp data.

# Feel free to fork this
1. You have permission to use the source code (within license terms), but not the images.
2. You need npm and gulp. Run `$ npm install` to install dependencies.
3. Whenever you modify files in sass folder, you need to minify etc. by running `$ gulp`.
4. Set up Google sheet for RSVP feature according to [this article](https://github.com/dwyl/learn-to-send-email-via-google-script-html-no-server).

# Credits
Hello, my name is Atte. I didn't start this from scratch; I started by forking [Ram Patra's excellent wedding website](https://github.com/rampatra/wedding-website).
Majority of the design and functionality should be credited to him and his wife Antara. My wife Marianne was also instrumental in our design changes.

Here is a list of changes:
1. Changed Google Map embedding so that it's unlimited free usage now. It used to require API access, Google Cloud Platform account and an attached credit card.
2. Changed RSVP form. It used to be simple 4 fields, but we needed more info. Now it's more like a decision tree where relevant fields are shown only to those who need them. Note that tabbing has been disabled as a workaround to a mobile issue.
3. Removed node_modules from repo (reducing size from 60MB to 10MB).
4. Removed embedded video, uber button, dress code and social media trackers.
5. Design changes: "splash screen style" background image to fill entire viewport (with placeholder svg and transition), mobile friendly line breaks, 3x3 image fancybox, added tooltip, etc.

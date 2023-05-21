# Hello PWA

TODO:
 - Can service worker AND index.js can read from manifest.json for notification title and app image?
 - Can is there a consistent but randomizable way to set cache name? manifest file hash? (to avoid collisions between remixes if that step is missed)
 - Read more about the mac/OS level notifications — can we customize the URL bit that shows under the title? Do they even show up by default? (looks like maybe no on mac?)
 - Check installed app locations on MacOS, Windows, iOS, Android so we can set proper expectations
 - How do we add the push server location gracefully?
 - Page design, style cleanup
 - Form labels, accessibility
 - Copy, explainer, and README (be sure to explain permissions in various browsers...)
 - Check: mobile notifications, app icon loader
 - Why isn't the notifications permission check not waiting to fire on mobile safari?
 
README STUFF:
 - manifest _needs_ "display": "standalone" to work right on iOS!
 - doesn't need apple specific stuff in the head — manifest is plenty now!
 - Helpers: iOS orientation change zoom fix, isInstalledPWA boolean
 - Features: realtime notifications, setting/clearing badges, orientation change detection


## You built this with Glitch!

[Glitch](https://glitch.com) is a friendly community where millions of people come together to build web apps and websites.

- Need more help? [Check out our Help Center](https://help.glitch.com/) for answers to common questions.
- Ready to make it official? [Become a paid Glitch member](https://glitch.com/pricing) to boost your apps with private sharing, more storage and memory, domains and more.

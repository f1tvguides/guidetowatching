# How To Watch F1TV

## Announcement:
Hey all! A new season is upon us, with some exciting updates to the apps. I'm preparing a new guide with all the updates, and I hope to have it ready before the first GP of 2022.

Here's the quick summary of the latest changes:

-	Official F1TV apps now save resume position
-	Official apps now allow watching live events from the start
-	PLC renamed to F1 Live, Main Feed renamed to F1 International
-	Third Party Apps may need updates to support any new functions

Thanks for reading!

-----

**Updated 2021-11-08, official Android TV app released, as well as Apple TV. Full change list at the end of the post.**

It's a new season, and with updates to F1TV, I wanted to create a new guide thread with all the options for how to watch F1 across various platforms. There are still updates to come for this season, so as those happen, I'll update this post, or create a new one when it finally gets auto archived after 180 days.

### Note About Subscriptions
For this thread, I won't be covering subscription options. Please search the rest of the sub for more information. As a general guideline, there are two F1TV subscription packages:

-	F1TV Access, which allows you to watch most content, usually with a two day delay
-	F1TV Pro, the best of the best, all content, including live feeds, and replays within minutes of a session ending

As always, these may have local limits to the region you're signing up from, as well as where you may be watching from. The [Content Schedule](https://www.formula1.com/en/toolbar/content_schedule.html) is a great guideline on what's available. The [F1TV Support page](https://support.f1.tv/s/?language=en_US) is also **full** of useful information.

## What's new, right now?
For this year, F1TV has introduced a brand new website with a new API for video.

**Not all of these features are everywhere just yet.** There are some limitations, which we'll cover below.

The main highlights:

-	1080P 50fps for the main feed
-	720P 50fps for secondary feeds (Pit Lane Channel, others)
-	The ability to rewind/pause/fast forward in a live stream, allowing you to start at the beginning of a session, even while it is still on

## What's coming later this year?
At some point this season, F1TV has stated these features are coming. Some of them are listed for the first half of the year. Some are now available; indicated with a checkmark.

-	✅ Chromecast from mobile apps
-	✅ AirPlay from computer and mobile apps
-	✅ Apple TV app
-	✅ Android TV app, (can be side loaded to Fire TV)

## How do I watch F1TV…
This will depend on your platform of choice, and the different options will have different restrictions to note.

## …on my computer?

**Option 1 - The Website**

The best supported option is to use the [official website](https://f1tv.formula1.com). You can usually connect your computer to your TV as well.

Official Website Features:

-	Will play in 1080p50/720p50
-	Allows Chromecast from Chrome browser
-	Allows AirPlay when using Safari on macOS

&gt;**Q: It stutters (when using Chrome)!**

A: You may experience stuttering when using Chrome. This is a weird known issue because of some changes Chrome made with certain types of video playback on certain systems. I help work on r/Jellyfin, and we've seen the issue too. Either use a different browser, or turn off [Hardware Acceleration](https://www.howtogeek.com/412738/how-to-turn-hardware-acceleration-on-and-off-in-chrome/).

---

Community made tools make up the rest of the computer list.
**Please remember that all community developers are unpaid volunteers, giving their own time to give us options to enhance our F1TV experience.**

---

**Option 2 - F1Viewer**

_F1Viewer has been updated! It now uses the new API._

Available on all platforms (Linux, macOS, Windows), [F1Viewer](https://github.com/SoMuchForSubtlety/f1viewer) is a trustworthy standby in the community, made by SoMuchForSubtlety.

It can be very powerful when deployed correctly. Posts [like this](https://www.reddit.com/r/F1TV/comments/mdqozy/f1viewer_is_still_the_best_viewer_for_the_2021/) by u/balexandre really show off how to make it great.


**Option 3 - Race Control**

For Windows users, the [Race Control](https://github.com/robvdpol/RaceControl) app is a great option. Made by u/SpoIIie, it's been updated to support the new video feeds for new sessions, and has multi feed support. It's one of the apps typically used to get those fun multi screen setups you see on this sub.

Race Control features:

-	1080p50/720p50 for new sessions
-	Allows multiple feeds at once
-	Can send video to Chromecast


**Option 4 - Unofficial Kodi Add-On**

Another community app, made by u/bbsan2k. This add-on is currently under fast development to ensure it's updated for the new F1TV features, thanks to u/TheDevFreak. To take advantage of the new video feeds, it's recommended (and possibly required) to use Kodi 19 (Matrix).

The add-on is available on [GitHub - plugin.video.f1tv](https://github.com/bbsan2k/plugin.video.f1tv/releases).

Features (in beta):

-	1080p50/720p50 for new sessions

**Option 5 - F1Hub**

This is a relative newcomer to the scene, made by u/kodosExecutioner. Written in Python, it'll run on all systems (Linux, macOS, Windows). There's a new GUI, and an easy installer for Windows. Try the screen presets to have multiple feeds setup!

F1Hub is temporarily not available for new downloads.

F1Hub Features:

-	1080p50/720p50 for new sessions
-	Allows multiple feeds at once

**Option 6 - F1 Web Viewer**

A fresh new entry, this is a special website that connects to F1TV for you and provides a whole TON of easy to use Drag and Drop features to help you build the layout you want. Includes syncing options, and can also be self-hosted if you want to run it yourself.

Since it uses the website, it has all the standard quality features.

More details here on Reddit: [F1 Web Viewer - A new way to watch F1](https://www.reddit.com/r/F1TV/comments/npgd82/new_f1_web_viewer_a_new_way_to_watch_f1/).


**Option 7 - F1TV+**

This is another new tool. It's a TamperMonkey script that modified the F1TV website to enable extra features, including a multi feed mode. Because it uses the original website, it gets the benefits of the higher quality playback.
More information is available on [GitHub - F1TV+](https://github.com/najdek/f1tv_plus).

## …on my Chromecast?
Using the official website, with the Chrome browser, on a computer, you can cast to a Chromecast. 

**UPDATED 2021-04-21:** The mobile app has been updated! You can now cast from your phone/tablet to a supported Chromecast or Cast-enabled TV. This uses the new API for high quality video (1080p50). No split screens are possible (e.g. head to head views), but controls are fast and responsive.

**This is not the same as casting your tab. This is actual Chromecast integration.**

You can see an example of this here - [Reddit: How To Stream To Chromecast Properly](https://www.reddit.com/r/F1TV/comments/mdqgv1/how_to_stream_to_chromecast_properly_steps_in/).

General Tips:

-	Start your Chromecast first
-	It must be an actual Chromecast, not a "cast compatible TV" (Like most newer LG or Samsung TVs). If your TV says "Available on specific sites" in Chrome, it won't work. That's not a real Chromecast.

You can also try using Race Control from the computer section above, if you're using Windows.

If you have the _new_ Chromecast with Google TV on it, see the Android TV section for an app option.

Some folks have reported success by using Chrome on an Android device, set to "Desktop Mode". This is untested and may stop working, so your mileage may vary.

## …via AirPlay/Apple TV?
**UPDATED 2021-10-17:** There is now an official Apple TV app! The unofficial option is still available for the time being.

**UPDATED 2021-04-21:** AirPlay is now available from the official app! This includes support for AirPlay to an Apple TV, and AirPlay to a TV (LG, VIZIO, Sony, Samsung, etc). The app update uses the new API for high quality video (1080p50). Head to Head (two feed view) is no longer possible, but all feeds seems to be very fast and responsive, in sync, and with updated controls!

The official [Apple TV app](https://apps.apple.com/us/app/f1-tv/id1315007279) has been released! Install it just like normal from the App Store.

If you have an Apple TV and want to customized your viewing experience, you're in luck. There's an app made by u/NoahFetz that has multi-stream support.

You can find out more on [GitHub - F1 Apple TV](https://github.com/NoahFetz/F1AppleTV).

Note that you must have TestFlight installed on your iPhone/iPad as well as your Apple TV for the invite link to work.

## …to my Android TV/Fire TV/Google TV device?

**UPDATED 2021-11-08:** There is now an official Android TV app! It is the same entry as the official Android app, on the [Google Play](https://play.google.com/store/apps/details?id=com.formulaone.production&hl=en&gl=US) store. The unofficial option is still available for the time being.


On supported devices, consider Chromecasting either from the computer, or one of the mobile apps. Otherwise, there will be an official app option, but currently with no known date other than 2021.

There's an unofficial app called "F1TV Viewer for Android TV", sometimes also called [Race Control TV](https://github.com/leonardoxh/race-control-tv) by u/leonardoxh. It's available on the [Google Play Store](https://play.google.com/store/apps/details?id=com.github.leonardoxh.f1), and allows you to watch on the big screen. This app has been updated to use the new API, and gets the new 1080p50/720p50 experience.

If you'd like to use it on your Fire TV device, you can sideload it. There's user instructions here: [Reddit - Sideload Race Control TV to Fire TV](https://www.reddit.com/r/F1TV/comments/m7nb82/f1tv_androidtv_viewer_now_updated_for_1080p50/grcdsr5?context=3).

## …on my Roku?
If your device is new enough (most are, like my 3810 Streaming Stick Plus from 2019), then you can use the Roku channel.

**UPDATED (Apr 12):** The Roku channel now uses the new API for high quality video (1080p50), and is available in more countries!

The Roku channel is so far confirmed in the US, Canada, Mexico, and Chile. Check your local channel store to see if it's available. If not, you can still try unlinking to reset your Roku and install from another territory.

A Twitter user used the Channel Store API to get a list of countries. See [here](https://twitter.com/hollogramtv/status/1381036052203380743).

The US channel is available here: [Roku Channel Store - F1TV](https://channelstore.roku.com/details/4af8eceac36ccd8b432a2d37712dde90/f1-tv).

##  …on my Phone or Tablet?
Use the official F1TV app! It's available on [Google Play](https://play.google.com/store/apps/details?id=com.formulaone.production), the [Amazon App Store](https://www.amazon.co.uk/Formula-One-Digital-Media-Limited/dp/B077VPVD47), or the [Apple AppStore](https://apps.apple.com/us/app/f1-tv/id1315007279).

**UPDATED 2021-04-21:** The apps have been updated! They now use the new API (1080p50), and support Chromecast. The iOS app now supports AirPlay as well. Head to head screens (two driver feeds at once) seems to be gone, but the new feed switcher and controls are fast and responsive. Testing so far shows it to be in sync.

## …on another device (smart TV browser, Xbox One browser, etc)?
**Update**: All Xbox One consoles should have the new Edge browser as of the latest update, and now streaming works again!

You can also use the add-on if you install Kodi on your Xbox or other device running Kodi. Look for it in the Computer section above (thanks for confirming u/TricolorCat!)

Others:
Sorry, there's no easy option at this time. You might try getting the raw video URL from another program on the computer, but there's no guarantees this will work.


---

I hope this helps everyone who wants to watch F1. If you have any comments or suggestions, please let me know. I'm considering making this a hosted website to make it easier to update, and include more information, screenshots, and an easier to navigate interface. Let me know if you'd like to see that.

Enjoy the season!

---

_Change Log_

2021-03-27:
-	Better formatting for post. More updates.

2021-03-28:
 - The Xbox can use the Kodi add-on, if you have installed Kodi on it
-	Chrome on desktop may stutter. Use another browser or turn off [hardware acceleration](https://www.howtogeek.com/412738/how-to-turn-hardware-acceleration-on-and-off-in-chrome/).

2021-04-12:
-	Roku app updated to new API (1080p50), and now in more countries! So far confirmed: US, Canada, Mexico, Chile. Others are available, see [Twitter](https://twitter.com/hollogramtv/status/1381036052203380743).

2021-04-21:
-	iOS and Android apps updated! Both now use the new API (1080p50), and Chromecast is supported. If using the iOS app, you can now AirPlay to a supported device. Head to Head casting (two screens) seems to be missing, but switching between feeds is fast and in sync. Controls upgraded, much easier to use now.

2021-05-04:
-	F1 Viewer has been updated for the new API!
-	The Kodi plugin has a [new release in Beta](https://github.com/bbsan2k/plugin.video.f1tv/releases)

2021-05-20:
-	F1 Hub now has a GUI, Windows installer, and screen presets!

2021-06-19:
-	F1 Web Viewer now added.

2021-09-26
-	Xbox consoles have been updated to the new Chrome based Edge browser, so playback works.

2021-10-17
-	Official Apple TV app has been released!

2021-11-08
-	The official Android TV app was released this past week!
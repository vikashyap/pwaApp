
# pwaApp
Working to build PWA App
#“A Progressive Web App uses modern web capabilities to deliver an app-like user experience.”
Native app store apps do things like send push notifications, work offline, look and feel like an app 
(as Apple and Google have imagined them), load on the homescreen, and so on and so forth. 
Mobile Web Apps accessed in a mobile browser, by comparison, historically haven’t done those things.
Progressive Web Apps fix that with new Web APIs, new design concepts, and new buzzwords.
To be clear, I’m talking about browser mobile web apps. Hybrid apps, like Ionic with Cordova,
run uninhibited in the native app environment, with all the features we expect of any native app. 
But pull out the web content from a hybrid app and load it in a mobile browser, 
and the app is thusly constrained by the features of the browser (for a variety of good security and API standardization reasons).

Progressive Web Apps bring features we expect from native apps to the mobile browser experience in a way 
that uses standards-based technologies and run in a secure container accessible to anyone on the web.

On the whole, Progressive Web Apps describe a collection of technologies, design concepts,
and Web APIs that work in tandem to provide an app-like experience on the mobile web. 
Let’s walk through some of the core tenets of Progressive Web Apps.

# Service Workers
Service Workers are an incredibly powerful, and equally as confusing, technology behind a Progressive Web App. 
They power offline functionality, push notifications, background content updating, content caching, and a whole lot more.

# Installability and App Manifest
Historically, mobile web apps were not installed like an app to the homescreen. 
Sure, a user could “pin” a mobile website to their homescreen on iOS and Android, but the experience was second-rate,
and the app still did not come with the local features we expect out of native apps (plus, does anyone actually do that?).

This is changing. Recently, Chrome on Android added support for installing web apps to the homescreen with a native install banner, 
just like the native app banners we’re used to.

To tell Chrome our mobile website is installable as an app, we write a manifest.json file and link to it from our main HTML page
(see the second link above for a full example).

# To run above Code.
Download or clone the code.
After downloading use APACHE or XAMP server to run your code.
You will find your PWA app is running.
You can check its offline functionality by turn of your browser network or by stopping your server.

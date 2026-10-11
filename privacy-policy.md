# OurSky Privacy Policy

*Last updated October 11, 2026*

**The short version:** There is no account, so there is nothing to attach data to. Your location is used to fetch weather and is not stored on any server run by this app. The only thing sent out is what you ask for when you tap AI Vibe Check.

## Your location
If you allow location access, the app reads your coordinates to look up the weather where you are and to name your city on screen. Coordinates go to Apple's WeatherKit to fetch a forecast. They are not sent to any server run by this app, and no location history is kept. You can turn location off any time in iOS Settings and set your city by hand instead.

## Weather data
Forecasts come from Apple WeatherKit, so Apple receives the location being looked up. City search suggestions come from Apple Maps, so what you type into the city field is sent to Apple to return matches. Apple's handling of these requests is covered by Apple's privacy policy.

## AI Vibe Check
This is the one feature that sends anything to a server run by this app, and only when you tap it. The request contains the two city names, the display names you picked, and the current conditions for both places (temperature, description, humidity and wind). It goes to a Cloudflare Worker, which passes it to an AI model to write the reading you see. It carries no account, no device identifier and no coordinates. If you never tap the button, nothing about you leaves the device this way.

## Partner sync
If you pair with someone using a code, the app stores your latitude, longitude, city name, chosen display name, a random device identifier and a timestamp in Apple's iCloud, in a shared area readable by whoever holds that pair code. This only happens after you enter a code. Unlinking deletes the record. Do not share a pair code with anyone you would not share your location with.

## What stays on your phone
Names, accent colors, unit preferences, card layout, saved cities and whether you have seen the guide are stored in the app's own storage on your device. They sync to the widget, Live Activity and Apple Watch app through a shared container on the same device. Deleting the app removes all of it.

## Purchases
Subscriptions are handled entirely by Apple through the App Store. The app is told whether you have an active subscription and nothing more. Payment details are never visible to this app.

## What the app does not do
- No account and no sign up
- No advertising and no ad identifiers
- No analytics or tracking SDKs
- Nothing sold or shared with data brokers
- No location history stored anywhere

## Notifications
Notifications, widgets and the Live Activity are generated on your device from forecast data already fetched. Nothing extra is collected to power them.

## Children
The app is not directed at children under 13 and does not knowingly collect anything from them.

## Changes
If what the app collects changes, this page will be updated and the date at the top will change.

## Contact
Questions: support@ourskyapp.com

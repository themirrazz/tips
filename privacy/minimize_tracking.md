# How to Minimize Tracking
[Homepage](https://github.com/themirrazz/tips) [Privacy tips](https://github.com/themirrazz/tips/tree/main/privacy)

## 1. Switch to DuckDuckGo

DuckDuckGo is one of the many search engines that don't track you. They show ads based on what you search, not who you are.

The amount of users who use DuckDuckGo is unknown; they don't know how many users use DuckDuckGo because they don't track you!

## 2. Use Cloudflare as your DNS

If your using Google DNS as any of your DNS servers (8.8.8.8 or 4.4.4.4), you should remove it and use Cloudflare. Cloudflare's DNS addresses are 1.0.0.1 and 1.1.1.1.

You can visit 1.1.1.1 or cloudflare.com to learn more about Cloudflare.

## 3. Install Brave Browser or Firefox

Firefox and Brave both come with built-in ad/tracking blocking. Brave is Chromium based, and therefore has more capabillities.

Firefox, however, may run better on your device. If you have a [Raspberry Pi](https://github.com/themirrazz/tips/tree/main/tech/raspberry-pi.md),

your only choice is to install Firefox, as Brave currently does not support Raspberry Pi.

## 4. Install the uBlock Origin Extension

If you're using Brave or Opera, which are both Chromium based, or actual Chrome itself (not recommended), you can install it [here](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm?hl=en).

If you have Firefox, Pale Moon, or a Firefox-based browser, you can install it [here](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/).

If you happen to use Microsoft Edge as your default browser (NOT RECOMMENDED AT ALL), you can install it [here](https://microsoftedge.microsoft.com/addons/detail/ublock-origin/odfafepnkmbhccpbejgmiehpchacaeak) or on the Chrome Web Store.

uBlock Origin is a [Free-and-open-source](https://github.com/themirrazz/tips/tree/main/patents/foss.md) adblocker. As well as blocking ads, it also blocks common tracks.
The unique thing about uBlock Origin is it knows common trackers, but it also has a template of what an ad or tracker is, allowing it to block an ad company the millisecond they incorperate themselves.


## 5. Disable "Ok Google", "Hey Siri", and Alexa's "wake word"

These wake words are ran on-device, which means they don't use as powerful speech recognition.

This leads to thinking it hears "ok google" or "Alexa" when really it doesn't.

This then leads to companies recording conversations because a misinterpetted word.

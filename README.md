# Ads and Recommended Content blocker for LG TVs

## Update: Go offline.

I just wanted to provide an update that despite my best efforts, my C2 at least keeps showing notifications on every boot. This appears to be a part of their plan to become an advertising company. [Click here](https://www.theverge.com/2023/7/14/23794747/lg-tv-smart-home-appliances-ads-subscriptions-webos) for more info. As a result, I have decided to just take it offline. I reset my TV and erased all network settings. I will not be bring it online for the forseeable future. While this list doesn't fully eliminate the notifications, and recommendations, it does still reduce them drastically. So I will be leaving it up. If you have new additions or changes, feel free to create a PR, and I will accept it. In the meantime, I will keep updating it's firmware, and testing it, if the firmware degrades performance or removes features, I will update this readme.

## Test info

- Test Device: LG C2 77-inch
- Test Continent: North America
- Test Country: United States
- Test State: Minnesota
- Latest tested firmware version: 03.33.90
- Date last tested: 20th December 2023

## FAQ

### What does it do?

When used by a pihole, or any other blocker, it blocks LG's annoying toasts, popups, and recommended content section.
It also blocks the software update server in case LG comes up with some patch that allows them to bypass a DNS blocker.

### What doesn't it do?

It does not block ads on YouTube. It does not block content on Amazon Prime or Spotify.

### Sounds great, how do I use it?

- Open the [list](https://github.com/TheShawnMiranda/LG-TV-Ad-Block/blob/master/list) file within this repo.
- Select Raw on the top right.
- Copy the URL.
- Go to the PiHole Dashboard.
- Select Adlists on the left side.
- Paste the URL in the address box.
- Click the Add button.
- Click on the Tools dropdown on the left hand side menu bar.
- Select Update gravity.
- Click on the Update gravity button.
- Turn off your TV, and disconnect it.

When you turn it on again, it will fail to load the recommended tab, and just show you your apps.

Known bug:

The LG C2 crashes when exiting the Prime Video app via the back button. This is an issue with the app, not caused by the blacklist. To resolve it, turn off the TV, disconnect it, and reconnect it. Or, to prevent it from happening, exit the Prime Video app via the home button.

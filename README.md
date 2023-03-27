# Ads and Recommended Content blocker for LG TVs

## Test info

- Test Device: LG C2 77-inch
- Test Continent: North America
- Test Country: United States
- Test State: Minnesota
- Latest tested firmware version: 03.30.45
- Date last tested: 27 March 2023

## FAQ

### What does it do?

When used by a pihole, or any other blocker, it blocks LG's annoying toasts, popups, and recommended content section.
It also blocks the software update server in case LG comes up with some patch that allows them to bypass a DNS blocker.

### What doesn't it do?

It does not block ads on YouTube. It does not block content on Amazon Prime, HBO Max or Spotify.

### Sounds great, how do I use it?

- Open the [list](https://github.com/TheShawnMiranda/LG-TV-Ad-Block/blob/master/list) file within this repo.
- Select Raw on the top right.
- Copy the URL.
- Go to the PiHole Dashboard.
- Select Adlists on the left side.
- Paste the URL to the Raw blacklist in the address box.
- Click the Add button.
- Click on the Tools dropdown on the left hand side menu bar.
- Select Update gravity.
- Click on the Update gravity button.
- Turn off your TV, and disconnect it.

When you turn it on again, it will fail to load the recommended tab, and just show you your apps.

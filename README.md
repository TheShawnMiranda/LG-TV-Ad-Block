# Ads and Recommended Content blocker for LG TVs

## Update: I'm back.

Hello again, I'm back. For a little while there I lost my job, apartment, etc. I'm back at work so I'm able to fund this little side project again. The only issue is I don't currently have a second LG TV to test the latest firmware. My old one is now rooted on the firmware listed below. The new list file, called fullblock is going to be the old list with a couple of new additions for my now rooted C2. I'm not using any apps that aren't from Homebrew Channel anymore so if you still use those and you switch to full block it may break some content. If that happens just use the list file instead.

## Update: ~Go offline~

I just wanted to provide an update that despite my best efforts, my C2 at least keeps showing notifications on every boot. This appears to be a part of their plan to become a data harvesting company.[Click here](https://youtu.be/Q9uefFYe6bM) for more info. ~As a result, I have decided to just take it offline. I reset my TV and erased all network settings. I will not be bring it online for the forseeable future. While this list doesn't fully eliminate the notifications, and recommendations, it does still reduce them drastically. So~ I will be leaving it up. If you have new additions or changes, feel free to create a PR, and I will accept it.

## Test setup

- Test Device: LG C2 77-inch
- Test Continent: North America
- Test Country: United States
- Test State: Minnesota
- Latest tested firmware version: 04.40.90
- Date last tested: 19th August 2026

## FAQ

### What does it do?

When used by a pihole, or any other blocker, it blocks LG's annoying toasts, popups, and recommended content section.

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
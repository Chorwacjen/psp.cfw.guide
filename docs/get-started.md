# Get Started

The cfw we will be installing on the PSP is called **ARK-4**. It is an upgraded and renovated version, compared to the older ones like PRO and ME. It can run emulators,
various plugins, homebrew, game backups and more.

However, before we start, we will get everything required for it to function and install.

## Requirements

- A way to copy downloaded files to your SD/MS card
- An application that can extract archives, such as [7-Zip](https://www.7-zip.org/) (Windows), [The Unarchiver](https://apps.apple.com/us/app/the-unarchiver/id425424353) (macOS), or [ZArchiver](https://play.google.com/store/apps/details?id=ru.zdevs.zarchiver) (Chromebook)
    - We advise you to not use WinRAR, as it is known to break things
    - If you're using Windows 11, we also advise you to not use it's built-in extractor (Windows Explorer), as it'll cause an error saying that the filename is too long or not valid

## Section I - Prep Work

::: warning

Ensure your SD/MS card is [formatted correctly](sd-card-setup.html).

:::

1. Insert your SD/MS card into your PC
1. Download the latest release of [ARK-4](https://github.com/PSP-Archive/ARK-4/releases/download/r154/ARK4.zip)
    - If it does not download, open the [release page](https://github.com/PSP-Archive/ARK-4/releases/), and download `ARK4.zip`
1. Connect your PSP or SD/MS card to the PC.
1. Open `ARK4.zip`
    - If you're using Windows, ensure 7-Zip is installed, then follow these steps:
	    1. Right-click on `ARK4.zip`
		1. If using Windows 11, click `Show more options`
		1. Hover over `7-zip`
		1. Click `Open archive`
1. Copy the `ARK_01234` folder from `ARK4.zip` to the `/PSP/SAVEDATA/` folder on your SD/MS card
1. Copy the `ARK_Loader` folder from `ARK4.zip` to the `/PSP/GAME/` folder on your SD/MS card
    1. PSP Go users can use either the internal or external memory, but both the loader and savedata folders NEED to be on the same location/device.
1. Properly unmount PSP from PC first, then on the PSP disconnect from USB Mode.

::: tip

Unsure what the SD/MS "root" is? [See this image](/assets/images/sdroot/en_US.png)

:::

## Section II - Checking for legacy CFW

1. Go to the Settings tab (furthest on the left in the XMB).
1. Scroll down to System settings > System information.
    - If after `System software:` It is displaying something like `6.20 PRO-C` or `6.60 LME` then your PSP has CFW. Proceed to [chronoswitch](chronoswitch.html).
    - If it doesn't, then congrats: your PSP is most likely on OFW! Proceed to the next section.

## Section III - Installing ARK-4

1. On the PSP go to the Game section (3rd option furthermost from the right icon on the XMB).
1. Click on Memory Stick™.
1. Click on ARK Loader.

That's it! You have running cfw. However, it is semi-permanent, which means you need to re-run the ARK Loader app on each reboot.

::: warning

Continuing this guide **has a very slim possibility of a brick**. If the semi-permanent solution is enough for you, or you are scared of bricking your device, **do not continue**.

:::

::: tip

Continue to [Installing ARK-4 Permanently](ark4-permanent-install.html)

:::
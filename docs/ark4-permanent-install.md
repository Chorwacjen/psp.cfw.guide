# Flashing ARK-4 with cIPL

::: warning

Make sure your console is charged when following this process. A sudden power loss could result in serious damage.

:::

::: warning

If you previously installed ARK-4 with Infinity, make sure to [revert with chronoswitch](chronoswitch.html) in order to successfully install and avoid bricking. In the
case you already downgraded with Chronoswitch, you can skip this.

:::

## Section I - Extracting files

1. Open the `ARK4.zip` archive.
1. Make sure to connect your PSP or SD/MS card to the PC.
1. Extract the `ARK_cIPL` (found in the `PSP` subdirectory of the archive) to the `/PSP/GAME/` folder on your SD/MS card.
1. Make sure to safely unmount either your PSP or SD/MS card from the PC.

## Section II - Installing ARK-4

1. On your PSP, go to Game.
1. Click on Memory Stick™.
1. Launch the ARK cIPL Flasher.
1. Press the corrisponding accept button to install.
    - For most regions, this is the X button, and for japan, this is the O button.
1. Reboot your PSP to verify whether or not you are still running ARK-4:
    1. Go to Settings > System Settings > System Informationm
    1. After `System Software:`, it should be something like `ARK 4.20.XX cIPL`.

If you followed all the steps correctly, you should have ARK-4 permanently flashed!

::: tip

If you wish to go even further, proceed to [ARK-4 Flash Installation](ark4-flash-install.html)

:::
# razer-blade-15-advanced-2020-hackintosh

This repo is based on this hackintosh: https://github.com/dursonATWIT/Razer-Blade-15-advanced-2020-hackintosh-OpenCore. Please make sure you know what you're doing and follow dortania guide. I've removed the System Serial Number and UUID I used for my laptop so you'll need to generate one for yours.

I'm using macOS Monterey 12.1 on my Razer Blade 15 Advanced 2020. The spec is:
 - Core i7 10875H
 - 16GB RAM
 - nVIDIA RTX 2080 Super MaxQ (disabled in macOS)


Almost everything work, except:
 - Palm rejection.
 - Airdrop.
 - Audio sometimes doesn't work if rebooting from Windows. Shutting down windows and doing a cold boot for macOS gets audio to work 100%.

For external display, I'm using a display link adapter (https://vi.aliexpress.com/item/1005002448484645.html?gatewayAdapt=glo2vnm)

Update: Upgraded to Ventura.
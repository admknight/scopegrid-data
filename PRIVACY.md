# ScopeGrid privacy policy

_Last updated: 25 October 2026 · applies to ScopeGrid for Android and ScopeGrid for Windows, version 1.7.3 and later._

ScopeGrid is made by Scopewise Consulting (Adam Knight), Lahore, Pakistan. Contact: badass.insane@gmail.com.

## In short

ScopeGrid has **no servers of its own**. It does not collect, sell or share anything about you. There are no ads, no analytics and no tracking. Everything ScopeGrid records stays on your own phone or PC.

## What ScopeGrid keeps, and where

| Data | Where it is kept | Who it is sent to |
|---|---|---|
| Your DessMonitor (or SmartESS) username and password, or a captured DessMonitor link | Encrypted on your device (Android Keystore on the phone, Windows DPAPI on the PC) | Only DessMonitor, to read your inverter and to change settings you ask for; and your own paired PC or phone, over the encrypted home-network link |
| Inverter readings, history, alarms, outage times, battery health, control schedules, bills and monthly reports | On your device only | Nobody |
| Your meter readings, tariff and slab rates | On your device only | Your own PC or phone through phone sync, if you pair them |
| The town or coordinates you set for the weather | On your device | Open-Meteo, to get the forecast for that place (no account, no identifier) |
| Published electricity rates | Checked about once a day when your bill follows a ready-made tariff; kept on your device | ScopeGrid's public rates file on GitHub is downloaded (no account, no identifier, nothing about you is sent) |
| Alerts to other phones | Settings on your device; the ntfy token or email password is encrypted | Only the ntfy server or email account you set up yourself |
| Crash details | On your device (Android) or in the app's log folder (Windows) | Nobody, unless you choose to share a report |

## Phone sync

When you pair your phone with your PC, they talk directly over your home network. Every message is encrypted with a key that only those two devices know. Nothing goes through the internet or through ScopeGrid servers, because there aren't any. Paired devices share your settings (bill, place, schedules, warnings) and your DessMonitor login, so whichever device you set up first sets up the other. The login stays encrypted on each device (Android Keystore, Windows DPAPI). Signing out on one device does not sign out the other.

## Camera and location (Android)

- **Camera:** used only while you scan a logger barcode or an equipment label. Images are read on the phone and are never stored or sent.
- **Approximate location:** used only if you tap "Use this phone's location" for the weather forecast. The coordinates are kept on the phone and sent only to Open-Meteo as described above.

## Inverter control

Settings you change, including changes made by your own schedules, are sent only to DessMonitor, which forwards them to your inverter. A record of each change is kept on your device.

## Updates

The GitHub version of ScopeGrid checks ScopeGrid's public release page (github.com/admknight/scopegrid-data) for a newer version. This request carries no personal information. The Google Play version is updated by Google Play.

## Children

ScopeGrid is a tool for managing a home solar system and is not directed at children.

## Your choices

- You can sign out or turn features off at any time in the app's settings.
- Uninstalling ScopeGrid deletes everything it stored on that device.
- Data held by DessMonitor about your account and inverter is covered by DessMonitor's own privacy policy.

## Changes to this policy

Any change will be published at this address, with a new "last updated" date, before the version of the app it applies to is released.

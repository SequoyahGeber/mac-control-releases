# Mac Control

Native monitoring, cooling controls, app audio controls, timers, a Dynamic Island, window tools, and local storage exploration for macOS.

## Download

Download the ZIP from [the latest release](https://github.com/SequoyahGeber/mac-control-releases/releases/latest), extract **Mac Control.app**, and move it to **Applications** before opening it.

Requires macOS 14 or later. Each release declares its supported processor architecture. Privileged fan writes are currently restricted to the supported Mac17,9 model and require approval of the fan service in macOS Login Items & Extensions. Other Macs can use the supported monitoring and utility features.

## In-app updates

Choose **Check for Updates** in Settings, the app menu, or the menu bar. Optional daily checks find compatible releases. You choose when to download and install. Updates verify signed release information and signed archives before extraction. Install and Relaunch closes the app fully, restores automatic cooling and original app audio, and preserves preferences.

The full Developer ID build uses this release feed. **Mac Control Beta** updates separately through TestFlight.

## Repository

This repository distributes compiled builds and release information. Mac Control application source is private and is not stored here. GitHub's automatically generated source archives contain only this distribution repository's public documentation.

The app includes [Sparkle](https://sparkle-project.org/) for updates; its license is included in the application bundle. No analytics or system profiling is enabled.

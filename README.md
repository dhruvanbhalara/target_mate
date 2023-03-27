![Banner](.github/assets/banner.png)

<br/>
<img align="left" alt="android" width="200px" src=".github/assets/text_logo_dark.svg#gh-light-mode-only" />
<img align="left" alt="android" width="200px" src=".github/assets/text_logo.svg#gh-dark-mode-only" />
<br/>
<br/>

A companion app for [Toggl track][toggl] to track & manage your working hours to achieve your monthly goals. If you're using [Toggl Track][toggl] to track your time then, this app can help you manage your monthly working hours.

<a href="https://github.com/BirjuVachhani/target_mate/releases/download/0.4.0/TargetMate-android-0.4.0.apk"><img src=".github/assets/android.png" height="70px" /></a> &nbsp; <a href="https://github.com/BirjuVachhani/target_mate/releases/download/0.4.0/TargetMate-macos-0.4.0.dmg"><img src=".github/assets/macos.png" height="70px" /></a> &nbsp; 
<a href="https://github.com/BirjuVachhani/target_mate/releases/download/0.4.0/TargetMate-windows-0.4.0.msix"><img src=".github/assets/windows.png" height="70px" /></a> 

See [Installation Guide](#installation-guide) for installing on desktop.

# Features

- Supports auth via credentials and API key.
- Custom working days selection to adjust for leaves and holidays.
- Set max monthly hours limit.
- Supports tracking per workspace, per project on [Toggl Track][toggl].
- Auto syncs stats at configurable intervals.
- Beautiful themes to select from.
- Tracks per day average working hours based on already tracked hours.
- Displays today's progress in system tray on desktop.
- Integrates with system tray on desktop for quick controls.
- Notifications support. Shows a notification for daily and monthly achieved goals.
- No analytics, no data collection, no strings attached! Everything stays on your local machine.

## Supported Platforms

| Android | iOS | macOS | Windows | Linux | Web |
|---------|-----|-------|---------|-------|-----|
| ✅       | 🚧   | ✅     | ✅       | 🚧     | ❌   |

### Disclaimer

> This is not an independent timer tracking app. It does not have ability to record your time. You have to use [Toggl Track][toggl] to track your time. This is a companion app to help you track your goals for achieving daily/monthly goals. It also allows you to set a max limit for monthly goal.

## Installation Guide

### MacOS
In order to install Target Mate on MacOS, download the file named `TargetMate-macos-x.x.x.dmg`.

#### Installing with DMG (Recommended)
To install Target Mate in your Mac simply open `TargetMate.dmg` and drag the Toogl Target app to the `Applications` folder next to it. If you are updating the app you'll need to click `Replace`.

1. Open `TargetMate-macos-x.x.x.dmg` and drag the Target Mate app to the `Applications` folder next to it. If you are updating the app you'll need to click `Replace`.
2. Target Mate should now appear in your Laucnhpad. However, if you try to open it you might get a message saying that `"Target Mate" can't be opened because Apple cannot check it for malicious software.`
3. To fix this, open `System Preferences` and click on `Security and Privacy`.
4. you'll see a message saying `"Target Mate" was blocked from use because it is not from an identified developer`.
5. Click on `Open Anyway` and then `Open` in the popup.
6. Done! You should now be able to use Target Mate normally!

### Windows

#### Installing with MSIX (Recommended)

Download the `TargetMate-windows-x.x.x.msix`.

Unfortunately, it isn't as easy as opening the file and installing it as I do not have a signed certificate.

To install Target Mate, 

1. Make sure the installer is not running. 
2. Right-click on the `msix` file and click on Properties.
3. Navigate to `Digital Signatures`. You will see only one signature called 'Birju Vachhani`.
4. Double click on the signature and then click on `View Certificate`.
5. Click on `Install Certificate`.
6. Select `Local System` and click on `Browse` button.
7. Select `Trusted Root Certification Authorities` and click ok.
8. Done! Close any open window by clicking on `ok`. Now you should be able to install `Target Mate` by just double-clicking `msix` file.

## Motivation

I love [Toggl Track][toggl] and I use it daily to track my working hours and generate time sheet at the end of the month. It provides almost all the things I need from a time tracking app except one thing. I usually find my self working on projects that are billed hourly. Sometimes, these projects have a max cap for working hours per month. So to make sure I only work in these constraints, I found myself checking reports on [Toggl Track][toggl] website to see for how many hours I have worked. While [Toggl Track][toggl] shows stats on your tracked time, it doesn't have any knowledge of my monthly limits, or my working days. So I had to calculate how many hours I can work each remaining days to ensure that I don't go overboard. 

Ideally, I'd prefer to have **fixed** working hours each day, however it's not always the case in real world. Some day I'd have more work, so I might work an extra hour or two. Some day I wouldn't have much going on, so I might just work for fewer hours. It's very difficult to control this on daily basis. Another situation I found myself is when I have very flexible deadline and I don't want to work too much in a single day to balance my work life, but I would end up working way more than initially planned simply because I **lose track** of my hourly goal/limit per day to do so (since I can always pick up from where I left next day). This is kind of important for my peace of mind and to make sure that I don't stretch myself too much when I clearly have enough time on upcoming days to finish a given work/task.

I was tired of manually keeping track of my daily and monthly goals and limits to make sure don't work too much and I don't go **overboard** for my monthly working hours limits. Hence, the birth of this **companion** app. 

**This app has only one primary goal:** _Help me visualize my daily and monthly target and goals by doing all the calculations automatically, so I don't have to go through the same tedious task every day! And it does its job perfectly!_ 

## How to get API key from Toggl Track

You can navigate to your [profile](https://track.toggl.com/profile) on [Toggl Track][toggl] to get your access token. Make sure you're logged in!

![api_key](.github/assets/api_key.png)

## Build from source

1. Clone the repo
2. Install dependencies with `flutter pub get`
3. Run app with `flutter run` on supported platforms.

## Contribution

You are most welcome to contribute to this project!

Please have a look at [Contributing Guidelines](https://github.com/BirjuVachhani/adaptive_theme/blob/main/CONTRIBUTING.md), before contributing and proposing a change.

## Liked this app?

Show some love and support by starring the repository. ⭐

Want to support my work?

<a href="https://github.com/sponsors/BirjuVachhani" target="_blank"><img src="https://raw.githubusercontent.com/BirjuVachhani/spider/main/.github/sponsor.png?raw=true" alt="Sponsor Author" style="!important;width: 600px !important;" ></a>

Or You can

<a href="https://www.buymeacoffee.com/birjuvachhani" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-blue.png" alt="Buy Me A Coffee" style="height: 51px !important;width: 217px !important;" ></a>

# Sponsers

<img width="100%" src='https://github.com/BirjuVachhani/target_mate/raw/main/.github/assets/sponsors_light.svg#gh-light-mode-only'/>    
<img width="100%" src='https://github.com/BirjuVachhani/target_mate/raw/main/.github/assets/sponsors_dark.svg#gh-dark-mode-only'/>

[toggl]: https://toggl.com/track/

[![Website](https://github.com/P1etrodev/harakiri-private/actions/workflows/deploy-website.yaml/badge.svg?branch=main)](https://github.com/P1etrodev/harakiri-private/actions/workflows/deploy-website.yaml)

[![Version](https://github.com/P1etrodev/harakiri-private/actions/workflows/deploy-version.yaml/badge.svg?branch=main)](https://github.com/P1etrodev/harakiri-private/actions/workflows/deploy-version.yaml)

# Harakiri: Tango Chat Integration for OBS

![Harakiri Logo](https://harakiri.pro/hk-logo.png)

## Overview

Harakiri is a desktop application designed to integrate the Tango chat into OBS Studio. It allows streamers to display and interact with their Tango chat directly within their OBS scenes.


## Ashigaru: Chrome Extension

[Ashigaru](https://chromewebstore.google.com/detail/ashigaru/gaalemppoajllefmopaphipbenflalln?authuser=0&hl=en) is a Chrome extension that listens to events on Tango and forwards them to the Harakiri application via its local server.

## Key Features
- OBS notifications for gifts, follows, and party invites with custom sounds.
- Countdown clock for Tango Gaming's Happy Hour reset.
- Fully customizable on-screen alerts, messages, and avatars.
- Interactive polls to engage viewers.
- Test events for gifts, messages, and follows.
- Track daily earnings and stream stats in real-time.

## Installation

1. Install [Ashigaru](https://chromewebstore.google.com/detail/ashigaru/gaalemppoajllefmopaphipbenflalln?authuser=0&hl=en) to your browser.
2. We **strongly** recommend the usage of extensions like [DoNotDiscard](https://chromewebstore.google.com/detail/donotdiscard-disable-tab/piohlfbmepkepkoiacedlalbmbkjfphc?hl=en) to prevent suddent disconnections.
3. Download the latest Harakiri release from the the [Harakiri Website](https://harakiri.pro).
4. Follow the installation instructions for your operating system.

## Usage

1. Launch OBS.
2. Go to Tools -> Scripts and add `harakiri.py`.
3. Go to Docks -> Custom Browser Docks.
4. Set the URL to `http://localhost:8765/chat`.
5. Go to Sources and use any of the urls at the right side in Tools -> Scripts -> `harakiri.py`
6. Adjust the width and height to fit your scene.

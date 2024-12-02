[![Join the chat at https://gitter.im/Soundnode/soundnode-app](https://badges.gitter.im/Soundnode/soundnode-app.svg)](https://gitter.im/Soundnode/soundnode-app?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Soundnode App
============

Soundnode App is an Open-Source project to support Soundcloud for desktop Mac, Windows, and Linux. <br>
It's built with Electron, Node.js, Angular.js, and uses the Soundcloud API.

> Be aware that Soundnode relies on Soundcloud API which only allows third party apps to play 15 thousand tracks daily. When the rate limit is reached all users are blocked from playing/streaming tracks. The stream will be re-enable one day after (at the same time) streams were blocked.

![alt tag](https://raw.githubusercontent.com/Soundnode/soundnode-app/master/Soundnode-app.png)

## Features

- No need to install
- Native media keyboard shortcuts
- Search for new songs
- Easy navigation
- Listen to songs from your Stream, Likes, Tracks, Following or Playlists
- Like songs and save to your liked playlist
- Full playlist feature
- Follow/Unfollow users

And much more!

## Configuration

Since soundcloud applies a rate limit to third party apps, you need to configure your own API key to make soundnode work.

* Login to soundcloud.com on favorite browser
* Look for an api call and write down the client_id parameter
![dev tools](doc/img/dev_tools.png)
* Edit your userConfig.json file (see here for location : https://github.com/eliecharra/soundnode-app/blob/master/app/public/js/common/configLocation.js#L34) and update clientId parameter with the previously retrieved one.

## How to contribute

First, building, testing, and reporting bugs is highly appreciated. Please include the console's output and steps to reproduce the problem in your bug report, if possible.

If you want to develop, you can look at the issues, especially the bugs, and then fix them.
Here's a [list of issues](https://github.com/Soundnode/soundnode-app/issues?state=open).

## Development

See the [Development page](https://github.com/Soundnode/soundnode-app/wiki/Development) for a complete guide on how to build
the app locally on your computer.

## Supported Platforms

- Windows
- Mac
- Linux

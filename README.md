# Xbox-xCloud-Client

xbox-xcloud-client is an open-source client for Xbox home streaming made in Javascript and Typescript.

_DISCLAIMER: Xbox-xCloud-Client is not affiliated with Microsoft or Xbox._

## Features

- Stream video and audio from the Xbox One and Xbox Series
- Support for gamepad controls
- Keyboard controls
- Build-in online friendslist

## Install

You can either compile the project yourself or download the (unsigned) executable from the [releases](https://github.com/unknownskl/xbox-xcloud-client/releases) page

## Local Development

Clone the repository:

    git clone https://github.com/unknownskl/xbox-xcloud-client.git
    cd xbox-xcloud-client

Install dependencies:

    npm ci

Run development build:

    npm start

## Known Issues

- Audio can get distorted when the audio is delayed or gets out of sync. This should recover within 3 seconds. You can also manually press `0` on your keyboard to reset the audio timings.

## Changelog

See [changelog](CHANGELOG.md)
# vr-headless-demo

## A demonstration of a VR experience with content managed in Magnolia CMS.


## Features

Uses AFRAME to create a VR experience with content from the Magnolia Stories App.

Uses the delivery endpoint: https://documentation.magnolia-cms.com/display/DOCS56/Delivery+endpoint+API

## Usage

Note that this version is compatible with Magnolia version 5.7 & 6.0

The files in the `vr-stories` directory are the full VR experience which can be run on any http server.

The `vr-stories-lm` directory is a Magnolia `Light Module` which provisions the REST endpoint
that the client expects.
To use it on your own Magnolia instance, just drop `vr-stories-lm` into your instances resources directory -usually named `modules` or `light-modules`. You'll need the Magnolia Travel Demo installed.

## Information on Magnolia CMS
https://documentation.magnolia-cms.com

## License

MIT

## Contributors

Magnolia, https://magnolia-cms.com

Christopher Zimmermann, @topherzee

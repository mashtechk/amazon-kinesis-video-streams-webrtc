# Amazon Kinesis Video Streams WebRTC SDK for JavaScript

[![NPM version](https://img.shields.io/npm/v/amazon-kinesis-video-streams-webrtc.svg)](https://www.npmjs.com/package/amazon-kinesis-video-streams-webrtc)
[![NPM downloads](https://img.shields.io/npm/dm/amazon-kinesis-video-streams-webrtc.svg)](https://www.npmjs.com/package/amazon-kinesis-video-streams-webrtc)

[![Build Status](https://travis-ci.org/awslabs/amazon-kinesis-video-streams-webrtc-sdk-js.svg?branch=master)](https://travis-ci.org/awslabs/amazon-kinesis-video-streams-webrtc-sdk-js)
[![Coverage Status](https://codecov.io/gh/awslabs/amazon-kinesis-video-streams-webrtc-sdk-js/branch/master/graph/badge.svg)](https://codecov.io/gh/awslabs/amazon-kinesis-video-streams-webrtc-sdk-js)
[![Known Vulnerabilities](https://snyk.io/test/github/awslabs/amazon-kinesis-video-streams-webrtc-sdk-js/badge.svg?targetFile=package.json)](https://snyk.io/test/github/awslabs/amazon-kinesis-video-streams-webrtc-sdk-js?targetFile=package.json)

## Running WebRTC Test Page
NodeJS version 8+ is required.

1. Run `npm install` to download dependencies.
1. Run `npm run develop` to run the webserver.
1. Open the WebRTC test page at `http://localhost:3001`

You will need to provide an AWS region, AWS credentials, and a Channel Name.

The source code for the test page is in the [`examples`](examples) directory.

## Using the SDK
To use the SDK in your own project, you need to import the following:
1. The AWS JS SDK with `AWS.KinesisVideo` and `AWS.KinesisVideoSignaling` clients and `AWS.util`. 
A build with these clients is located at [`examples/aws-sdk.min.js`](examples/aws-sdk.min.js)
1. This KVS WebRTC SDK with the `KVSWebRTC.SignalingClient`. Builds are available in the [`dist`](dist) directory.

Documentation for the KVS WebRTC SDK Signaling Client can be found [here](dist/commonjs/SignalingClient.d.ts).
See the test page for a complete usage example.

## License

This project is licensed under the Apache-2.0 License.


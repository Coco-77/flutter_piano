# flutter_piano

A Crossplatform Midi Piano built with Flutter.

This application runs on both iOS and Android. This uses a custom CrossPlatform Midi Synth I built for Flutter a Flutter plugin that uses .SF2 sound font files located in the assets folder that can pointed to in the pubspec.yaml.

## Getting Started

This application only runs in landscape mode, orientation is set in the AndroidManifest.xml and in the Runner.xcworspace settings.

Make sure to turn your volume up and unmute the phone if possible, the application will try to unmute the device but it can be overriden.

## Configuration

Optionally the key width can be changed in the settings for adjusting for densitity.

The key labels can also be turned off if you want a more minimal look.

You can change the Piano.sf2 file to any sound font file for playing different instruments. 

Total Dart Code Size: 5039 bytes
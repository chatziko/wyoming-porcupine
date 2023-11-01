# Wyoming Porcupine

[Wyoming protocol](https://github.com/rhasspy/wyoming) server for the [porcupine](https://github.com/Picovoice/porcupine) wake word detection system.

This is an experimental fork of [rhasspy/wyoming-porcupine1](https://github.com/rhasspy/wyoming-porcupine1) that uses
the latest version (v3.0) of porcupine.

Advantages of v3 compared to v1:
- Improved accuracy
- More supported languages and pre-trained wake words
- Ability to use custom wake words

Drawbacks:
- An access token from console.picovoice.ai is needed
- Each token can be used on only 3 machines per month

## Home Assistant Add-on

[![Show add-on](https://my.home-assistant.io/badges/supervisor_addon.svg)](https://my.home-assistant.io/redirect/supervisor_addon/?addon=9f80aae6_porcupine&repository_url=https%3A%2F%2Fgithub.com%2Fchatziko%2Fhassio-addons)

[Source](https://github.com/chatziko/hassio-addons/tree/main/porcupine)


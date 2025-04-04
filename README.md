© Juhász Bence
Minden jog fenntartva

# Forcing higher sample rate (filter cuts too low at 44.1)

 ```
2024-10-21 16:15:57 pw-metadata -n settings 0 clock.force-rate 96000
2024-10-21 16:15:53 pw-metadata -n settings 0 bluez5.default.rate = 96000
2024-10-21 16:15:48 pw-metadata -n settings 0 audio.rate 96000
2024-10-20 20:23:23 pw-metadata -n settings 0 clock.rate 96000
```

1. start stream on internal sound card, should be 96khz
2. turn on bt device, should switch to it automatically, keeping the stream format

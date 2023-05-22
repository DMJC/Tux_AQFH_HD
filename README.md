# Tux: A Quest for Vengeance!
This repository is for my Art fixes/improvements to Tux: A Quest for Herring.
I'd like to modernise Tux: A Quest for Herring and improve some of the texturing and art detailing. All credit to Steve and Oliver Baker for making the original game.

## Development Platform:
Debian Linux 12.0 Bookworm

## Dependancies:
libplib-dev, libplib1

## Known Issues:
- No Pipewire/PulseAudio/Alsa Support.
- modprobe snd-pcm-oss for audio on Linux (ALSA to OSS Wrapper). You might need to ln -s /dev/dsp1 /dev/dsp to get sound working. The game is expecting /dev/dsp as the sound device.

## To Do:
- Modernise Audio Code

## Media
![Screenshot](https://github.com/DMJC/Tux_AQFH_HD/blob/main/doc/snap2tb.png?raw=true)

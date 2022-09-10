# pw-loopback-memo

## quick info
tldr pw-loopback

## get sink id under node name
wpctl status

## loopback with -C sinkid
pw-loopback -m '[[FL FR]]' -C alsa_input.pci-0000_0f_00.4.analog-stereo --playback-props='[media.class=Audio/Source]'

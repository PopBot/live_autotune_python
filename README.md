# Python Live Autotune

> Live autotune microphone input for Python

## Requirements

```shell
brew install portaudio
brew install libav
brew instal ffmpeg
```

> Note: If your PortAudio installation is through Homebrew, you will need to direct pip to the path to install a package requirement (pyaudio), so run
> the following: ```pip install --global-option='build_ext' --global-option="-I$(brew --prefix)/include" --global-option="-L$(brew --prefix)/lib" pyaudio```
> to properly install pyaudio.
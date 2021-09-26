# Recaptcha v2 solver

A simple program to bypass recaptcha version 2 using the audio verification method.

This program only demonstrates how to bypass recaptcha on https://www.google.com/recaptcha/api2/demo

You will need to adapt this program to work on other websites. This should serve as a base repository that you can modify to meet your needs.

## OS support

1. Windows
2. MacOS (non ARM architecture) is possible, but an emphasis is placed on Windows given that `ffmpeg` doesn't and won't be supporting ARM architecture

## Dependencies

1. selenium
2. pydub
3. speech recognition
4. ffmpeg
5. ffmpy

## Usage

```
python recaptcha_solver.py
```

## Common errors

> NameError: name 'sample_audio' is not defined

Try installing ffmpeg manually, http://blog.gregzaal.com/how-to-install-ffmpeg-on-windows/

## Original Source

The code in this repository was heavily borrowed and inspired by this [blog post](https://ohyicong.medium.com/how-to-bypass-recaptcha-with-python-1d77a87a00d7) and [repository](https://github.com/ohyicong/recaptcha_v2_solver) by [@ohyicong](https://github.com/ohyicong)

# Fourier Transform

## Description

A simple Jupyter notebook script for visualizing the signal and frequencies of any audio file pulled from YouTube. <br>
It also has the capability to amplify or suppress certain frequencies after which it can visualise the resulting signal and save it into a wav file.

## Dependencies

Numpy <br>
Scipy <br>
Pytube <br>
Matploblib <br>

## Issues

The resulting wav file is handled weirdly by some programs. For example using Apple Music results in extremely loud noise compared to the input, whereas for other programs noise level is normal. This may be a result of the created wav files lacking tags or attributes that were present in the input file.

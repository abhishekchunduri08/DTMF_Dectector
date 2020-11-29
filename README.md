# DTMF_Detector
Using Matlab to simulate Dual-Tone Multi-Frequency (DTMF) of telephone

# Program Structure :
## Main.m
```
DTMF_tone_generator.m
```
> * button_0 ~ 9
> * button_A ~ D
> * button_Sign, button_Star

* Dual-Tone_multifrequency_generator

```
button_SoundAll.m
```
* Generate a Tone_file.wav
```
button_Decode.m
```
* Read Tone_file.wav & Decode
* Goertzel algorithm :


| DTMF Frequency (Hz) | Frequency Bin : k |
|:-------------------:|:-----------------:|
| 697                 | 18                |
| 770                 | 20                |
| 852                 | 22                |
| 941                 | 24                |
| 1209                | 31                |
| 1336                | 34                |
| 1477                | 38                |
| 1633                | 42                |


```
button_Clear.m
```
* Clear all windows

# Program GUI :



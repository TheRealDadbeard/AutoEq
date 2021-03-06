# Sony MDR-XB950N1

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 -7.4; 23 -7.5; 25 -7.7; 28 -7.8; 31 -7.8; 34 -7.7; 37 -7.6; 41 -7.5; 45 -7.3; 49 -7.1; 54 -7.0; 60 -6.9; 66 -6.9; 72 -7.0; 79 -7.3; 87 -7.7; 96 -8.1; 106 -8.3; 116 -8.2; 128 -7.9; 141 -7.3; 155 -6.7; 170 -6.0; 187 -5.1; 206 -4.0; 227 -2.7; 249 -1.4; 274 -0.1; 302 1.0; 332 1.6; 365 1.6; 402 1.3; 442 0.8; 486 0.3; 535 0.0; 588 -0.1; 647 -0.1; 712 -0.0; 783 0.0; 861 0.1; 947 0.0; 1042 -0.0; 1146 -0.2; 1261 -0.3; 1387 0.1; 1526 0.3; 1678 0.4; 1846 0.7; 2031 1.7; 2234 3.4; 2457 5.2; 2703 6.0; 2973 6.0; 3270 6.0; 3597 6.0; 3957 6.0; 4353 6.0; 4788 4.6; 5267 6.0; 5793 6.0; 6373 5.5; 7010 2.5; 7711 0.3; 8482 0.0
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Sony MDR-XB950N1 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sony MDR-XB950N1 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.6dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.9dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 25 Hz   | 0.69 | -6.5 dB |
| Peaking | 129 Hz  | 0.46 | -8.0 dB |
| Peaking | 315 Hz  | 1.24 | 5.7 dB  |
| Peaking | 3224 Hz | 1.45 | 6.5 dB  |
| Peaking | 5690 Hz | 2.83 | 5.0 dB  |
| Peaking | 1900 Hz | 1.49 | -1.4 dB |
| Peaking | 2478 Hz | 3.21 | 2.4 dB  |
| Peaking | 3188 Hz | 3.91 | -1.2 dB |
| Peaking | 4229 Hz | 5.93 | 1.4 dB  |
| Peaking | 8348 Hz | 3.66 | -1.3 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/rtings/rtings/Sony%20MDR-XB950N1/Sony%20MDR-XB950N1.png)
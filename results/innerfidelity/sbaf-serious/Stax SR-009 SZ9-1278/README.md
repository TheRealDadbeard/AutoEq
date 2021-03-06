# Stax SR-009 SZ9-1278

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 0.0; 23 6.0; 25 6.0; 28 6.0; 31 6.0; 34 6.0; 37 6.0; 41 6.0; 45 6.0; 49 6.0; 54 6.0; 60 5.0; 66 4.5; 72 4.9; 79 5.0; 87 4.8; 96 4.5; 106 4.4; 116 4.2; 128 3.9; 141 3.8; 155 3.6; 170 3.3; 187 3.3; 206 3.1; 227 3.1; 249 3.0; 274 3.0; 302 2.9; 332 2.9; 365 2.8; 402 2.7; 442 2.6; 486 2.1; 535 2.0; 588 2.1; 647 1.9; 712 1.5; 783 1.6; 861 1.5; 947 0.6; 1042 0.0; 1146 -0.1; 1261 -0.1; 1387 -0.2; 1526 -0.1; 1678 -0.4; 1846 1.3; 2031 2.8; 2234 3.2; 2457 4.1; 2703 4.1; 2973 3.4; 3270 3.3; 3597 4.1; 3957 2.8; 4353 1.4; 4788 -0.2; 5267 2.6; 5793 6.0; 6373 5.4; 7010 2.4; 7711 0.3; 8482 0.0
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Stax SR-009 SZ9-1278 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Stax SR-009 SZ9-1278 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.9dB** and build filters manually
with these parameters. The first 4 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.9dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 17 Hz   | 0.05 | 5.2 dB  |
| Peaking | 3209 Hz | 1.3  | 5.4 dB  |
| Peaking | 5181 Hz | 1.32 | -5.2 dB |
| Peaking | 5971 Hz | 3.17 | 9.9 dB  |
| Peaking | 33 Hz   | 0.87 | 1.0 dB  |
| Peaking | 178 Hz  | 0.66 | -1.1 dB |
| Peaking | 968 Hz  | 0.31 | 1.7 dB  |
| Peaking | 1624 Hz | 0.85 | -3.5 dB |
| Peaking | 2166 Hz | 2.78 | 2.8 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Stax%20SR-009%20SZ9-1278/Stax%20SR-009%20SZ9-1278.png)
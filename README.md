# Seeed mgc3130 fro python
Microchip’s MGC3X30 are 3D gesture recognition and motion tracking controller chips based on Microchip’s patented GestIC technology.They enable user command input with natural hand and finger movements.  

***  

## Usage

Plugin the module,check the module detection by :
```
i2cdetect -y 1
```
The i2c address of seeed mgc3x30 is **0x68**.

***  

Then , run the application:
```
    ./flick-demo

```
or 

```
    ./flick-snail
```


## reference
**This library is based on [pySupply/Flick](https://github.com/PiSupply/Flick).**  

Because of the hardware deferences,We have made many modifications and cuts,And retain the original license.


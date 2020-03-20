# MN Dust Kit Package
This MN Dust Measurement Kit package was developed by Minnie with assistance from Devicemart.

MN Dust Measurement Kit is a small measure of fine dust. It measures the dust in the surrounding air. And mark the status with facial expressions and traffic lights.
If you Press A button, to see the dust value.

When the air is clean, a smile and a green light. When the air is normal, a blank expression and a yellow light. When the air is bad, the devil's face and the red light. It So Cute!!

<img src="https://blogfiles.pstatic.net/MjAyMDAzMjBfMjY5/MDAxNTg0NjgyNDg4MzA2.Fvmdz0sHoCWtDddgq0521DqDbU9fDJahBM1UYJ6GE8kg.yPhVd_ialyJNzNJ8qXEByThayRESPwPmZqLsvVOOc7kg.PNG.no1_devicemart/icon.png?type=w1" width="400px" style="margin-left: auto; margin-right: auto; display: block;"></img>

(Product Page : http://www.devicemart.co.kr/goods/view?no=12391833)

(Blog Post : https://blog.naver.com/no1_devicemart/221789742690)


## Basic usage

```JavaScript
// set dust sensor
    pins.digitalWritePin(DigitalPin.P1, 0)
    control.waitMicros(280)
    DustVal = pins.analogReadPin(AnalogPin.P0)
    control.waitMicros(40)
    pins.digitalWritePin(DigitalPin.P1, 1)
    control.waitMicros(9680)
    
// show dust sensor value
    basic.showNumber(Dust)
```

## Supported targets

* for PXT/microbit

## License

MIT



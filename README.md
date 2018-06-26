# E-stop Notes

## [Wireless e-stop][1]  
Interlock:
![](https://github.com/EE3-DTPRJ-Robot-Intelligence/Estop/blob/master/relay.png)


Connect jumper pin 1 and 2.
Relay: press one button is ON, press another button is OFF.


## Connection of wireless e-stop and e-stop
Power line → buck (12V output) → (+(yellow) -(grey)) of wireless e-stop  
mbed signal (red) → e-stop (pink) → wireless e-stop → mbed signal (black)  

The following circuit diagram is shown below.  
![](https://github.com/EE3-DTPRJ-Robot-Intelligence/Estop/blob/master/relay_c.PNG)



[1]:https://www.amazon.com/gp/product/B01CCSG2ZY/?keywords=12V%20Remote%20Control&tag=insma-website-20&linkId=b0e08b9ae0a8ab2ca6e018cfcd735b6b

## Reference
* https://www.amazon.com/gp/product/B01CCSG2ZY/?keywords=12V%20Remote%20Control&tag=insma-website-20&linkId=b0e08b9ae0a8ab2ca6e018cfcd735b6b


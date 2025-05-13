#This project will realize led light on/off in stm32

hardware && software init by CubeMX

If we want to control led light on/off at set intervals, we need do following step
0.Enable GPIO(Because this module default close for reduce power consumption)
1.Connect to PIN
2.Config PIN to output
3.Control output level high/low at set intervals

0~2 Can do by config CubeMX
3 I insert business logic

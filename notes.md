# Helicopter Swash Notes:

## Naming convention:
![alt text](naming.png "Naming Convention Swash Plates")

Front:

    CCW
Back:

    CW
## Trims:

Back:

    Servo 3: 1550
    Servo 2: 1550
    Servo 1: 1550
Front:
    
    Servo 1: 1530
    Servo 3: 1500
    Servo 2: 1530 


## Ardupilot Parameter Mapping:

    Front:

        Servo 1: Motor 1, Servo1
        Servo 2: Motor 2, Servo2
        Servo 3: Motor 3, Servo 3
        Front ESC: Motor 7, HeliRSC (Servo 7)
    
    Back:
        Servo 1: Motor 4, Servo4
        Servo 2: Motor 5, Servo5
        Servo 3: Motor 5, Servo6
        Back ESC: Motor 8, HeliTailRSC (Servo 8)


### Ardupilot Servo Function Reference:

    0	Disabled
    31	HeliRSC
    32	HeliTailRSC
    33	Motor1
    34	Motor2
    35	Motor3
    36	Motor4
    37	Motor5
    38	Motor6
    39	Motor7
    40	Motor8
ardu
## Ardupilot Parameters to set

FRAME_CLASS 11
H_DUAL_MODE 0
H_SW_TYPE 3
H_SW_COL_DIR 0
H_SW2_TYPE 3
H_SW_COL_DIR 0

SERVO1_FUNCTION 33
SERVO2_FUNCTION 34
SERVO3_FUNCTION 35

SERVO4_FUNCTION 36
SERVO5_FUNCTION 37
SERVO6_FUNCTION 38

SERVO7_FUNCTION 31
SERVO8_FUNCTION 31
# uCarKey
smart car key 

uses the CC1350 uC from TI to implement a smart car key 

implements a variation of the car key RF protocol (433 Mhz )  

RF frames include button information, battery status, rolling code and encrypted part (AES) 

in parallel, Ble is used to pair the key to a smart phone 

this allows additional functions like controlling car lights or air conditioning, that are not possible using simple buttons.

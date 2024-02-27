# M480BSP_CAN_TX_RX_REMOTE
 M480BSP_CAN_TX_RX_REMOTE


udpate @ 2024/02/27

1. simple M480 CAN TX , RX sample code 

2. on M487_LV2_Advance_Board , CAN transceiver PIN#8 , need to pull down (by GPIO output low or pull down)

refer to CAN_RS_PIN_Init

3. system cock should use XTAL for CAN clock initial correctly

4. power on will send TX normal frame and remote frame

![image](https://github.com/released/M480BSP_CAN_TX_RX_REMOTE/blob/main/CAN_TX_normal_remote.jpg)

press digit 2 , will send CAN TX normal frame

![image](https://github.com/released/M480BSP_CAN_TX_RX_REMOTE/blob/main/CAN_TX_normal_remote_digit2.jpg)

5. with PCAN tool , test different ID CAN receive 

![image](https://github.com/released/M480BSP_CAN_TX_RX_REMOTE/blob/main/CAN_RX.jpg)


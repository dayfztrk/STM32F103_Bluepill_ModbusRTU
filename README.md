# STM32F103_Bluepill_ModbusRTU
STM32F103_Bluepill_ModbusRTU
Written by TAYFUN OZTURK

MODBUS RTU (slave) protocol can be communicated from 3 different UART channels. (USART1,USART2,USART3). (115200/8N1 @all uarts)
In this code, RS485 channel tied to USART3. RS232 channel tied to USART2. 
RS485 enable pins are not tied. So, You can write code where it is in the annotated comment line.
RX is in INT mode, TX is in Polling Mode.
Modbus table is defined in typedef struct such as class. You can expend the paramenters (registers).


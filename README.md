# DMA 方式串口收发

1. 什么是DMA

2. 软件配置
3. 相关函数

DMA 方式串口发送函数：

```c
HAL_StatusTypeDef HAL_UART_Transmit_DMA(UART_HandleTypeDef* huart, uint8_t* pData, uint16_t Size);
```

该函数一共有三个参数
参数类型和中断串口发送函数一样。

DMA方式串口接收函数：

``` c
HAL_StatusTypeDef HAL_UART_Receive_DMA(UART_HandleTypeDef* huart, uint8_t* pData, uint16_t Size);
```

该函数一共有三个参数
参数类型和中断类型串口发送函数一样。

4. 代码编写


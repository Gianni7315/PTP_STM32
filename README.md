My main goal of this project is to establish a connection between the STM32 H743ZI Nucleo development board and my computer through Ethernet connection. Then establish PTP. As well, I want the PTPD timers to update every 1ms and print results to the console.
Stole a lot of the code from https://github.com/hasseb/stm32h7_atsame70_ptpd, although I received a few error messages in regards to the _gettimeofday function, so I added an additional file to return 0.

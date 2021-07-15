# stm32-sd-spi
Minimum example project showing how to interface SD card over SPI for the STM32L452RE microcontroller.

Although STM32CubeMX generally does a good job in simplifying most of the hazzle with setting up STM32 microcontrollers for interfacing various types software and hardware, when it comes to interfacing SD-cards, it requires quite a lot of work.

First, I made an attempt to use STM32CubeMX for configuring the SDMMC peripheral which is built for high-speed SD card interfacing. But for some reason, the code stalls and I have not spent too much time in trying to get it to work.

Luckily, https://github.com/kiwih/cubeide-sd-card have done a good job in simplifying the process of interfacing SD cards over SPI and I have simply followed his guide with success.

He even has a blog post that thoroughly explains how to use it https://01001000.xyz/2020-08-09-Tutorial-STM32CubeIDE-SD-card/.
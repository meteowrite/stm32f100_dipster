# Yet another STM32F100 Board

Simple board to ease the work with STM32F100 LQFP64 devices that I have laying around.
Pitch between SIL headers is multiple of 2.54, making it suitable for breadboarding as well. 

# Features

- Reset Push button
- Boot configuration (Flash/System ROM) DIP switch 
- PD2 routed to DIP switch as well
- XTAL provision
- Hardwired USART1 and SWD headers
- Mounting holes
- Minimalistic patch/prototype area (visible as pin headers in the 3D)

![Alt text](/images/stm32f100_dipster_pcb.png?raw=true "3D PCB View")

# What is missing

- No LED indicator, not even for power indication

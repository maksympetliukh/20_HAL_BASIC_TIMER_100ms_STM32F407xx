# Basic Timer 100 ms

### What this project is
This project is created to learn what the basic timer is and how it works. Learn how to
run it with System Clock and how to configure it for different tasks.
This project is developed accordingly to online course [Mastering Microcontroller: Timers, PWM, CAN, Low Power(MCU2)](https://www.udemy.com/course/microcontroller-programming-stm32-timers-pwm-can-bus-protocol/learn) 
by Kiran Nayak (FastBit Embedded Brain Academy).

### What actually this program does 
- set up System Clock
- configure peripheral buses clocks
- set up required basic timer (TIM6)
- configure its parameters (Prescaler, Period)
- configure IRQ
- run 100ms signal over GPIO pin to allow us to measure whether it correct or not (PulseView + Sealae LA)

### Used devices
- MCU: **STM32F407VET6**
- CPU: **ARM Cortex-M4**
- Debugger: **WeAct 1.0**
- Logic Analyzer: **Sealae 8-channel clone**

### Used software and documentation
- Programming language: **C**
- Implementation: **HAL**
- IDE: **CLion**
- STM32 Project editor: **STM32CubeMX**
- Reference Manual: **RM0090**
- Logic Analyzer Tool: **PulseView**
# bare-metal-stm32-sensor-uart
Bare-metal STM32 firmware, no HAL/Arduino: direct register access for GPIO LED blink, ADC sensor read with real-value conversion, and UART text output to a serial terminal. Pure C, datasheet-driven — `*(volatile uint32_t*)0x40020014` style. Learn what's under the abstraction.

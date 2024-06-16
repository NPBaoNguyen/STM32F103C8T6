# Display-LCD-16x02-using-I2C-module-for-STM32F103C8T6
// LCD library referenced from Khue Nguyen Creator
// Configuration
1. HCLK f = 72MHz
2. Timer 2:
   - Prescaler: 72-1
   - Counter Period: 0xffff-1
4. GPIO:
   - PB6 - SCL
   - PB7 - SDA
6. I2C1

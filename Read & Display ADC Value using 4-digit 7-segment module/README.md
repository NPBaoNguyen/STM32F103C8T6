# Read-Display-ADC-values-no-interupt-using-4-digit-7-segment-LED
// Module LED Common-Cathode 5641AS
// Configuration
1. HCLK f = 36MHz
2. ADC1: IN0 (PA0)
  - Continous Conversion: Enable
  - Enable Regular Conversion: Enable
  - Number of Conversion: 1
  - Rank: 1
  - Channel: 0
  - Sampling Time: 1.5 Cycles
3. Timer 2:
  - Prescaler: 36-1
  - Counter Period: 0xffff-1
4. GPIO: Output
  * a - PC13
  * b - PA1
  * c - PA2
  * d - PA3
  * e - PA4
  * f - PA5
  * g - PA6
  * D1 - PA7
  * D2 - PB0
  * D3 - PB1
  * D4 - PA10

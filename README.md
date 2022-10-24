# iCEStamp

iCEStamp. Tiny FPGA core module based on iCE40LP1K-CM36 (iCEStamp1K) and iCE40UL1K-CM36 (iCEStampUL1K). Inspired by postage stamp, with the physical size of just 17.78 * 17.78 * 3.50 mm!

Specification
=

## iCEStamp1k
- FPGA : iCE40LP1K CM36
    - Logic Cells : 1280 cells
    - Block RAM : RAM4K * 16 (64kBits  or 8kBytes)
    - 25 I/O pins
    - Sadly no DSP block and PLL Block
    - Requires external clock/oscillator
    - x1 SPI Hardened IP
- IO Supply voltage : 2v5 to 3v3
- On board 1v2 regulator for core voltage

## iCEStampUL1K
- FPGA : iCE40UL1K CM36
    - Logic Cells : 1248 cells
    - Block RAM : RAM4K * 14 (56kBits or 7kBytes)
    - 26 I/O pins included High current sink for IR and RGB led
    - Internal 48Mhz HF oscillator and 10kHz LF oscillator
    - PLL block included 
    - x2 I2C Hardened IP
    - x1 IR TX/RX Hardened IP
    - x1 RGB PWM Hardened IP
- IO Supply voltage : 2v5 to 3v3
- On board 1v2 regulator for core voltage
# Pseudocode – Hydroelectric Energy Logger

## Goal
Log voltage and RPM of a small hydro generator and estimate power output over time.

## Flow
- [ ] Read voltage every second (ADC)
- [ ] Read RPM using hall sensor + timer interrupts
- [ ] Calculate power = V × I (use estimated load resistance if I not measured)
- [ ] Log to CSV on SD card: timestamp, V, RPM, power
- [ ] Add OLED display for live stats

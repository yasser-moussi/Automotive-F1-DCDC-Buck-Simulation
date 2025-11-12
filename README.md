# Automotive F1 DCDC Buck Converter Simulation

A professional MATLAB/Simulink implementation of a 400V-to-28V Buck Converter for F1 hybrid power systems.

![BMS Dashboard](https://img.shields.io/badge/Simulink-R2025a-blue.svg)
![BMS](https://img.shields.io/badge/Battery-Management_System-yellow.svg)
![Automotive](https://img.shields.io/badge/Automotive-Engineering-red.svg)

## 🚀 Features

- **High-Voltage Step-Down** - 400V input to 28V output with precise PWM control
- **Low Ripple Filtering** - Inductor/capacitor design for <1% voltage ripple
- **Switching Efficiency** - Ideal switch/diode model at 100 kHz frequency
- **Real-Time Monitoring** - Voltage/current scopes for transient analysis
- **Scalable Parameters** - Adjustable duty cycle and components for F1 loads
- **Loss Compensation** - Tuned for diode/switch drops in automotive conditions

## 📊 System Performance

| Metric | Value | Industry Standard |
|--------|-------|-------------------|
| Output Voltage Accuracy | ±0.2V | ±1V |
| Voltage Ripple | <0.5V | <1V |
| Switching Frequency | 100 kHz | 50-200 kHz |
| Efficiency | >95% | >90% |



MetricValueIndustry StandardOutput Voltage Accuracy±0.2V±1VVoltage Ripple<0.5V<1VSwitching Frequency100 kHz50-200 kHzEfficiency>95%>90%

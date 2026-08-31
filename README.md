# Current Buffer Compensated Op-Amp

## About the Project

This project is about the design and simulation of a Current Buffer Compensated Op-Amp at transistor level.

The circuit was designed in Cadence Virtuoso and different simulations were performed to check its gain, bandwidth, phase margin, slew rate, output swing and power consumption.

The main aim was to design an Op-Amp which gives good gain and stability while keeping the power consumption low.

## Circuit Blocks

The Op-Amp consists of the following main sections:

- Differential Input Stage
- Current Buffer Stage
- Output Stage
- Bias Network

The differential input stage takes the input signal and provides the initial amplification. The current buffer stage is used between the input and output sections, while the output stage provides the required output drive. The bias network provides the required bias currents to the circuit.

## Design and Simulation

The complete circuit was implemented at transistor level using Cadence Virtuoso.

The following analyses were performed:

- DC Operating Point Analysis
- AC Analysis
- Transient Analysis
- Slew Rate Analysis
- Output Voltage Swing Analysis
- Power Consumption Analysis
- Hybrid-π Model Simulation

## Results

The main simulation results are:

| Parameter | Result |
|---|---:|
| DC Gain | 85.3 dB |
| Unity Gain Frequency | 22.3 MHz |
| Phase Margin | 60.6° |
| Positive Slew Rate | 32.4 V/µs |
| Negative Slew Rate | 9.28 V/µs |
| Total Slew Rate | 20.84 V/µs |
| Output Voltage Range | 0.146 V – 1.8 V |
| Power Dissipation | 190 µW |

The achieved results satisfy the main design requirements of the project. :contentReference[oaicite:0]{index=0}

## Hybrid-π Model

The circuit was also checked using a Hybrid-π model.

The obtained results were:

- GBW = 25.61 MHz
- Phase Margin = 63.83°

This was used to further check the frequency response of the designed amplifier. :contentReference[oaicite:1]{index=1}

## Software Used

- Cadence Virtuoso
- Analog Design Environment
- CMOS Transistor-Level Simulation

Project Outcome

The project helped in understanding transistor-level analog circuit design, current buffer compensation, frequency response, stability, slew rate and power analysis.

The final design achieved a DC gain of 85.3 dB with 22.3 MHz unity-gain bandwidth and 60.6° phase margin. The total measured slew rate was 20.84 V/µs with around 190 µW power dissipation.

Author

Prince Kumar

M.Tech – Communication Engineering
IIT Guwahati

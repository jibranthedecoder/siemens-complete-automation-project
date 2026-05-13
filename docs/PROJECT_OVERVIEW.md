# Chemical Process Automation System

This repository contains a complete Siemens automation learning project that follows the engineering workflow from P&ID interpretation to functional specification, hardware selection, PLC programming, HMI implementation, and simulation.

The project represents an industrial chemical mixing and dosing process. The automation system is based on Siemens S7-1500, TIA Portal V16, Siemens GRAPH, WinCC Basic HMI, PLCSIM Advanced, and SIMIT.

## Project phases

1. Functional specification from P&ID
2. Siemens S7-1500 hardware and I/O configuration
3. PLC, HMI, GRAPH sequence, PID, and simulation implementation

## Process scope

The simulated process prepares a chemical solution using water, NaOH, and powder dosing. The process includes filling, chemical dosing, powder feeding, mixing, transfer to storage, and controlled dosing to the next process stage.

## Automation scope

The PLC software uses a modular architecture with reusable blocks for motors, valves, sensor scaling, HMI handling, automatic/manual mode handling, fault logic, emergency stop logic, test mode, PID flow control, and the main GRAPH process sequence.

## Repository structure

- `README.md` — public project presentation
- `docs/` — documentation, architecture notes, and LinkedIn descriptions
- `tia-portal/` — intended location for TIA Portal archive files such as `.zap16`
- `reports/` — intended location for exported PDF reports
- `simulation/` — intended location for SIMIT/PLCSIM screenshots or simulation notes
- `media/` — intended location for screenshots used on GitHub, LinkedIn, or portfolio pages

## Note

Binary engineering files such as `.zap16`, PDF exports, and videos should be uploaded manually if the GitHub connector cannot transfer uploaded binary files directly.
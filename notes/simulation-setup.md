# Simulation Setup

## Program Description
- Computes Maclaurin series for sin(x)
- User inputs angle in degrees and number of terms

## Compilation
- Windows: g95 mlsin.f90 -o mlsin.exe
- Linux/macOS: gfortran mlsin.f90 -o mlsin.exe

## Execution
- Run `./mlsin.exe` and follow prompts
- Enter angle and degree of approximation

## Observations
- Convergence improves with more terms
- Relative error decreases
- Faster convergence for smaller x

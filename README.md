# QPSK & 16-QAM Digital Modulation Simulator

A Python-based simulation of digital modulation schemes used in wireless communication systems (including 4G/5G), covering the full transmission chain: bit generation → modulation → AWGN noise channel → demodulation → error analysis.

## What it does

- Implements QPSK and 16-QAM modulation/demodulation from scratch
- Simulates an AWGN (Additive White Gaussian Noise) wireless channel
- Calculates Bit Error Rate (BER) across a range of Signal-to-Noise Ratio (SNR) values
- Validates simulated QPSK results against the theoretical BER formula
- Compares QPSK vs 16-QAM performance to demonstrate the throughput vs reliability tradeoff

## Key Results

- Simulated QPSK BER closely matches theoretical predictions across all tested SNR values
- 16-QAM requires approximately 7-8 dB higher SNR than QPSK to achieve the same BER, demonstrating the real-world tradeoff between data rate and noise resilience used in adaptive modulation (a core technique in 4G/5G networks)

## Tools Used

Python, NumPy, Matplotlib, SciPy

## How to run

Open `qpsk16qamModulationSimulator.ipynb` in Google Colab or Jupyter Notebook and run all cells sequentially.

# SNS_codingassignment
Coding assignment Group3
# Signal Filtering Project

## Overview

This project aims to infer the type of filtering applied to an input signal based on the given output signal. It involves implementing low-pass, high-pass, and band-pass filters, convolving each filter with the input signal, comparing the filtered outputs with the given output signal using correlation, and determining the best-matched filter.

## Methodology

### 1. Implementing Filters

- **Low Pass Filter:** Allows low-frequency components to pass through while attenuating high-frequency components.
- **High Pass Filter:** Allows high-frequency components to pass through while attenuating low-frequency components.
- **Band Pass Filter:** Allows a specific range of frequencies to pass through while attenuating frequencies outside the desired band.

### 2. Convolution

- Convolution is performed to combine each filter with the input signal, resulting in the filtered output signals (ylp(t), yhp(t), ybp(t)).

### 3. Comparison

- The filtered output signals are compared with the given output signal using correlation.
- Correlation values range from -1 to 1, with 1 indicating a perfect match, 0 indicating no correlation, and -1 indicating a perfect inverse correlation.

### 4. Determining the Best-Matched Filter

- The correlation results for each filter are analyzed to determine the best-matched filter.
- The filter with the highest correlation value indicates the type of filtering applied to the input signal.
### 5.Audio playing
- To play the audio, download the file in.wav format first
- then use the headphone to hear the clear voice
## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/signal-filtering-project.git

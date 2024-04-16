# SNS_codingassignment
Coding assignment Group3
# Methodology
The project involves the following steps:

# Implementing Low Pass, High Pass, and Band Pass Filters:
Low Pass Filter: Allows low-frequency components of the input signal to pass through while attenuating high-frequency components.
High Pass Filter: Allows high-frequency components of the input signal to pass through while attenuating low-frequency components.
Band Pass Filter: Allows a specific range of frequencies to pass through while attenuating frequencies outside the desired band.
# Convolving Each Filter with the Input Signal:
Convolution is a mathematical operation that combines two functions, such as the filter and the input signal, to produce a third function.
The convolution of the filter and the input signal results in the filtered output signal.
This step applies each filter (Low Pass, High Pass, and Band Pass) to the input signal to obtain the corresponding filtered outputs.
# Comparing the Filtered Outputs with the Given Output Signal:
The filtered outputs obtained in the previous step are compared with the given output signal.
Correlation is used as the comparison metric, which measures the similarity between the filtered outputs and the given output signal.
Correlation values range from -1 to 1, with 1 indicating a perfect match, 0 indicating no correlation, and -1 indicating a perfect inverse correlation.
# Determining the Best-Matched Filter:
The correlation results for each filter (Low Pass, High Pass, and Band Pass) are analyzed to determine which filter best matches the given output signal.
The filter with the highest correlation value is considered the best-matched filter, as it indicates the type of filtering that was applied to the input signal to produce the given output signal.

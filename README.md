# Follow the Leader? Message Framing and the Lifecycle of Mobilization of Online Armies in the Social Media Age

This repository contains supplemental files and resources related to the paper **"Follow the Leader? *Message Framing and the Lifecycle of Mobilization of Online Armies in the Social Media Age*"**. The resources contained here are included for completeness. All main findings are presented and discussed in the manuscript.

Below is an overview of the directory structure and the purpose of each folder and file.

## Directory Structure

### Dynamic Topic Model Plots
This folder contains visualizations of dynamic topic models categorized by different frames. These plots are categorized by topic, with a legend that provides the topic representations. These topic representations confirm our strategy for categorizing content into framing types and shed light on the themes within each core framing type:
- `diagnostic_tsot.png`: Diagnostic frame time series of topics.
- `motivational_tsot.png`: Motivational frame time series of topics.
- `non_framing_tsot.png`: Non-framing frame time series of topics.
- `prognostic_tsot.png`: Prognostic frame time series of topics.

### FEVD Plots
This folder includes Forecast Error Variance Decomposition (FEVD) plots for different windows:
- `Window 1 FEVD.png`
- `Window 4 FEVD.png`
- `Window 7 FEVD.png`
- `Window 10 FEVD.png`

### Impulse Response Plots
This folder contains impulse response plots showing the relationships between different frames and actions:
- `1_responses_of_moti_frame_to_diag_frame.png`: Response of motivational frame to diagnostic frame.
- `10_responses_of_diag_frame_to_acti_mobilization.png`: Response of diagnostic frame to action mobilization.
- `11_responses_of_prog_frame_to_moti_frame.png`: Response of prognostic frame to motivational frame.
- `12_responses_of_prog_frame_to_diag_frame.png`: Response of prognostic frame to diagnostic frame.
- `13_responses_of_prog_frame_to_msnb_breitbart.png`: Response of prognostic frame to media mentions (MSNBC/Breitbart).
- Additional plots follow a similar naming convention.

## How to Use This Repository

1. **Explore Dynamic Topic Models**: Navigate to the `Dynamic Topic Model Plots` folder to analyze the time series of topics categorized by frames.
2. **Analyze FEVD Results**: Visit the `FEVD Plots` folder to understand the variance decomposition across different windows.
3. **Study Impulse Responses**: Check the `Impulse Response Plots` folder for detailed relationships between frames and actions.

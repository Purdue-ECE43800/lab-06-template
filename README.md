# Lab 6: Frequency Analysis

In this experiment, we will use Fourier series and Fourier transforms to analyze
continuous-time and discrete-time signals and systems. The Fourier representations of signals
involve the decomposition of a signal in terms of complex exponential functions. These
decompositions are important in the analysis of linear time-invariant (LTI) systems, because
the response of an LTI system to a complex exponential input is a complex exponential of the
same frequency — only the amplitude and phase of the input signal are changed. Studying the
frequency response of an LTI system therefore gives complete insight into its behavior.

This lab also uses Simulink, an icon-driven simulation package that represents a system as a
block diagram and then digitally simulates its behavior. The models it needs are in
[`Lab6Utilities/`](Lab6Utilities), and [`simulink_help.pdf`](simulink_help.pdf) is a short
reference for the tool.

## Getting Started

1. Git clone the repository.

2. Open a new Terminal, run the command `jupyter notebook` and open `lab6_report.ipynb`.

3. Complete the lab report `lab6_report.ipynb`.

## Submission

### Code Submission
Option1:

```bash
git add -A
git commit -m "update lab report"
git push
```

Option2:
Use Github Desktop

### Report Submission
1. Export your report as an HTML file, then print it as a PDF for uploading to Gradescope.
2. Submit a PDF copy of your report to [Gradescope](https://www.gradescope.com/).

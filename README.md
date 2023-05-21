# LogStudy
LogBench is the benchmark for evaluating the performance of LLMs in logging statement generation.
Here is the overview of the study:
![overview](img/overview.png)
We provide part of the code in the folder `/src`, We will make the full source code available after the paper has been accepted.
# Download the Datasets
As GitHub does not hold large datasets, you can download the whole benchmark dataset LogBench-O at [here](https://drive.google.com/file/d/1KS4xrHkzggbmorK9OwGmTLa7QYmRsDGQ/view?usp=share_link)

# Study Objects
| Model        | Access | Year |
| ------------ | ------ | ---- |
| Davinci      | API    | 2022 |
| ChatGPT      | API    | 2022 |
| LANCE        | Model  | 2022 |
| InCoder      | Model  | 2022 |
| CodeGeex     | Plugin | 2022 |
| TabNine      | Plugin | 2022 |
| Copilot      | Plugin | 2021 |
| Code Whisper | Plugin | 2022 |

# Benchmark Details
Currently LogBench contains two sub-dataset for evaluating the performance of current code/log generation models, namely LogBench-O and LogBench-T.
## LogBench-O
The folder `/LogBench-O` contains the sampled files of LogBench-O.
## LogBench-T
The folder `/LogBench-T` contains the sampled files of LogBench-T.


# Additional: Code Transformation Tool

The folder `/build` contains the built tranformation tool we developed. It will conduct the code tranformation automatically with the seven code transformers.

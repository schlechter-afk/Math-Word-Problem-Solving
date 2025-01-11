# Mathematical Word Problem Solving

This repository consists of implementations for different methods to solve Mathematical Word Problems.

<img src="collage.png">*Note: All the above diagrams were made with Excalidraw*</img>

The methods implemented for this task include:
- FFN Encoder, LSTM Decoder
- RNN Encoder, LSTM Decoder
- Transformers
- Goal-Driven Tree Structured : https://www.ijcai.org/proceedings/2019/0736.pdf
- Graph-to-Tree Learning : https://aclanthology.org/2020.acl-main.362.pdf

LLMs for comparison:
  - Gemini-2-9B
    - Baseline
    - Standard prompting with fine-tuning
    - Few-shot prompting with fine-tuning
    - Inference-side Chain Of Thought reasoning (CoT)
    - Inference-side CoT + Few-shot prompting
  - Mistral Instruct 7B
    - Baseline
    - Standard prompting with fine-tuning

The code and results for all the baseline models can be found in the `Baseline Models` directory.

The code and results for LLMs can be found in the `LLMs` directory.

A comprehensive report for the project can be found here: [Report](./final_report_team_44.pdf)

The pre-trained models for all of the above can be found [here](https://drive.google.com/drive/folders/1eciPU5mak6DJTdNAZxl-m283GA38f4mm).

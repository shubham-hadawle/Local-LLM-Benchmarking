# Local-LLM-Benchmarking
Creating a benchmarking code to determine what open-sourced models can the local machine run

We need to precisely determine whether it is beneficial running a local model. We want to create a benchmarking code to determine what open-sourced models can the machine run and with what approximate latency (tpm) - Llama 3.1 8B, Qwen 2.5, Gemma 2B. 
This benchmarking code preferable should be efficient and not take too much computing resources and should give as accurate answers as possible.

This repository benchmarks Llama-3.1 8B, Qwen-2.5B, and Gemma-2B locally to measure throughput (tokens per second/minute) and latency.

## Requirements
- Python 3.10+
- PyTorch 2.0+
- transformers>=4.30.0
- accelerate>=0.20.3
- bitsandbytes (for 8-bit quantization)

## Model Benchmarks
1. Gemma 2B
<img width="567" height="200" alt="gemma2b" src="https://github.com/user-attachments/assets/28b73abb-ac1d-4b1b-a9c6-6e39e15a2f5a" />
</br>
</br>
  
2. Llama 3.1 8B
<img width="593" height="230" alt="Llama 1" src="https://github.com/user-attachments/assets/76b6b0c7-406c-40ee-bd0b-304c05c44cb8" />
<img width="494" height="150" alt="Llama 2" src="https://github.com/user-attachments/assets/49c136e9-10ee-4043-a51d-ba3310b835c2" />
</br>
</br>

3. Qwn 2.5
<img width="693" height="250" alt="image" src="https://github.com/user-attachments/assets/f16968ed-56a5-41f5-9458-8c3962fc8e2f" />
<img width="600" height="170" alt="image" src="https://github.com/user-attachments/assets/24475d23-fc10-4511-be12-6b5180512d59" />
</br>
</br>

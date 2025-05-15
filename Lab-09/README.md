# README: Running Local Inference with Hugging Face Transformers

This guide shows you how to find a pretrained model on Hugging Face and run it locally—no API key or external billing required.

---

## 1. Finding a Pretrained Model

1. **Visit the Model Hub**  
   Go to [https://huggingface.co/models](https://huggingface.co/models).

2. **Filter by Task**  
   - In the sidebar, under **Tasks**, select **Text Generation**.  
   - Optionally filter by **Library** (“transformers”) or by model size.

3. **Choose a Model**  
   Popular text-generation models:
   - `gpt2` (117 M parameters)  
   - `EleutherAI/gpt-neo-1.3B` (1.3 B parameters)  
   - `bigscience/bloom-560m` (560 M parameters)

4. **Read the Model Card**  
   Check usage examples, recommended settings, and any special notes (e.g., padding token requirements).

---

## 2. Installing Dependencies

Install the core libraries:

```bash
pip install transformers torch

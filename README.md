# PEFT_LLAMA

Parameter efficient fine-tuning Llama model with MIMIC dataset

## model
The model that has been utilized is Llama 2.
Llama 2 is a collection of pretrained and fine-tuned generative text models ranging in scale from 7 billion to 70 billion parameters. 
This is the repository for the 7B pretrained model, converted for the Hugging Face Transformers format: 
https://huggingface.co/meta-llama/Llama-2-7b-hf

## dataset
MIMIC-IV is a publicly available database sourced from the electronic health record of the Beth Israel Deaconess Medical Center. Information available includes patient measurements, orders, diagnoses, procedures, treatments, and deidentified free-text clinical notes.
https://archive.physionet.org/physiobank/database/mimicdb/

## LoRA
We used LoRA to efficiently fine-tune the LLaMA model with findings from the MIMIC dataset and inferred the results.
HuggingFace documentation:
https://huggingface.co/docs/peft/en/package_reference/lora

Original paper:
https://arxiv.org/abs/2106.09685

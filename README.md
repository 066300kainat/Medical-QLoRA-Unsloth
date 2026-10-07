# Medical QLoRA Fine-Tuning with Unsloth

This project demonstrates medical-domain fine-tuning of the Llama 3.2 3B Instruct language model using 4-bit QLoRA and Unsloth in Google Colab.

## Technologies Used

- Python
- Google Colab
- Unsloth
- Hugging Face Transformers
- Hugging Face Datasets
- TRL
- PEFT / LoRA
- BitsAndBytes
- Llama 3.2 3B Instruct

## Project Details

- Base Model: Llama 3.2 3B Instruct
- Quantization: 4-bit
- Fine-Tuning: QLoRA / LoRA
- LoRA Rank: 16
- Training Epochs: 2
- Training Examples: 1,000
- GPU: NVIDIA Tesla T4
- Final Training Loss: 0.6415
- GPU Memory Allocated: approximately 2.45 GB

## Dataset

Medical Meadow Medical Flashcards:

medalpaca/medical_meadow_medical_flashcards

## Purpose

This project demonstrates efficient Parameter-Efficient Fine-Tuning (PEFT), 4-bit quantization, LoRA adapter training, GPU memory optimization, and medical-domain model adaptation.

## Disclaimer

This project is for educational and research purposes only and should not be used for medical diagnosis or treatment decisions.

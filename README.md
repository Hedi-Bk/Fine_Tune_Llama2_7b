# Fine-Tuning LLaMA-2-7B with QLoRA

Fine-tuning the **LLaMA-2-7B** model using **QLoRA** on a dataset of **1000 examples**, fully executed on **KAGGLE**.

---

## Kaggle Notebook

Click here to open the project:

[![Open In Kaggle](https://www.kaggle.com/code/bkhedi/huggingface-finetune-llama2)]


---

## Project Objective

- Fine-tune a **LLaMA-2-7B** model
- Use **QLoRA (Quantized Low-Rank Adaptation)**
- Train **only LoRA adapters**
- Load the base model in **4-bit NF4** using **bitsandbytes**
- Environment: **Google Colab**

---

## Technologies Used

- **LLaMA-2-7B**
- **QLoRA (HuggingFace PEFT)**
- **BitsAndBytes (4-bit NF4 quantization)**
- **Google Colab**
- **Hugging Face Transformers**

---

## Additional Resources (Research Papers & Blog)

If you want to learn more about QLoRA, check out these excellent resources:

- 📄 **QLoRA Research Paper (Official)** :
  [Arxiv paper](https://arxiv.org/pdf/2305.14314.pdf)
- 📝 **QLoRA Explained – W&B Blog** :
  [Web Blog](https://wandb.ai/sauravmaheshkar/QLoRA/reports/What-is-QLoRA---Vmlldzo2MTI2OTc5)

This project is heavily inspired by the tutorial from:

- **Krish Naik (YouTube)**

  Tutorial: _Fine-tuning LLaMA-2 using QLoRA_

---

## Note

> This project was entirely developed on Google Colab (no local code).
>
> The GitHub repository is used only for documentation and project organization.

---

## License

Free to use for educational purposes.

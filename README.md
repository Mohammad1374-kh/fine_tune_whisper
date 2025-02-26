**Requirements:**

**Fine-tuning:**
Use fine_tune_whisper_Mohammad_Khosravi.ipynb (Jupyter Notebook – you can use Google Colab).
To fine-tune the model, you need to create an account on Hugging Face and generate an access token to save your checkpoints during training.
Additionally, fine-tuning requires **at least 32 GB of GPU memory** (e.g., an A100 on Colab, which is unfortunately not available in the free tier) for Whisper Large v3.

My fine-tuned model is available for further fine-tuning at:
https://huggingface.co/MohammadKhosravi/whisper-large-v3-Persian

**Inference:**
For inference, use Whisper_transcription_inference_Mohammad_Khosravi.ipynb.
You do not need a Hugging Face access token for inference.
A minimum of 13 GB of GPU memory is required for efficient inference. You can use a CPU, but the inference time will be extremely long.

A free T4 GPU on Colab works well for basic testing and short-term use.

# Uz_En_llm
- Built Uzbek-English Pretrained Language Model (140M Parameters)
- Collected a diverse Uzbek-English dataset and trained a Byte Pair Encoding (BPE) tokenizer from scratch, resulting in a vocabulary size of ~62,016 tokens.
- Built a decoder-only Transformer architecture with 140.7M parameters and a 1024-token context window.
- Developed the full AI training pipeline and pre-trained the model using open-source multilingual datasets on 2× NVIDIA A100 GPUs for 16.5 hours.
- Reached ~3.5% cross-entropy loss during pretraining; model currently supports next-token generation.
- Planning to fine-tune the model for instruction-following and downstream task alignment.
- Demo includes both short and long prompt generation samples.

### Params:
- Max token=100 and 300
- temperature=0.8
- top_k=40


![telegram-cloud-photo-size-2-5267283433401482442-y](https://github.com/user-attachments/assets/3c581f31-427c-4cd5-9c76-367bc837f78b)
![telegram-cloud-photo-size-2-5269596616887762496-y](https://github.com/user-attachments/assets/404f5e64-99c5-4258-9305-d32c1d3c83a1)

### Params:
- Max token=1024
- temperature=1
- top_k=40


![telegram-cloud-photo-size-2-5210946201350960991-y](https://github.com/user-attachments/assets/4bf2d6bd-68d7-45ee-8860-705403961da7)
![telegram-cloud-photo-size-2-5210946201350960990-y](https://github.com/user-attachments/assets/8bc4fda5-cc6f-4ebb-b420-c30f92ef297e)


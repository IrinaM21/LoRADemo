Small demo of LoRA fine-tuning with Hugging Face for sequence classification. Results, checkpoints, data included. Detailed explanation of implementation in notebook. 

LoRADemo/
├── distilbert_amazon_adapters/
│   ├── adapter_config.json
│   └── adapter_model.safetensors
├── merged_distilbert_amazon/
│   ├── config.json
│   └── model.safetensors (after download at link below)
├── tokenized_amazon/ (after download at link below)
│   ├── dataset_dict.json
│   ├── train/
│     ├── (tokenized train set files)
│   └── test/
│      ├── (tokenized test set files)
├── lora_results/ (after download at link below)
│   └── (checkpoints)
└── README.md

Adapter checkpoints: https://drive.google.com/drive/folders/1yp16uP8ScR4SSF2v2h1ncGAjZ1YrG1AY?usp=share_link

Merged model weights: https://drive.google.com/file/d/1Eu-vr_wy2LarIPtiqu2BsoXKxsRgwQ1z/view?usp=share_link
mv to ./merged_distilbert_amazon to run inference.

Download tokenized Amazon Review Polarity dataset here: https://drive.google.com/drive/folders/1TeA7i09KnHMVGEoQzptRDkQR_-yxsSBS?usp=share_link

Dataset src: https://huggingface.co/datasets/mteb/amazon_polarity (other sources linked in notebook)

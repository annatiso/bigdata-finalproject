# AI Watermarking for Model Attribution

The aim of this code is to embed a watermarking scheme into four open-source models:
- [DeepSeek V3](https://github.com/huggingface/transformers/tree/debfe904c94d1104e94c71d2276a0d522f0f5081/src/transformers/models/deepseek_v3)
- [Falcon](https://github.com/huggingface/transformers/tree/debfe904c94d1104e94c71d2276a0d522f0f5081/src/transformers/models/falcon)
- [LLaMA](https://github.com/huggingface/transformers/tree/debfe904c94d1104e94c71d2276a0d522f0f5081/src/transformers/models/llama)
- [Mistral](https://github.com/huggingface/transformers/tree/debfe904c94d1104e94c71d2276a0d522f0f5081/src/transformers/models/mistral)

The watermarking scheme is based on the pseudo-code provided in the paper [Undetectable watermarking for language models](https://proceedings.mlr.press/v247/christ24a.html).

The watermarked models will then be used to generate watermarked text data so that we can test the watermark detector for model attribution.

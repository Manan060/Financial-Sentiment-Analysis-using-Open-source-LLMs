# Financial Sentiment Analysis with Fine-Tuned LLMs

This project explores parameter-efficient fine-tuning of open-source Large Language Models (LLMs) for financial sentiment analysis using the Financial PhraseBank dataset.

## Models Used
- LLaMA-2-7B-it
- Mistral-7B-Instruct
- Gemma-2B-it

## Techniques
- LoRA (Low-Rank Adaptation)
- QLoRA (4-bit Quantized LoRA)
- Hugging Face Transformers & PEFT

## Dataset
- Financial PhraseBank (sentiment-labeled financial news sentences)

## Results
Fine-tuned models significantly outperform their base versions and the benchmark FinBERT model.

| Model | Accuracy | Precision | Recall | F1 |
|------|----------|-----------|--------|----|
| LLaMA2-7B-it | 86% | 86% | 86% | 0.86 |
| Gemma-2B-it | 87% | 87% | 87% | 0.87 |
| Mistral-7B-Instruct | **89%** | **89%** | **89%** | **0.89** |

## Hugging Face Models
- [LLaMA2 Fine-Tuned Model][https://huggingface.co/Manan28/Finllama2-finetuned](Link)
- [Mistral Fine-Tuned Model][https://huggingface.co/Manan28/FinMistral-finetuned](Link)
- [Gemma Fine-Tuned Model][https://huggingface.co/Manan28/Fingemma-finetuned](Link)


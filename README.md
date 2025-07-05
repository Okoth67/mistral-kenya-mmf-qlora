# Mistral Kenya Finance QLoRA

Fine-tuning Mistral-7B on a small Kenyan dataset to build a financial assistant that answers questions about Money Market Funds (MMFs).

## 💡 Objective
Use QLoRA (Quantized Low-Rank Adaptation) to fine-tune a 7B LLM on domain-specific financial data from Kenya. The final model answers common retail investment questions.

## 📊 Dataset
A small instruction-tuned JSON dataset (`kenya_mmf_data.json`) with 20 examples in Alpaca format:
```json
{
  "instruction": "What is a money market fund?",
  "input": "",
  "output": "A money market fund in Kenya is..."
}

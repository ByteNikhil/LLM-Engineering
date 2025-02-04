# LLM Engineering

## Model Parameters
| Model | Parameters |
|-------|------------|
| GPT-1 | 117M |
| GPT-2 | 1.5B |
| Gemma | 2B |
| Llama 3.1 | 8B |
| Llama 3.1 | 70B |
| Mixtral | 140B |
| GPT-3 | 175B |
| Llama 3.1 | 405B |
| GPT-4 | 1.76T |
| Other frontier models | undisclosed |

## Transformers

### Evolution of Token Prediction
1. Character-level training: Neural networks predicted the next character in sequences
2. Word-level training: Neural networks predicted the next word in sequences  
3. Token-level breakthrough: Working with chunks of words called 'tokens'

### GPT's Tokenizer
Token conversion rules of thumb for typical English writing:
- 1 token ≈ 4 characters
- 1 token ≈ 0.75 words
- 1000 tokens ≈ 750 words

Note: Token count increases for mathematical notation, scientific terms, and code.

## API Costs
- APIs typically operate on a pay-per-call basis without subscriptions
- Costs are calculated based on:
 - Number of input tokens
 - Number of output tokens
- Cost and context window comparisons available via Vellum.ai
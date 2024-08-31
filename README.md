# evaluation-LLMs-pt-tables

## Table 1: Evaluated models.
| Model       | Size | Developer                        |
|-------------|------|----------------------------------|
| LLaMA       | 7B   | Meta AI                          |
| LLaMA 2     | 7B   | Meta AI                          |
| LLaMA 2     | 13B  | Meta AI                          |
| Alpaca-LoRA | 7B   | Eric J. Wang                     |
| Cabrita     | 7B   | Pi Esposito and Pedro Gengo      |
| Falcon      | 7B   | Technology Innovation Institute  |
| Falcon      | 40B  | Technology Innovation Institute  |
| Vicuna      | 7B   | Large Model Systems Organization |
| Vicuna      | 13B  | Large Model Systems Organization |
| Vicuna      | 33B  | Large Model Systems Organization |
| GPT-J       | 6B   | Eleuther AI                      |
| GPT4All-J   | 6B   | Nomic AI                         |
| Dolly       | 3B   | Databricks                       |
| BODE        | 7B   | Recogna-NLP                      |
| BODE        | 13B  | Recogna-NLP                      |
| Mistral     | 7B   | MistralAI                        |

## Table 2: Numerical classification method.

| Category | Description                                                                             |
|----------|-----------------------------------------------------------------------------------------|
| 1        | The model is not able to generate sentences or it generates non-Portuguese sentences.   |
| 2        | The model generates text having no cohesion nor coherence.                              |
| 3        | The model generates mostly cohesive and coherent texts, but with major factual errors.  |
| 4        | The model generates cohesive and coherent texts, but with factual errors.               |
| 5        | The model generates cohesive and coherent texts with few or no errors.                  |

## Table 3: Evaluation of the models.

| Model       | Size | PT-BR Training | Evaluation |
|-------------|------|----------------|------------|
| LLaMA       | 7B   | Yes            | 1          |
| LLaMA 2     | 7B   | Yes            | 4          |
| LLaMA 2     | 13B  | Yes            | 5          |
| Alpaca-LoRA | 7B   | No             | 1          |
| Cabrita     | 7B   | Yes            | 5          |
| Falcon      | 7B   | No             | 1          |
| Falcon      | 40B  | Yes            | 3          |
| Vicuna      | 7B   | Yes            | 4          |
| Vicuna      | 13B  | Yes            | 5          |
| Vicuna      | 33B  | Yes            | 5          |
| GPT-J       | 6B   | No             | 2          |
| GPT4All-J   | 6B   | No             | 2          |
| Dolly       | 3B   | No             | 2          |
| BODE        | 7B   | Yes            | 5          |
| BODE        | 13B  | Yes            | 5          |
| Mistral     | 7B   | No             | 2          |

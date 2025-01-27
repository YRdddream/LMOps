# LMOps: Enabling AI w/ LLMs

## News
- Dec, 2022: [Why Can GPT Learn In-Context? Language Models Secretly Perform Finetuning as Meta Optimizers](#) (coming soon)
- [Paper&Model&Demo Release] Dec, 2022: [Optimizing Prompts for Text-to-Image Generation](https://aka.ms/promptist)
- [Paper&Code Release] Dec, 2022: [Structured Prompting: Scaling In-Context Learning to 1,000 Examples](https://arxiv.org/abs/2212.06713)
- [Paper Release] Nov, 2022: [Extensible Prompts for Language Models](https://arxiv.org/abs/2212.00616)

## Prompt Intelligence

Advanced technologies facilitating prompting language models.

### X-Prompt: extensible prompts beyond NL for descriptive instructions

[Paper] [Extensible Prompts for Language Models](https://arxiv.org/abs/2212.00616)

> - Extensible interface allowing prompting LLMs beyond natural language for fine-grain specifications

> - Context-guided imaginary word learning for general usability

![Extensible Prompts for Language Models](https://user-images.githubusercontent.com/1070872/207856788-5409d04d-c406-4b29-ae7b-2732e727d4cc.png)


### Promptist: reinforcement learning for automatic prompt optimization

[Paper] [Optimizing Prompts for Text-to-Image Generation](https://aka.ms/promptist-paper)

> - Language models serve as a prompt interface that optimizes user input into model-preferred prompts.

> - Learn a language model for automatic prompt optimization via reinforcement learning.

![image](https://user-images.githubusercontent.com/1070872/207856962-02f08d92-f2bf-441a-b1c3-efff1a4b6187.png)


### Structured Prompting: consume long-sequence prompts in an efficient way

[Paper] [Structured Prompting: Scaling In-Context Learning to 1,000 Examples](https://arxiv.org/abs/2212.06713)

- Example use cases:

> 1) Prepend (many) retrieved (long) documents as context in GPT.

> 2) Scale in-context learning to many demonstration examples.

![image](https://user-images.githubusercontent.com/1070872/207856629-2bb0c933-c27b-4177-9e10-e397622ae79b.png)

## Links

- [microsoft/unilm](https://github.com/microsoft/unilm): Large-scale Self-supervised Pre-training Across Tasks, Languages, and Modalities
- [microsoft/torchscale](https://github.com/microsoft/torchscale): Transformers at (any) Scale

## Hiring: [aka.ms/nlpagi](https://aka.ms/nlpagi)
We are hiring at all levels (including FTE researchers and interns)! If you are interested in working with us on Foundation Models (aka large-scale pre-trained models) and AGI, NLP, MT, Speech, Document AI and Multimodal AI, please send your resume to <a href="mailto:fuwei@microsoft.com" class="x-hidden-focus">fuwei@microsoft.com</a>.

## License
This project is licensed under the license found in the LICENSE file in the root directory of this source tree.

[Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct)

### Contact Information

For help or issues using the pre-trained models, please submit a GitHub issue.
For other communications, please contact [Furu Wei](http://gitnlp.org/) (`fuwei@microsoft.com`).

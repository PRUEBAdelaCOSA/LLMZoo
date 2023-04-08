# LLM Zoo: democratizing ChatGPT

⚡LLM Zoo is a project that provides data, models, and evaluation benchmark for large language models.⚡

## 🤔 Motivation 

- Break  "AI supremacy"  and democratize ChatGPT
> "AI supremacy" is understood as a company's absolute leadership and monopoly position in an AI field, which may even include exclusive capabilities beyond general artificial intelligence. This is unacceptable for society and may even lead to individual influence on the direction of the human future, thus bringing various hazards to society.
- Make ChatGPT-like LLM accessible across countries and languages
- Make AI open again. Every person, regardless of their skin color or place of birth, should have equal access to the technology gifted by the creator. For example, many pioneers have made great efforts to spread the use of light bulbs and vaccines to developing countries. Similarly, ChatGPT, one of the greatest technological advancements in modern history, should also be made available to all.

## 📚 Data
### Instruction data
- Multilingual instructions (language-agostic instructions with post-translation)
- Language-specific instructions
- **User**-centered instruction (**Modular** instruction construction)
- **Chat**-based instructions (user, instruction, conversations)
> check open intruction dataset in https://github.com/FreedomIntelligence/InstructionZoo
### Conversation data
- User-generated ChatGPT conversations
> check open User-chatGPT conversation data in  https://github.com/FreedomIntelligence/OpenChatGPT

## 🐼 Models
The philosophy to name models: 
> The biggest barrier to LLM is that we do not have enough candidate names for LLM, as LLAMA, Guanaco, Vicuna, and Alpaca were already used, and there are no more members in the camel family. Therefore, we find a similar hybrid creature in Greek mythology, [Chimera](https://en.wikipedia.org/wiki/Chimera_(mythology)), composed of different Lycia and Asia Minor animal parts.
Coincidentally, it is a hero/role in DOTA (and also Warcraft III). It could therefore be used to memorize a period to play games overnight during high school and undergraduate time.

> The second model is named **Phoenix**. In Chinese culture, the Phoenix is commonly regarded as a symbol of *the king of birds*; as the saying goes "百鸟朝凤", indicating its ability to coordinate with all birds, even if they speak different languages. We refer to Phoenix as the one capable of understanding and speaking hundreds of (bird) languages.  

> More importantly, **Phoenix** is the symbol of "the Chinese University of Hong Kong, Shenzhen" (CUHKSZ); It goes without saying this is also for the Chinese University of Hong Kong (CUHK).

### Chimera: 

LLM  mainly for Latin and Cyrillic languages.

### Phoenix: 

LLM across Languages.

### CAMEL (Chinese And Medically Enhanced Langauge models)

Its Chinese name is HuatuoGPT or 华佗GPT to commemorate the great Chinese physician named Hua Tuo (华佗), who lived around 200 AC.  Training is already finished; we will release it in two weeks; some efforts are needed to delopy it in public cloud servers in case of massive requests.

### Vision-langugae LLaMA (coming soon)
### Retrieval-augmented LLaMA (coming soon)


## 🧐 Evaluation

## 🏭 Deployment
### Install

### Serving

### Web UI

## 🤖 Limitations


Our goal in releasing our models is to assist our community in better replicating ChatGPT/GPT4. We are not targeting competition with other competitors, as benchmarking models is a challenging task. Our models face similar models to those of ChatGPT/GPT4, which include:

- Lack of common sense: our models may not always have the ability to apply common sense knowledge to situations, which can lead to nonsensical or inappropriate responses.

- Limited knowledge domain: our models' knowledge is based on the data it was trained on, and it may not have the ability to provide accurate or relevant responses outside of that domain.

- Biases: our models may have biases that reflect the biases in the data it was trained on, which can result in unintended consequences or unfair treatment.

- Inability to understand emotions: While our models can understand language, it may not always be able to understand the emotional tone behind it, which can lead to inappropriate or insensitive responses.

- Misunderstandings due to context: our models may misunderstand the context of a conversation, leading to misinterpretation and incorrect responses.


## 🙌 Contributors
LLM Zoo are mainly contributed by:
- Data and Model: [Zhihong Chen](https://zhjohnchan.github.io/), [Junying Chen](), [Hongbo Zhang](), [Feng Jiang](), [Benyou Wang](https://wabyking.github.io/old.html) (Advisor)
- Evaluation: [Tiannan Wang](), [Fei Yu](), [Guiming Chen]()
- Others: Zhiyi Zhang, Jianquan Li and Xiang Wan

As an open source project, we are open to contributions. Feel free to contribute if you have any ideas or find any issue.


## Acknowledgement

We are aware that our works are inspired by the following works, include but are not limited to 
- LLaMA: https://github.com/facebookresearch/llama
- Bloom: https://huggingface.co/bigscience/bloom
- Self-instruct: https://github.com/yizhongw/self-instruct
- Alpaca: https://github.com/tatsu-lab/stanford_alpaca
- Vicuna: https://github.com/lm-sys/FastChat

Without these nothing could happen in this repository

## Citation
```angular2
@misc{llm-zoo-2023,
  title={LLM Zoo: democratizing ChatGPT},
  author={Zhihong Chen and Junying Chen and Hongbo Zhang and Feng Jiang and Guiming Chen and Tiannan Wang and Fei Yu and Zhiyi Zhang and Jianquan Li and and Xiang Wan and Haizhou Li and Benyou Wang},
  year = {2023},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/FreedomIntelligence/LLMZoo}},
}
```

We are from the School of Data Science, the Chinese University of Hong Kong, Shenzhen (CUHKSZ) and the Shenzhen Rsearch Institute of Big Data (SRIBD).

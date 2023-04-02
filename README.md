# open_source_chatgpt_list

list of open source works to implement chatgpt-like chatbots.

| institution/contributor             | model                                                                                      | language | base model                    | main feature                                                                                                                                                                                                                                                                                                                                                               |
| :---------------------------------- | :----------------------------------------------------------------------------------------- | -------- | :---------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Meta                                | [LLaMA](https://github.com/facebookresearch/llama)                                            | en       | -                             | LLaMA-13B outperforms GPT-3(175B) and LLaMA-65B is competitive to PaLM-540M.<br />Base model for most follow-up works.                                                                                                                                                                                                                                                     |
| @ggerganov                          | [llama.cpp](https://github.com/ggerganov/llama.cpp)                                           | en       | LLaMA                         | c/cpp implement of llama and some other models, using quantization.                                                                                                                                                                                                                                                                                                       |
| Stanford                            | [Alpaca](https://github.com/tatsu-lab/stanford_alpaca)                                        | en       | LLaMA-7B                      | use 52K instruction-following data generated by Self-Instructt techniques to fine-utne 7B LLaMA,<br /> the resulting model,  Alpaca, behaves similarly to the `text-davinci-003` model on the Self-Instruct instruction-following evaluation suite.<br />Alpaca has inspired many follow-up models.                                                                 |
| LianJia                             | [BELLE](https://github.com/LianjiaTech/BELLE)                                                 | en/zh    | BLOOMZ-7B1-mt                 | maybe the first Chinese model to follow Alpaca.                                                                                                                                                                                                                                                                                                                            |
| Tsinghua                            | [ChatGLM-6B](https://github.com/THUDM/ChatGLM-6B)                                             | en/zh    | GLM                           | well-known Chinese model, in chat mode, and can run on single GPU.                                                                                                                                                                                                                                                                                                         |
| Databricks                          | [Dolly](https://github.com/databrickslabs/dolly)                                              | en       | GPT-J 6B                      | use Alpaca data to fine-tune a 2-year-old model: GPT-J, which exhibits surprisingly high quality<br /> instruction following behavior not characteristic of the foundation model on which it is based.                                                                                                                                                                    |
| @tloen                              | [Alpaca-LoRA](https://github.com/tloen/alpaca-lora)                                           | en       | LLaMA-7B                      | trained within hours on a single RTX 4090,<br />reproducing the [Stanford Alpaca](https://github.com/tatsu-lab/stanford_alpaca) results using [low-rank adaptation (LoRA)](https://arxiv.org/pdf/2106.09685.pdf),<br />and can run on a Raspberry pi.                                                                                                                           |
| ColossalAI                          | [ColossalChat](https://github.com/hpcaitech/ColossalAI/blob/main/applications/Chat/README.md) | en/zh    | LLaMA-7B                      | provides a unified large language model framework, including:<br />Supervised datasets collection<br />Supervised instructions fine-tuning<br />Reward model training<br />RLHF<br />Quantization inference<br />Fast model deploying<br />Perfectly integrated with the Hugging Face ecosystem                                                                            |
| Shanghai AI Lab                     | [LLaMA-Adapter](https://github.com/ZrrSkywalker/LLaMA-Adapter)                                | en       | LLaMA-7B                      | Fine-tuning LLaMA to follow instructions within 1 Hour and 1.2M Parameters                                                                                                                                                                                                                                                                                                 |
| PhoebusSi                           | [Alpaca-CoT](https://github.com/PhoebusSi/Alpaca-CoT)                                         | en/zh    | LLaMA/ChatGLM/BLOOM           | extend CoT data to Alpaca to boost its reasoning ability.<br />aims to build an instruction finetuning (IFT) platform with extensive instruction collection (especially the CoT datasets)<br /> and a unified interface for various large language models.                                                                                                                 |
| AetherCortex                        | [Llama-X](https://github.com/AetherCortex/Llama-X)                                            | en       | LLaMA                         | Open Academic Research on Improving LLaMA to SOTA LLM                                                                                                                                                                                                                                                                                                                      |
| Together                            | [OpenChatKit](https://github.com/togethercomputer/OpenChatKit)                                | en       | GPT-NeoX-20B                  | OpenChatKit provides a powerful, open-source base to create both specialized and general purpose chatbots for various applications.<br /> The kit includes an instruction-tuned language models, a moderation model, and an extensible retrieval system for including <br />up-to-date responses from custom repositories.                                                 |
| nomic-ai                            | [GPT4All](https://github.com/nomic-ai/gpt4all)                                                | en       | LLaMA                         | trained on a massive collection of clean assistant data including code, stories and dialogue                                                                                                                                                                                                                                                                               |
| @ymcui                              | [Chinese-LLaMA-Alpaca](https://github.com/ymcui/Chinese-LLaMA-Alpaca)                         | en/zh    | LLaMA-7B/13B                  | expand the Chinese vocabulary based on the original LLaMA and use Chinese data for secondary pre-training,<br /> further enhancing Chinese basic semantic understanding. Additionally, the project uses Chinese instruction data<br /> for fine-tuning on the basis of the Chinese LLaMA, significantly improving the model's understanding and execution of instructions. |
| UC Berkley、**Stanford**、CMU | [Vicuna](https://github.com/lm-sys/FastChat)                                                  | en       | LLaMA-13B                     | Impressing GPT-4 with 90% ChatGPT Quality                                                                                                                                                                                                                                                                                                                                  |
| @NouamaneTazi                       | [bloomz.cpp](https://github.com/NouamaneTazi/bloomz.cpp)                                      | en/zh    | BLOOM                         | C++ implementation for BLOOM inference.                                                                                                                                                                                                                                                                                                                                    |
| HKUST                               | [LMFlow](https://github.com/OptimalScale/LMFlow)                                              | en/zh    | LLaMA/Galatica/GPT-2<br />... | An extensible, convenient, and efficient toolbox for finetuning large machine learning models, designed to be user-friendly,<br /> speedy and reliable, and accessible to the entire community.                                                                                                                                                                            |

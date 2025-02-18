# Welcome to the Gemma Cookbook
This is a collection of guides and examples for [Google Gemma](https://ai.google.dev/gemma/).

## Get started with the Gemma models
Gemma is a family of lightweight, state-of-the art open models built from the same research and technology used to create the Gemini models. The Gemma model family includes:
* [base Gemma](https://ai.google.dev/gemma/docs/model_card)
* [CodeGemma](https://ai.google.dev/gemma/docs/codegemma)
* [PaliGemma](https://ai.google.dev/gemma/docs/paligemma)
* [RecurrentGemma](https://ai.google.dev/gemma/docs/recurrentgemma)

You can find the Gemma models on GitHub, Hugging Face models, Kaggle, Google Cloud Vertex AI Model Garden, and [ai.nvidia.com](ai.nvidia.com).

## Table of contents

| Name                                                                                                           | Description                                                                                                                                                                             |
| -------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Common_use_cases.ipynb](Common_use_cases.ipynb)                                                               | Illustrate some common use cases for Gemma, CodeGemma and PaliGemma.                                                                                                                    |
| **Gemma**                                                                                                      |
| [Keras_Gemma_2_Quickstart.ipynb](Gemma/Keras_Gemma_2_Quickstart.ipynb)                                         | Gemma 2 pre-trained 9B model quickstart tutorial with Keras.                                                                                                                            |
| [Keras_Gemma_2_Quickstart_Chat.ipynb](Gemma/Keras_Gemma_2_Quickstart_Chat.ipynb)                               | Gemma 2 instruction-tuned 9B model quickstart tutorial with Keras. Referenced in this [blog](https://developers.googleblog.com/en/fine-tuning-gemma-2-with-keras-hugging-face-update/). |
| [Chat_and_distributed_pirate_tuning.ipynb](Gemma/Chat_and_distributed_pirate_tuning.ipynb)                     | Chat with Gemma 7B and finetune it so that it generates responses in pirates' tone.                                                                                                     |
| [Gemma_control_vectors.ipynb](Gemma/Gemma_control_vectors.ipynb)                                               | Implement [control vectors](https://arxiv.org/abs/2310.01405) with Gemma in the I/O 2024 [Keras talk](https://www.youtube.com/watch?v=TV7qCk1dBWA).                                     |
| [Self_extend_Gemma.ipynb](Gemma/Self_extend_Gemma.ipynb)                                                       | Self-extend context window for Gemma in the I/O 2024 [Keras talk](https://www.youtube.com/watch?v=TV7qCk1dBWA).                                                                         |
| [Gemma_Basics_with_HF.ipynb](Gemma/Gemma_Basics_with_HF.ipynb)                                                 | Load, run, finetune and deploy Gemma using [Hugging Face](https://huggingface.co/).                                                                                                     |
| [Guess_the_word.ipynb](Gemma/Guess_the_word.ipynb)                                                             | Play a word guessing game with Gemma using Keras.                                                                                                                                       |
| [Game_Design_Brainstorming.ipynb](Gemma/Game_Design_Brainstorming.ipynb)                                       | Use Gemma to brainstorm ideas during game design using Keras.                                                                                                                           |
| [Translator_of_Old_Korean_Literature.ipynb](Gemma/Translator_of_Old_Korean_Literature.ipynb)                   | Use Gemma to translate old Korean literature using Keras.                                                                                                                               |
| [Prompt_chaining.ipynb](Gemma/Prompt_chaining.ipynb)                                                           | Illustrate prompt chaining and iterative generation with Gemma.                                                                                                                         |
| [Advanced_Prompting_Techniques.ipynb](Gemma/Advanced_Prompting_Techniques.ipynb)                               | Illustrate advanced prompting techniques with Gemma.                                                                                                                                    |
| [Run_with_Ollama.ipynb](Gemma/Run_with_Ollama.ipynb)                                                           | Run Gemma models using [Ollama](https://www.ollama.com/).                                                                                                                               |
| [Deploy_with_vLLM.ipynb](Gemma/Deploy_with_vLLM.ipynb)                                                         | Deploy a Gemma model using [vLLM](https://github.com/vllm-project/vllm).                                                                                                                |
| [RAG_with_ChromaDB.ipynb](Gemma/RAG_with_ChromaDB.ipynb)                                                       | Build a Retrieval Augmented Generation (RAG) system with Gemma using [ChromaDB](https://www.trychroma.com/) and [Hugging Face](https://huggingface.co/).                                |
| [Minimal_RAG.ipynb](Gemma/Minimal_RAG.ipynb)                                                                   | Minimal example of building a RAG system with Gemma using [Google UniSim](https://github.com/google/unisim) and [Hugging Face](https://huggingface.co/).                                |
| [Using_Gemma_with_LangChain.ipynb](Gemma/Using_Gemma_with_LangChain.ipynb)                                     | Examples to demonstrate using Gemma with [LangChain](https://www.langchain.com/).                                                                                                       |
| [Gemma_RAG_LlamaIndex.ipynb](Gemma/Gemma_RAG_LlamaIndex.ipynb)                                                 | RAG example with [LlamaIndex](https://www.llamaindex.ai/) using Gemma.                                                                                                                  |
| [Integrate_with_Mesop.ipynb](Gemma/Integrate_with_Mesop.ipynb)                                                 | Integrate Gemma with [Google Mesop](https://google.github.io/mesop/).                                                                                                                   |
| [Integrate_with_OneTwo.ipynb](Gemma/Integrate_with_OneTwo.ipynb)                                               | Integrate Gemma with [Google OneTwo](https://github.com/google-deepmind/onetwo).                                                                                                        |
| [Finetune_with_Axolotl.ipynb](Gemma/Finetune_with_Axolotl.ipynb)                                               | Finetune Gemma using [Axolotl](https://github.com/OpenAccess-AI-Collective/axolotl).                                                                                                    |
| [Finetune_with_XTuner.ipynb](Gemma/Finetune_with_XTuner.ipynb)                                                 | Finetune Gemma using [XTuner](https://github.com/InternLM/xtuner).                                                                                                                      |
| [Finetune_with_LLaMA_Factory.ipynb](Gemma/Finetune_with_LLaMA_Factory.ipynb)                                   | Finetune Gemma using [LLaMA-Factory](https://github.com/hiyouga/LLaMA-Factory).                                                                                                         |
| **PaliGemma**                                                                                                  |
| [Image_captioning_using_PaliGemma.ipynb](PaliGemma/Image_captioning_using_PaliGemma.ipynb)                     | Use PaliGemma to generate image captions using Keras.                                                                                                                                   |
| [Image_captioning_using_finetuned_PaliGemma.ipynb](PaliGemma/Image_captioning_using_finetuned_PaliGemma.ipynb) | Compare the image captioning results using different PaliGemma versions with [Hugging Face](https://huggingface.co/).                                                                   |
| [Finetune_PaliGemma_for_image_description.ipynb](PaliGemma/Finetune_PaliGemma_for_image_description.ipynb)     | Finetune PaliGemma for image description using [JAX](https://github.com/google/jax).                                                                                                    |

## Get help
Ask a Gemma cookbook-related question on the new [Build with Google AI Forum](https://discuss.ai.google.dev/), or open an [issue](https://github.com/google-gemini/gemma-cookbook/issues) on GitHub.

## Wish list
If you want to see additional cookbooks implemented for specific features/integrations, please send us a pull request by adding your feature request(s) in the [wish list](https://github.com/google-gemini/gemma-cookbook/blob/main/WISHLIST.md). 

If you want to make contributions to the Gemma Cookbook project, you are welcome to pick any idea in the [wish list](https://github.com/google-gemini/gemma-cookbook/blob/main/WISHLIST.md) and implement it.

## Contributing
Contributions are always welcome. Please read [contributing](https://github.com/google-gemini/gemma-cookbook/blob/main/CONTRIBUTING.md) before implementation.

Thank you for developing with Gemma! We’re excited to see what you create.

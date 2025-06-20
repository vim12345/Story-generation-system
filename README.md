# Story-generation-system

# Description:
A story generation system uses generative models to create coherent narratives or stories based on an initial input, prompt, or theme. These models typically use language models such as transformers or RNNs to learn patterns in text and generate creative and engaging stories. This project will focus on building a simple story generation system using a pre-trained language model such as GPT or LSTM to generate stories.

# ✅ What It Does:
* Uses a pre-trained GPT-2 model to generate coherent and creative stories.

* Tokenizer is used to convert the input text (prompt) into tokens, which the model processes to generate text.

* The generated story continues the input prompt in a coherent manner, producing a narrative that fits the context.

# Key features:
* GPT-2 model is fine-tuned for general language generation tasks and is capable of generating meaningful text.

* Temperature controls the randomness of predictions. A higher value (like 1.0) introduces more randomness, making the output more creative.

* No-repeat n-gram size helps in generating more coherent text by avoiding repetitive n-grams.

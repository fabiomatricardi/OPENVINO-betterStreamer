# OPENVINO-betterStreamer
Textual Interface for Gemma2-2B Openvino with streaming effect


---

* [AI structure data Extraction](https://github.com/fabiomatricardi/NuExtract-1.5-openvino) - A streamlit interface with [NuExtract-1.5-tiny](https://huggingface.co/numind/NuExtract-1.5-tiny) and openvino-genai to extract data from plain text into structured custom json formats. The Repo also gives a small tutorial on how to convert [NuExtract-1.5-tiny](https://huggingface.co/numind/NuExtract-1.5-tiny) into OpenVINO IR format.
* [StableLM-3B Chatbot](https://github.com/fabiomatricardi/OpenVINO-StableLM-3B-streamlit) - A streamlit CHATBOT interface with [stablelm-zephyr-3b](https://huggingface.co/stabilityai/stablelm-zephyr-3b) quantized in 4bit and optimum-intel. The Interface has a kind text streaming effect, and the number of turns are handled to not exceed the context window. The Model used is [published on Hugging Face Hub](https://huggingface.co/FM-1976/stablelm-zephyr-3b-openvino-4bit) and was created with the free HF Space hosting the [NCCF-quantization tool](https://huggingface.co/spaces/OpenVINO/nncf-quantization).
* [Gemma2-2b AI Chat App](https://github.com/fabiomatricardi/OpenVINO-Gemma2B-streamlit) - A beautiful Chat Interface, with interactive tuning parameters, powered by Optimum-Intel[openvino], Streamlit and the small but powerful Gemma2-2b-instruct model by Google. The model is an int4 quantized version, hosted on [Hugging Face Hub](https://huggingface.co/circulus/on-gemma2-2b-it-ov-awq-int4).
* [LaMini Power](https://github.com/fabiomatricardi/openvino-Lamini) - An experimental text based chat interface in the terminal running the [LaMini-Flan-T5-248M](https://huggingface.co/MBZUAI/LaMini-Flan-T5-248M) . This is a breakthrough made possible by openvino, because encoder-decoder model could not be quantized. The [LaMini model family](https://github.com/mbzuai-nlp/lamini-lm/) is a highly curated herd of very small models achieving strong accuracy even with only 512 tokens of context length.

[![Mentioned in Awesome OpenVINO](https://awesome.re/mentioned-badge-flat.svg)](https://github.com/openvinotoolkit/awesome-openvino)

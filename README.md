Hi,

This a just a slightly modified tutorial code for inferencing LLM using Unsloth FastModel/Fastlanguagemodel library. Normally, we used this library for testing our fine-tuned model in
Unsloth training. But however, we can also just use it as general LLM inference (similiar to transformer library by HuggingFace). All model from Huggingface is compatible with
this Unsloth library. The neat thing is that I believe/notice is slightly faster, better memory management slightly easier/consistent to inference compared to transformer library(and proper/better quantization support).

Just sharing this as I believe this library is rarely discuss for local LLM inference.

(Do use T4 gpu in colab as Fastmodel library only support GPU at the momemnt (to best of my knowledge))


Unsloth Original code link: https://colab.research.google.com/github/unslothai/notebooks/blob/main/nb/Gemma3_(4B).ipynb 

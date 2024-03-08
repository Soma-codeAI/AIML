# Open Source Models with Hugging Face

[Open Source Models with Hugging Face](https://www.deeplearning.ai/short-courses/open-source-models-hugging-face/)

## What you’ll learn in this course
The availability of models and their weights for anyone to download enables a broader range of developers to innovate and create.

In this course, you’ll select open source models from Hugging Face Hub to perform NLP, audio, image and multimodal tasks using the Hugging Face transformers library. Easily package your code into a user-friendly app that you can run on the cloud using Gradio and Hugging Face Spaces.

You will:

- Use the transformers library to turn a small language model into a chatbot capable of multi-turn conversations to answer follow-up questions.
- Translate between languages, summarize documents, and measure the similarity between two pieces of text, which can be used for search and retrieval.
- Convert audio to text with Automatic Speech Recognition (ASR), and convert text to audio using Text to Speech (TTS).
- Perform zero-shot audio classification, to classify audio without fine-tuning the model.
Generate an audio narration describing an image by combining object detection and text-to-speech models.  
- Identify objects or regions in an image by prompting a zero-shot image segmentation model with points to identify the object that you want to select.
- Implement visual question answering, image search, image captioning and other multimodal tasks.
- Share your AI app using Gradio and Hugging Face Spaces to run your applications in a user-friendly interface on the cloud or as an API. 

The course will provide you with the building blocks that you can combine into a pipeline to build your AI-enabled applications!

- Find and filter open source models on Hugging Face Hub based on task, rankings, and memory requirements.
- Write just a few lines of code using the transformers library to perform text, audio, image, and multimodal tasks.
- Easily share your AI apps with a user-friendly interface or via API and run them on the cloud using Gradio and Hugging Face Spaces.

## Who should join?
Anyone who wants to get started building AI applications quickly and easily using open source models.


## Acronyms 
- PET - Parameter Efficient training
- TRL - Transformer Reinforcement Learning
- Transformers and Accelerate Library 

## References

### NLP Models
- Conversational - blenderbot (facebook/blenderbot-400M-distill)[https://huggingface.co/facebook/blenderbot-400M-distill]
- Translaction - No Language Left Behind Model [facebook/nllb-200-distilled-600M](https://huggingface.co/facebook/nllb-200-distilled-600M)
- Summarization - BART (large-sized model), fine-tuned on CNN Daily Mail [facebook/bart-large-cnn](https://huggingface.co/facebook/bart-large-cnn)
- Sentence Similarity - sentence-transformers [sentence-transformers/all-MiniLM-L6-v2](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2)

### Audio Models
- Zero Shot Audio Classification(Feature Extraction) - CLAP: Contrastive Language-Audio Pretraining[laion/clap-htsat-unfused](https://huggingface.co/laion/clap-htsat-unfused)
- Automatic Speech Recognition - Distil-Whisper: distil-small.en [distil-whisper/distil-small.en](https://huggingface.co/distil-whisper/distil-small.en)
- Text to Speech -  VITS: Conditional Variational Autoencoder with Adversarial Learning for End-to-End Text-to-Speech[kakao-enterprise/vits-ljs](https://huggingface.co/kakao-enterprise/vits-ljs)

### Computer Vision 

- Object Detection - DETR (End-to-End Object Detection) model with ResNet-50 backbone [facebook/detr-resnet-50](https://huggingface.co/facebook/detr-resnet-50)
- Segmentation - Zigeng/SlimSAM-uniform-77 [Zigeng/SlimSAM-uniform-77](https://huggingface.co/Zigeng/SlimSAM-uniform-77)
- Depth Estimation - DPT-Hybrid (also known as MiDaS 3.0) [Intel/dpt-hybrid-midas](https://huggingface.co/Intel/dpt-hybrid-midas)

### Multi-Modal

- Image-text-matching - BLIP: Bootstrapping Language-Image Pre-training for Unified Vision-Language Understanding and Generation [Salesforce/blip-itm-base-coco](https://huggingface.co/Salesforce/blip-itm-base-coco)
- Image Captioning - BLIP: Bootstrapping Language-Image Pre-training for Unified Vision-Language Understanding and Generation [Salesforce/blip-image-captioning-base](https://huggingface.co/Salesforce/blip-image-captioning-base)


#### Websites / Papers Referenced: 

- [End-to-End Object Detection with Transformers](https://arxiv.org/abs/2005.12872)
- [Gradio](https://www.gradio.app/)
- [Segment Anything](https://segment-anything.com/)
- [isl-org/DPT](https://github.com/isl-org/DPT)
- [Vision Transformers for Dense Prediction](https://arxiv.org/abs/2103.13413) 


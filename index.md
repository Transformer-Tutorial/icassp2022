---
layout: home
title: ICASSP Tutorial
nav_exclude: true
seo:
  type: Course
  name: Just the Class
---

# Transformer Architectures for Multimodal Signal Processing and Decision Making

---

## Time and Location

Instructors: [Chen Sun](https://chensun.me) and [Boqing Gong](http://boqinggong.info/)

Sessions:
- Tuesday, 24 May 2022, 19:00 - 23:00 (UTC+8)
- Wednesday, 25 May 2022, 19:00 - 21:00 (UTC+8)
- Thursday, 26 May 2022, 19:00 - 23:00 (UTC+8)

## About

The Transformer neural architectures have become the de-facto model of choice in natural language processing (NLP). In computer vision, there has recently been a surge of interest in end-to-end Transformers, prompting the efforts to replace hand-wired features or inductive biases with general-purpose neural architectures powered by data-driven training. The Transformer architectures have also arrived at state-of-the-art performance in multimodal learning, protein structure prediction, decision making, and so on. 

These results indicate the Transformer architectures' great potential beyond the previously mentioned domains and in the signal processing (SP) community. We envision these efforts may lead to a unified knowledge base that produces versatile representations for different data modalities, simplifying the inference and deployment of deep learning models in various application scenarios. Hence, we believe it is timely to provide a short course on the Transformer architectures and related learning algorithms. 

In this short course, we plan to provide a deep dive into these neural architectures, understand how they work, and focus on their impacts on self-supervised learning, a technique that trains machine learning models without requiring labeled data, and multimodal learning, a technique that leverages multiple input sources, such as vision, audio, and text. We will also study recent attempts to interpret these models, thus revealing potential risks on model bias. This course aims at providing the audience with knowledge about the Transformer neural architectures and related learning algorithms so that they can apply them to their own research and further advance their state of the arts. 


## Learning Goals

We anticipate students will:
- Become familiar with self-attention and other building blocks of Transformers, the vanilla Transformer architecture, and its variations
- Learn about Transformers’ applications in computer vision and natural language processing: ViT, Swin-Transformers, BERT, GPT-3, etc.
- Understand supervised, self-supervised, and multimodal self-supervised learn algorithms to train a Transformer
- Acquire visualization methods to inspect a Transformer
- Learn advanced topics: related neural architectures (e.g., MLP-Mixer), applications in visual navigation, decision Transformers, etc.

## Resources

- [Prismia Signup](https://prismia.chat/projects/5c703ec5-5485-4b2c-b1f8-eac07660aad4/join)
- [Quiz](https://app.smartsheet.com/b/form/4bc75d2bdd764321980cff67c2f9195f)

## Pre-Reading

- [Convolutional neural networks](https://d2l.ai/chapter_convolutional-neural-networks/index.html)
- [Neural machine translation with recurrent neural networks and attention](https://www.tensorflow.org/text/tutorials/nmt_with_attention)
- [Attention is all you need](https://arxiv.org/abs/1706.03762)
- [Transformers for image recognition at scale](https://arxiv.org/abs/2010.11929)

## Syllabus

{% for module in site.modules %}
{{ module }}
{% endfor %}


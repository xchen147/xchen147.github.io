---
title: "PaLI: A Jointly-Scaled Multilingual Language-Image Model"
collection: publications
permalink: /publication/2022_PaLI_A_Jointly_Scaled_Multilingual_Language_Image_Model
excerpt: '__PaLI__ (**Pa**thways **L**anguage and **I**mage model) achieves state-of-the-art in multiple vision and language tasks (such as captioning, visual question-answering, scene-text understanding), while retaining a simple, modular, and scalable design.'
date: 2022-09-14
author: '*__Xi Chen__, Xiao Wang et al*'
venue: 'arXiv:2209.06794 (2022)'
paperurl: 'https://arxiv.org/abs/2209.06794'
blogurl: 'https://ai.googleblog.com/2022/09/pali-scaling-language-image-learning-in.html'

---

Effective scaling and a flexible task interface enable large language models to excel at many tasks. PaLI (Pathways Language and Image model) extends this approach to the joint modeling of language and vision. PaLI generates text based on visual and textual inputs, and with this interface performs many vision, language, and multimodal tasks, in many languages. To train PaLI, we make use of large pretrained encoder-decoder language models and Vision Transformers (ViTs). This allows us to capitalize on their existing capabilities and leverage the substantial cost of training them. We find that joint scaling of the vision and language components is important. Since existing Transformers for language are much larger than their vision counterparts, we train the largest ViT to date (ViT-e) to quantify the benefits from even larger-capacity vision models. To train PaLI, we create a large multilingual mix of pretraining tasks, based on a new image-text training set containing 10B images and texts in over 100 languages. PaLI achieves state-of-the-art in multiple vision and language tasks (such as captioning, visual question-answering, scene-text understanding), while retaining a simple, modular, and scalable design.

[Access the paper here](https://arxiv.org/abs/2209.06794)

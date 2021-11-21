---
title: "E-ViL: A Dataset and Benchmark for Natural Language Explanations in Vision-Language Tasks"
collection: publications
permalink: /publication/2021-iccv-evil
excerpt: ''
date: 2021-10-11
venue: 'International Conference on Computer Vision (ICCV)'
paperurl: 'https://openaccess.thecvf.com/content/ICCV2021/papers/Kayser_E-ViL_A_Dataset_and_Benchmark_for_Natural_Language_Explanations_in_ICCV_2021_paper.pdf'
citation: ''
---

## Abstract:

Recently, there has been an increasing number of efforts to introduce models capable of generating natural language explanations (NLEs) for their predictions on vision-language (VL) tasks. Such models are appealing, because they can provide human-friendly and comprehensive explanations. However, there is a lack of comparison between existing methods, which is due to a lack of re-usable evaluation frameworks and a scarcity of datasets. In this work, we introduce e-ViL and e-SNLI-VE. e-ViL is a benchmark for explainable vision-language tasks that establishes a unified evaluation framework and provides the first comprehensive comparison of existing approaches that generate NLEs for VL tasks. It spans four models and three datasets and both automatic metrics and human evaluation are used to assess model-generated explanations. e-SNLI-VE is currently the largest existing VL dataset with NLEs (over 430k instances). We also propose a new model that combines UNITER, which learns joint embeddings of images and text, and GPT-2, a pre-trained language model that is well-suited for text generation. It surpasses the previous state of the art by a large margin across all datasets. Code and data are available here: https://github.com/maximek3/e-ViL.


[Download paper here](https://openaccess.thecvf.com/content/ICCV2021/html/Kayser_E-ViL_A_Dataset_and_Benchmark_for_Natural_Language_Explanations_in_ICCV_2021_paper.html)

## BibTex:

@InProceedings{Kayser_2021_ICCV,
    author    = {Kayser, Maxime and Camburu, Oana-Maria and Salewski, Leonard and Emde, Cornelius and Do, Virginie and Akata, Zeynep and Lukasiewicz, Thomas},
    title     = {E-ViL: A Dataset and Benchmark for Natural Language Explanations in Vision-Language Tasks},
    booktitle = {Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV)},
    month     = {October},
    year      = {2021},
    pages     = {1244-1254}
}
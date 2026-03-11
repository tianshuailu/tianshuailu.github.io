---
permalink: /
title: "Tianshuai Lu"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, I am interested in NLP, CL (Computational Linguistics), and their intersection with digital humanities and philology, and currently looking for a PhD position in those areas.

Previously, I was a research engineer at [Media Technology Center](https://mtc.ethz.ch/), ETH Zurich, working on 1) LLM (Large Language Models) hallucination detection and mitigation in the faithful news summarization project; 2) RAG (Retrieval Augmented Generation) for knowledge intensive question-answering tasks.

I obtained my Master's degree from University of Zurich, where I worked on machine translation under the supervision of [Annette Rios](https://www.cl.uzh.ch/en/research-groups/accessibility/team/current-members/rios.html) and [Noëmi Aepli](https://noe-eva.github.io/) in the [CL department](https://www.cl.uzh.ch/en.html).

I also worked as a student assistant at the [Chair of Developmental Psychology: Adulthood](https://www.psychology.uzh.ch/en/areas/dev/lifespan.html) at University of Zurich, implementing experiments to facilitate research on prospective memory.

Overview of some work
======

I view NLP as an inherently interdisciplinary field. While working on reducing machine translation gender bias, I briefly read on how gender is represented in language and how models pick up gender biases, which are apparently present in the training data but also deeply rooted in language and culture. Addressing those issues requires the joint effort of computer science, linguistics, sociolinguistics, psychology, and more. This interdisciplinary perspective is a mindset I aim to carry into my future research.

Machine translation of low-resource languages
------
![Malayalam and its transliteration in Devanagari script](/images/malayalam.png){: .align-right width="400px"}
As a (high-resource) Indo-Aryan language, Hindi shares many linguistic features with Malayalam, a Southern Dravidian (low-resource) language. We built an English-Malayalam translation model leveraging [*sprachbund*](https://en.wikipedia.org/wiki/Sprachbund) (i.e., languages that are genetically unrelated but share many features due to geographical proximity and continuous contact throughout history) without using any English-Malayalam parallel corpus. Here are the [project report](/files/Master_Project_Report.pdf) and [GitHub repo](https://github.com/tianshuailu/NMT-Adapt_ml_IN).

Gender bias in machine translation
------
![gender representation in language](/images/gender_representation.png){: .align-right width="350px"}
This work utilizes a controlled text generation method, Future Discriminators for Generation (FUDGE), to reduce the so-called Speaking As gender bias emerging when translating from English to a language that openly marks the gender of the speaker. Here are the [paper](https://aclanthology.org/2023.gitt-1.6/) and the full-length [thesis](/files/tianshuai_lu_thesis.pdf).

## Presentation and talks

- Oral presentation of the paper [Reducing Gender Bias in NMT with FUDGE](https://aclanthology.org/2023.gitt-1.6/) at GITT workshop, [EAMT 2023](https://events.tuni.fi/eamt23/), Tampere, Finland.
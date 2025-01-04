## Projects and Publications

---

<h3 style="padding: 0px; margin: 0px;"><strong>Sign Language Sense Disambiguation</strong></h3>
<p style="padding: 0px; margin: 0px;"><small>Jana Grimm, Miriam Winkler, Oliver Kraus, Tanalp Agustoslu.LIMO 2024 @ KONVENS 2024. arXiv Preprint.</small></p>
<p style="padding: 0px; margin: 20px 0px;"></p>

📝 **Abstract:**
This project explores methods to enhance sign language translation of German sign language, specifically focusing on disambiguation of homonyms. Sign language is ambiguous and understudied which is the basis for our experiments. We approach the improvement by training transformer-based models on various bodypart representations to shift the focus on said bodypart. To determine the impact of, e.g., the hand or mouth representations, we experiment with different combinations. The results show that focusing on the mouth increases the performance in small dataset settings while shifting the focus on the hands retrieves better results in larger dataset settings. Our results contribute to better accessibility for non-hearing persons by improving the systems powering digital assistants, enabling a more accurate interaction. The code for this project can be found on [GitHub.](https://github.com/OvrK12/slt)

[View paper](https://arxiv.org/abs/2409.08780)

---

<h3 style="padding: 0px; margin: 0px;"><strong>LMU-BioNLP at SemEval-2024 Task 2: Large Diverse Ensembles for Robust Clinical NLI</strong></h3>
<p style="padding: 0px; margin: 0px;"><small>Zihang Sun, Danqi Yan, Anyi Wang, Tanalp Agustoslu, Qi Feng, Chengzhi Hu, Longfei Zuo, Shijia Zhou, Hermine Kleiner, Pingjun Hong, Suteera Seeha, Sebastian Loftus, Anna Barwig, Oliver Kraus, Jona Volohonsky, Yang Sun, Leopold Martin, Lena Altinger, Jing Wang, Leon Weber.In SemEval, ACL 2024 Workshop.</small></p>
<p style="padding: 0px; margin: 20px 0px;"></p>

📝 **Abstract:**
In this paper, we describe our submission for the NLI4CT 2024 shared task on robust Natural Language Inference over clinical trial reports. Our system is an ensemble of nine diverse models which we aggregate via majority voting. The models use a large spectrum of different approaches ranging from a straightforward Convolutional Neural Network over fine-tuned Large Language Models to few-shot-prompted language models using chain-of-thought reasoning.Surprisingly, we find that some individual ensemble members are not only more accurate than the final ensemble model but also more robust.

[View paper](https://aclanthology.org/2024.semeval-1.224/)

---

### Lispy - A Lisp dialect

Lispy is a functional programming language with an interpreted nature and a homoiconic design, drawing inspiration from the Lisp programming language developed in 1958. The interpreter is written in C, utilizing the MPC library for parsing operations. Lispy serves as an Interactive Prompt, enabling users to evaluate expressions in real-time or to evaluate external files written in the Lispy language.

[![](https://img.shields.io/badge/C-white?logo=C)](#) [![](https://img.shields.io/badge/Lisp-white?logo=Lisp)](#) [![](https://img.shields.io/badge/Ubuntu-white?logo=ubuntu)](#)

[View code on Github](https://github.com/agustoslu/lispy)

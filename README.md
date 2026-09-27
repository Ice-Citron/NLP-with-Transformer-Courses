# Natural Language Processing with Transformers — Study Notebooks

This repository contains my Jupyter notebooks for O'Reilly's *Natural Language 
Processing with Transformers*, by Lewis Tunstall, Leandro von Werra, and Thomas Wolf.

I worked through the book examples in Google Colab and added detailed
notes to help me understand the code and the underlying concepts.

This study was a part of my preparation for my IB Computer Science
Extended Essay. The later research examined different normalisation methods and
their positions within GPT-2 Transformer blocks.

**[Research repository — nanoGPT-Valkyrie][research]**

[Read the extended essay][paper]

## My work

The repository contains seven annotated study notebooks for Chapters
2 to 8. They combine the book examples with my notes and work in Colab.

The notes examine individual operations as well as Transformer model concepts.
Examples include tensor dimensions and the use of `torch.gather`.
Throughtout my study, I used ChatGPT to explore questions and queries I had 
during the whole process.

The `Original/` folders contain copies of the book notebooks.
These provide a reference beside my study versions.

## Chapter guide

Start with the study notebooks below.

| Chapter | Focus | My notebook |
|---|---|---|
| 2 | Text classification with DistilBERT | [Open][ch2] |
| 3 | Attention and Transformer architecture | [Open][ch3] |
| 4 | Multilingual named entity recognition | [Open][ch4] |
| 5 | Text generation and decoding methods | [Open][ch5] |
| 6 | Summarisation, BLEU, and ROUGE | [Open][ch6] |
| 7 | Question answering and document retrieval | [Open][ch7] |
| 8 | Model efficiency and knowledge distillation | [Open][ch8] |

Chapter 7 includes notes on Haystack and Elasticsearch.
Chapter 8 also contains notes on quantisation and model benchmarks.

### Chapter 10: Transformers from scratch

[Chapter 10](<Chapter 10/>) contains the original book notebook and
saved tokenizer files. It has no separate annotated study notebook.

- [Original notebook][ch10]
- [Tokenizer files](<Chapter 10/tokenizer/>)

The tokenizer folder contains the vocabulary and merge rules.
It also contains the tokenizer configuration and special-token settings.

## Repository structure

```text
NLP-with-Transformer-Study/
├── README.md
├── LICENSE
├── Chapter 2/                 # Text classification
├── Chapter 3/                 # Transformer architecture
├── Chapter 4/                 # Multilingual NER
├── Chapter 5/                 # Text generation
├── Chapter 6/                 # Summarisation
├── Chapter 7/                 # Question answering
├── Chapter 8/                 # Model efficiency
├── Chapter 10/
│   ├── Original/
│   └── tokenizer/
└── study-log/
```

Chapters 2 to 8 each contain my study notebook and an `Original/` folder.
The chapter numbers follow the book.

## References and acknowledgements

Tunstall, Lewis; von Werra, Leandro; and Wolf, Thomas.
*Natural Language Processing with Transformers: Building Language
Applications with Hugging Face.* O'Reilly Media, 2022.

The book and its [official notebooks][upstream] provide the source
examples for this study. The original authors retain credit for that work.

My later research code and results are available in
[nanoGPT-Valkyrie][research]. The [paper][paper] contains the full
research references and acknowledgements.

## Licence

This repository contains an [Apache License 2.0](LICENSE).

[research]: https://github.com/Ice-Citron/nanoGPT-Valkyrie
[paper]:
  https://drive.google.com/file/d/1dlhTgv4-A2cCYSsL00An_XpfGpg1DyWy/view
[upstream]: https://github.com/nlp-with-transformers/notebooks
[colab]: https://colab.research.google.com/
[ch2]: <Chapter 2/CS_EE_DistilBERT_notes.ipynb>
[ch3]: <Chapter 3/CS_EE_Transformer_Anatomy.ipynb>
[ch4]: <Chapter 4/CS_EE_Multilingual_NER.ipynb>
[ch5]: <Chapter 5/CS_EE_Text_Generation.ipynb>
[ch6]: <Chapter 6/CS_EE_Summarisation.ipynb>
[ch7]: <Chapter 7/CS_EE_Question_Answering.ipynb>
[ch8]: <Chapter 8/CS_EE_Transformer_Efficiency.ipynb>
[ch10]: <Chapter 10/Original/10_transformers-from-scratch.ipynb>

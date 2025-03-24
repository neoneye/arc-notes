# Datasets for ARC (Abstraction and Reasoning Corpus)

For simplicity, most of the datasets are contained in a [single repo](https://github.com/neoneye/arc-dataset-collection).

These datasets all follow the same json format as the original ARC dataset.

## ARC-AGI-2 - The current benchmark

- Repo: [arcprize/ARC-AGI-2](https://github.com/arcprize/ARC-AGI-2)
- Authors: François Chollet + ARC Prize + Task Contributors
- License: Apache-2.0

## ARC-AGI-1 - The previous benchmark

- Repo: [fchollet/ARC-AGI](https://github.com/fchollet/ARC-AGI/tree/master/data)
- Authors: François Chollet
- License: Apache-2.0

## Mini-ARC

- Repo: [MINI-ARC](https://github.com/KSB21ST/MINI-ARC)
- Authors: Subin Kim, Prin Phunyaphibarn, Donghyun Ahn, Sundong Kim
- License: Apache-2.0

## ConceptARC

- Repo: [ConceptARC](https://github.com/victorvikram/ConceptARC/tree/main/corpus)
- Authors: Arseny Moskvichev, Victor Vikram Odouard, Melanie Mitchell
- License: MIT

## 1D-ARC

- Repo: [khalil-research/1D-ARC](https://github.com/khalil-research/1D-ARC/tree/main/dataset)
- Authors: Yudong (Will) Xu, Wenhao Li, Pashootan Vaezipoor, Scott Sanner, Elias B. Khalil
- License: MIT

## Sequence\_ARC

- Repo: [Sequence_ARC](https://github.com/seedling123/Sequence_ARC)
- Authors: Seedling123
- License: Apache-2.0

## arc\_1d by optozoraz

- Repo: [optozorax/arc_1d](https://github.com/optozorax/arc_1d)
- [Visualization](https://optozorax.github.io/arc_1d/)
- Authors: Ilya Sheprut
- License: MIT

## ARC\_synthetic\_extend

- Repo: [ARC_synthetic_extend](https://github.com/frankaging/ARC_synthetic_extend)
- Authors: Zhengxuan Wu.
- License: MIT

## PQA: Perceptual Question Answering

- Paper: [arXiv](https://arxiv.org/abs/2104.03589)
- Paper: [Homepage](https://qugank.github.io/pqa.github.io/)
- Repo: [qugank/pqa.github.io](https://github.com/qugank/pqa.github.io)
- Authors: Yonggang Qi, Kai Zhang, Aneeshan Sain, Yi-Zhe Song
- License: Unspecified

## synth_riddles

- Repo: [synth_riddles](https://github.com/arc-community/synth_riddles)
- Authors: Andreas Köpf
- License: MIT

## ARC dataset tama

- Repo: [arc-dataset-tama](https://github.com/neoneye/arc-dataset-tama)
- Authors: Simon Strandgaard.
- License: MIT

## ARC dataset diva

- Repo: [arc-dataset-diva](https://github.com/neoneye/arc-dataset-diva)
- Authors: Simon Strandgaard.
- License: MIT

## ARC Community

- Repo: [arc-community/arc](https://github.com/arc-community/arc)
- Authors: Yannic Kilcher, Peter Nemeth, Jack Cole.
- License: Unspecified

## Optional ARC

What's special about this dataset? `Counter-examples`.
This dataset enhances the original ARC dataset, so every `test` pair have gotten 8 examples of what the output should NOT be.

- Repo: [Optional ARC](https://github.com/SoseSose/Optional-ARC)
- Authors: SoseSose
- License: Unspecified

## ARC Interactive

Captured interaction histories as users are solving ARC-AGI puzzles.
This may be relevant if you are trying to mimic what actions humans are performing.

- Repo: [ARC-Interactive-History-Dataset](https://github.com/neoneye/ARC-Interactive-History-Dataset)
- Authors: Simon Strandgaard
- License: MIT

## ARC Bad Predictions

This dataset contains incorrect predictions that are somewhat close to the target.
This may be relevant if your ARC-solver can repair on a previous prediction or does ranking of multiple solutions.

- Repo: [arc-bad-predictions](https://huggingface.co/datasets/neoneye/arc-bad-prediction)
- Authors: Simon Strandgaard
- License: MIT

# Task generators

## RE-ARC: Reverse-Engineering the Abstraction and Reasoning Corpus

- Repo: [RE-ARC](https://github.com/michaelhodel/re-arc/)
- Authors: Michael Hodel
- License: MIT

## ARC gym

- Repo: [ARC gym](https://github.com/SimonOuellette35/ARC_gym)
- Authors: Simon Ouellette
- License: Unspecified

## BabyARC

- Repo: [BabyARC](https://github.com/frankaging/BabyARC)
- Authors: Zhengxuan Wu.
- License: MIT

## ARC Generative DSL

- Repo: [arc-generative-DSL-infinite-data](https://github.com/arc-community/arc-generative-DSL-infinite-data)
- Authors: Jack Cole, James Enouen.
- License: Unspecified

## ARC-Generator

- Repo: [ARC-Generator](https://github.com/Krzysiulek/ARC-Generator)
- Authors: Krzysztof Czarnecki
- License: Unspecified

## ARC-HTML

- Repo: [pfletcherhill/mini-arc](https://github.com/pfletcherhill/mini-arc) - Unfortunately the project name clashes with the popular `MiniARC` dataset.
- Authors: Paul Fletcher-Hill
- License: Unspecified
- Comment: The 43 puzzle generators are html files, so it's non-trivial to extract an ARC like json file.

# Corrections to the original ARC dataset

- Code: [data-preprocessing-correcting-tasks-with-errors](https://www.kaggle.com/code/ademiquel/data-preprocessing-correcting-tasks-with-errors/notebook)
- Authors: Alejandro de Miquel
- License: Unspecified


# Communicating Natural Programs to Humans and Machines

- Repo: [LARC - Language-complete Abstraction and Reasoning Corpus](https://github.com/samacqua/LARC)
- Authors: Samuel Acquaviva, Yewen Pu, Marta Kryven, Theodoros Sechopoulos, Catherine Wong, Gabrielle E Ecanow, Maxwell Nye, Michael Henry Tessler, Joshua B. Tenenbaum.
- License: MIT


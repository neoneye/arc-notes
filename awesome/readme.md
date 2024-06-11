# Awesome ARC (Abstraction and Reasoning Corpus)

*Links to awesome resources.* 

## News and status

* [ARC Prize](https://arcprize.org/) - ARC Prize is a $1,000,000+ public competition to beat and open source a solution to the ARC-AGI benchmark.
* [Kaggle - ARC Prize 2024](https://www.kaggle.com/competitions/arc-prize-2024) - Submit solutions here.
* [lab42.global/arcathon](https://lab42.global/arcathon/) - This was where ARCathon 2022 and ARCathon 2023 was hosted. ARCathon is now ARC Prize.
* [ARCathon news and publications](https://lab42.global/arcathon/updates/) - The newest publications are interesting to read.
* [Dataset-Induced Meta-Learning and other tricks: Improving model efficiency on ARC](https://lab42.global/community-post-model-efficiency/) - What is status of ARC in late 2023.
* [ARC: Interview with Jack Cole](https://lab42.global/arc-interview/) - Status of ARC early 2024. Interview with the ARC World Record Holder, Jack Cole, solving 34 of the 100 hidden tasks.
* [ARC: Where do we stand today?](https://lab42.global/arc-article/) - Status of ARC mid 2023.

## Leaderboard

* [2024 - Leaderboard - ARC Prize](https://arcprize.org/leaderboard) - Pretty formatted leaderboard.
* [2024 - Leaderboard - Kaggle](https://www.kaggle.com/competitions/arc-prize-2024/leaderboard) - The usual kaggle style. 
* [2022,2023,2024 - Leaderboard](https://lab42.global/arcathon/leaderboard/) - This may be of historical interest. The best team solved 34 tasks out of 100 hidden tasks. 
* [2020 - Leaderboard](https://www.kaggle.com/competitions/abstraction-and-reasoning-challenge/leaderboard) - This may be of historical interest. The best team solved 21 tasks out of 100 hidden tasks.

## Discord

* [ARC Prize](https://discord.gg/9b77dPAmcA) - The entire Discord server is about ARC.
* [Lab42 Discord server](https://discord.gg/waRCYPEc6C) - Several channels for discussing ARC.
* [Yannic Kilcher's Discord server](https://ykilcher.com/discord) - Every Sunday 1700 UTC there is a voice meeting for only discussing ARC.
* [John's AI Group Discord server](https://discord.gg/bzp87AHJy5) - Follow progress of Tan John Chong Min's ARC project.


## Wiki

* [ARC community wiki](https://github.com/arc-community/arc/wiki) - Contains analysis of several of the 800 tasks.


## Editors

* [ARCreate](https://arc-editor.lab42.global/) - Contribute with new tasks to the ARC 2 dataset.
* [The original ARC testing interface](https://github.com/fchollet/ARC/tree/master/apps) - Edit train and test pairs. No backend required.
* [BrainGridGame](https://braingridgame.com/), [repo](https://github.com/neoneye/ARC-Interactive), [dataset](https://github.com/neoneye/ARC-Interactive-History-Dataset) - What kind of interactions does humans do when solving an ARC task. This project captures the interaction history and continuesly updates the dataset with interaction histories.
* [O2ARC](https://o2arc.com/), [repo](https://github.com/GIST-DSLab/O2ARC_V2), [repo](https://github.com/KSB21ST/MINI-ARC/) - Editor with ability to record user interaction while solving an ARC task.
* [ARC-Game](https://volotat.github.io/ARC-Game/), [repo](https://github.com/volotat/ARC-Game) - The ARC 1 dataset made into a fun game that runs in the browser.
* [arc-site](https://github.com/victorvikram/arc-site) - Edit train and test pairs. It runs in the browser, without backend.
* [arc-app](https://github.com/victorvikram/arc-app) - Seems to be react, with frontend and server.
* [arc-level-editor](https://github.com/arc-community/arc-level-editor) - Edit train and test pairs. Requires a nodejs installation.


## Tools

* [mxbi/arckit](https://github.com/mxbi/arckit) - Python and command-line tools for easily working with the ARC dataset.
* [arc-dsl](https://github.com/michaelhodel/arc-dsl) - Solutions to all 400 training tasks of the ARC dataset.
* [Console for inspecting ARC tasks](https://github.com/neoneye/arc-console) - Printing ARC images to the console can get messed up. Instead I have made a web server for viewing ARC images. It uses a websocket between the browser and the webserver (but you don't have to worry about the websocket). You can view an image by sending a POST request, and the image gets appended at the bottom of the web page.
* [Predicting the output size of an ARC task](https://github.com/neoneye/arc-output-size) - Using the command line tool for making better guesses about the output size.
* [ARCLE - ARC Learning Environment](https://github.com/ConfeitoHS/arcle) - Abstraction and Reasoning Corpus as a Farama Gymnasium environment.
* [simon-arc-env](https://github.com/neoneye/simon-arc-env) - Abstraction and Reasoning Corpus as a Farama Gymnasium environment.

## How does humans solve ARC

* [ARC-eyetracking](https://github.com/lbakst/ARC-eyetracking) - uses PsychoPy for eye tracking.
* [ARC-behavioral](https://github.com/ahn-cj/ARC-behavioral) - has an interesting video explaining how [the eye tracking works with ARC](https://github.com/ahn-cj/ARC-behavioral/blob/main/demo/training/mturk_tutorial.mov).
* [human-arc](https://github.com/MichaelPascale/human-arc) - eye tracking.

## Prompt and language

* [Dataset-Induced Meta-Learning (and other tricks): Improving model efficiency on ARC](https://lab42.global/community-post-model-efficiency/) - by 
Jack Cole and Mohamed Osman.
* [Large Language Models as General Pattern Machines](https://general-pattern-machines.github.io/) - Solves 85 of 800 tasks.
* [GPT4 solving LARC tasks](https://github.com/evanthebouncy/larc_gpt4) - Solving ARC tasks using the LARC human descriptions with GPT4, solves 139 of 384 tasks.
* [Tan John Chong Min's ARC prompts](https://github.com/tanchongmin/ARC-Challenge) - Solves 50 of 111 training set problems!
* [Andreas Köpf's arc-agents](https://github.com/andreaskoepf/arc-agents) - Solving ARC tasks with CodeLlama, Llama2, WizardCoder or similar language models, solves 45 of 800 tasks.
* [Simon Strandgaard's ARC prompts](https://github.com/neoneye/arc-prompt) - Experiments solving ARC tasks with GPT4 or similar language models, solves 39 of 800 tasks.
* [ARC_LLMs: Keeping track of LLM progress on ARC](https://github.com/alxndrTL/ARC_LLMs), [website source code](https://github.com/alxndrTL/alxndrTL.github.io/tree/master/ARC) and [visualization](https://alxndrtl.github.io/ARC/) - Visualize what ARC tasks gets solved (or not) by LLMs!.
* [Fast and flexible: Human program induction in abstract reasoning tasks](https://arc-visualizations.github.io/) and [repo](https://github.com/arc-visualizations/arc-visualizations.github.io) - by Aysja Johnson, Wai Keen Vong, Brenden M. Lake and Todd M. Gureckis.


## Videos

* [Videos about ARC](https://github.com/neoneye/arc-notes/tree/main/videos%20about%20arc) - Introduction to ARC, interviews with experts, experiments with language models.


## Datasets

* [Datasets for ARC](https://github.com/neoneye/arc-notes/tree/main/datasets) - Links to datasets that use the ARC format.

## Best implementations

* [Mehran Kazeminia - ensemble](https://www.kaggle.com/code/mehrankazeminia/arc2023-end-to-end-v7) - Solves 31 out of 100 hidden tasks.
* [Michael Hodel - ensemble](https://www.kaggle.com/code/michaelhodel/arc-ensemble/notebook) - Solves 31 out of 100 hidden tasks.
* [Phil Dhingra - ensemble](https://www.kaggle.com/code/philipkd/arc-late-submission-1st-and-3rd-place-ensemble) - Solves 29 out of 100 hidden tasks.
* [taka or team `armo` - ensemble](https://github.com/tien2020le2020/arc_baseline/tree/arc_tree7) - Solves 29 out of 100 hidden tasks. The code is not on the `main` branch.
* [icecuber](https://github.com/top-quarks/ARC-solution) - Solves 21 out of 100 hidden tasks. Kaggle 2021 - 1st place.
* [Alejandro & Roderic & Yuji](https://github.com/alejandrodemiquel/ARC_Kaggle) - Solves 19 out of 100 hidden tasks. Kaggle 2021 - 2nd place.
* [Vlad & Ilia](https://www.kaggle.com/code/ilialar/3rd-place-end-to-end-solution/notebook), [repo](https://github.com/IliaLarchenko/abstract_reasoning) - Solves 19 out of 100 hidden tasks. Kaggle 2021 - 3rd place.
* [Puzzlemaster](https://github.com/artyompal/kaggle-abstract-reasoning) - Solves 14 out of 100 hidden tasks.
* [Maciej Sypetkowski + Michał Sypetkowski](https://github.com/maciej-sypetkowski/kaggle-arc-solution) - Solves 8 out of 100 hidden tasks.
* [Simon Strandgaard](https://github.com/loda-lang/loda-rust) - Solves 8 out of 100 hidden tasks.
* [Michael Hodel](https://github.com/michaelhodel/arc-dsl) - Solves 6 out of 100 hidden tasks.
* [Anastasia Karpovich](https://www.kaggle.com/code/user189546/5-crop-tasks-by-brute-force) - Solves 5 out of 100 hidden tasks.
* [Andy Penrose](https://www.kaggle.com/code/andypenrose/macro-dsl-for-arc-with-heuristic-search/notebook) - Solves 4 out of 100 hidden tasks.
* [Sébastien Ferré](https://github.com/sebferre/ARC-MDL) - Solves 3 out of 100 hidden tasks.
* [Naoya Tanahashi](https://github.com/Naoism/kaggle_Abstraction_and_Reasoning_Challenge) - Solves 3 out of 100 hidden tasks.
* [Robert Lizée](https://github.com/robertlizee/arc-solver) - Solves 1 out of 100 hidden tasks.

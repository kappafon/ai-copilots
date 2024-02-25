---
title: How LLMs are trained
tags:
  - LLM
---
In the training phase [[LLM]]s absorb all the available data. Then convert words, characters and other symbols to numbers aka tokens. The tokens become the vocabulary of the language. So in turn the more complex the language is, the more complex the vocabulary.

After the tokenization, models go through training phases. Where given different inputs they try to determine the probability of what the next token should be. And they do it until they form the message sent back to you.

Most of the training is a statistical analysis of the tokens, that determines the most likely next token. But **that** is followed by human led reinforcement. So the models and their predictions get _"better"_[^is-it] over time as they are trained on human preference.

[^is-it]: [Coding on Copilot: 2023 Data Suggests Downward Pressure on Code Quality (incl 2024 projections) - GitClear](https://www.gitclear.com/coding_on_copilot_data_shows_ais_downward_pressure_on_code_quality)


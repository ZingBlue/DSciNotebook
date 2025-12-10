# DATASCI 302W Project

This repository is a report and analysis of perceptions artificial intelligence (AI) prior to the introduction of generative AI.

Primary data set: <https://github.com/AdaLovelaceInstitute/how-do-people-feel-about-ai>

## Description and Goals

This project explores demographic differences in attitudes toward AI, produce summary visualizations, provides statistical models (e.g., subgroup comparisons and regression) to understand these differences. To view the report, see the exploratory analysis notebook: [EDA-Notebook.html](./EDA-Notebook.html).

In some ways, the data we use is a bit special: recorded in late 2022, the data provides insight into how lay people in the UK perceived AI *prior* to the mass adoption of generative AI technologies.
As a result, (by induction) we learn about how people perceive classical (aka non-generative) AI *today*.
In lay terms, classical AI is a form of AI created to solve a very specific problem.
Typical applications of classical AI include organizing social media feeds, facial recognition, solving puzzles (such as mazes, chess, etc...), etc...
In contrast, generative AI (such as ChatGPT) generates and transforms data.
In practice, this output data often comes in the form of text, visual art, and music.

Since classical AI and generative AI are often conflated nowadays (generative AI has taken grasp of the [mind](https://en.wikipedia.org/wiki/AI_takeover) and [hearts](https://people.com/man-proposed-to-his-ai-chatbot-girlfriend-11757334) of the public in the past few years),
it is difficult to determine how the public views classical AI.

Thus, our best impression of how the public perceives classical AI *today* is best recorded in *late 2022* - exactly when our data set was recorded!

Our project aims to understand how lay people perceive classical AI and its applications, in particular, we became curious about how demographics (such as age, sex, etc...) impact these perceptions.

## Repository Information

The folder structure is straightforward: the most important file is [EDA-Notebook.Rmd](./EDA-Notebook.Rmd), this file contains the code to compile "knit" [EDA-Notebook.html](./EDA-Notebook.html) (the final report with our results). To read our report, open [EDA-Notebook.html](./EDA-Notebook.html).

Our data set is located in the folder [how-do-people-feel-about-ai-main](./how-do-people-feel-about-ai-main) (and in the GitHub repo mentioned at the beginning of this document)

Aside from this, there are some operational files and folders such as [renv](./renv) and [.gitignore](./.gitignore) but these exist to supplement and the programming and collaboration process, they have little to do with the research itself.

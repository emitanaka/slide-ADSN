The Grammar of Experimental Design

15 min talk

The critical role of data collection is well captured in the expression "garbage in, garbage out" -- in other words, if the collected data is rubbish then no analysis, however complex it may be, can make something out of it. The gold standard for data collection is through well-designed experiments.  Re-running an experiment is generally expensive, contrary to statistical analysis where re-doing it is generally low-cost; there's a higher stake in getting it wrong for experimental designs. But how do we design experiments in R? In this talk, I present my R-package edibble that implements a novel framework, which I refer to as the "grammar of experimental design", to facilitate the data collection and design of an experiment. The grammar builds the experimental design by describing the fundamental components of the experiment. Because the grammar resembles a natural language, there is greater clarity about the experimental structure, and includes considerations beyond the construction of the experimental layout. I will reconstruct some experimental layout using edibble with comparison to other popular R-packages. 

## Figure

tidyverse is well suited for the data science project workflow as illustrated below in (B) (from [Grolemund and Wickham 2017](https://r4ds.had.co.nz/introduction.html)). For experimental data, the statistical aspect begins before obtaining data as depicted below in (A). The focus of `edibble` is to facilitate work in (A).

Submission ID: **fee5551cf289165ce97dde77eff2dcfd**

- *Elevator pitches* replace poster sessions. If your abstract is accepted, you can decide whether you want to present your project as a technical note or as a pre-recorded lightning talk of 4–5 minutes. Presenters will attend their designated elevator pitch session for Q&A and networking.

# Assignment: Visualization Project

**The Art and Science of Empirical Computer Science (Fall 2022)**

At a high-level, for this visualization project, I would like you to perform exploratory data analysis on a bibliometric dataset of your choice.
From this exploration, I would like you to come up with one or more interesting observations or questions to ask.
And then, I would like you to build a visualization that either "makes the points" or answers the questions that you posed.

Perhaps it's easiest to illustrate what I'm looking for by example:

[**UWaterloo CS Collaboration Graph**](https://observablehq.com/d/65672db51a1d6200).
Each year before hiring season, Ian Goldberg scrapes information from DBLP to construct the (collaboration) co-authorship graph for the faculty members in the School.
It's something useful to show faculty candidates who would like to learn more about the composition of the School.
Jian Zhao took the raw data and produced the visualization in the above link.

[**What are the top Canadian universities for AI research?**](https://lintool.github.io/csranking-aica/).
This is a visualization created by [Alan Wu](https://wuliwei.xyz/), a Ph.D. student in [WatVis Lab](http://www.jeffjianzhao.com/), under my guidance.
The goal is quite straightforward: this visualization tries to answer the question, "What are the top Canadian universities for AI research?" based on data from [CSRankings](http://csrankings.org/).

[**Waterloo AI Institute Co-Authorship Graph**](https://toluclassics.github.io/wai/).
This visualization was created by [Odunayo Ogundepo](https://toluclassics.github.io/wai/), one of my Master's students, under my guidance.
The AI Institute prides itself on a multi-disciplinary approach to AI, which I wanted to illustrate.
This is the result.

[**Big Cows 🐮: Information Retrieval**](https://lintool.github.io/bigcows/index-ir.html).
This is a personal project of mine that started over a decade ago for my own tenure case at the University of Maryland.
The tenure application process at Maryland mandated a bibliometric analysis of the candidate being considered for promotion, specifically in relationship to peers.
This site arose from a simple interface to display the data, but has evolved over time to include many IR researchers.

This project will be completed individually, but I will allow, with prior permission, larger projects that may involve sharing code (e.g., a common data crawler that you collaborate on building) or data (e.g., a large dataset that you perform data cleaning on together, but analyze individually).
However, in the end, each student will be responsible for producing a final, distinct visualization.
If you are interested in doing something along these lines, please get in touch with me as soon as possible.

## Sources of Data

The following are data sources that might serve as starting points.
In some cases the datasets offer bulk downloads; some offer APIs; for others, you'll have to write web scrapers.

+ [Google Scholar](https://scholar.google.com/): Of course, probably the most extensive source of bibliometric data... but for most data you'll have to scrape.
+ [Semantic Scholar](https://www.semanticscholar.org/) by AI2: provides bulk download options as well as an extensive API.
+ [DBLP](https://dblp.org/) (try querying using [QLever](https://qlever.cs.uni-freiburg.de/dblp))
+ [CSRankings](https://csrankings.org/)

## Project Ideas

Some of the figures in the book are good sources of inspiration.
You might build a visualization that could automatically create a particular figure.
For example:

+ Figure 2.1: Plotting the _h_-indexes for computer scientists.
+ Figure 5.1: Plotting the "drop pin" diagram of a scientist's impact.

Another source of projects might be variations of the ideas underlying the visualizations presented above.
For example, we know what the UWaterloo CS collaboration graph looks like.
How does it compare to other top Canadian departments (e.g., Toronto)?
What about top CS departments in the US?

# Perplexing_Perplexities

The _[t-distributed Stochastic Neighbour Embedding](https://lvdmaaten.github.io/tsne/)_ (t-SNE) algorithm has an interesting parameter called 'perplexity'. The effect of perplexity was spectacularly highlighted in the article, _[How to Use t-SNE Effectively](https://distill.pub/2016/misread-tsne/)_. If I've understood it correctly, perplexity correlates to the number of nearby datapoints, or "neighbours", for every datapoint in lower-dimensional space. Changing this parameter severely impacts the resulting plot.

This was super interesting, so I wanted to play around with it for myself.

Modifying van der Maaten's [python implementation](https://lvdmaaten.github.io/tsne/code/tsne_python.zip), and using [MatPlotLib](https://matplotlib.org/) for the visualisation, I created animations to have a look at how perplexity affects simplistic datasets.

![](tSNE_animation.gif)

> More to come.